---
layout: post
title: "Apache Maven 3.6.1 Released"
date: '2019-04-13T11:08:32+00:00'
permalink: apache-maven-3-6-1
categories:
  - Maven
  - Maven-Releases
---
The Apache Maven team is pleased to announce the release of the Apache
Maven 3.6.1.

Apache Maven is a software project management and comprehension tool. Based
on the concept of a project object model (POM), Maven can manage a
project's build, reporting and documentation from a central piece of
information.

You can find out more about Apache Maven at https://maven.apache.org

You can download the appropriate sources etc. from
the [download page](https://maven.apache.org/download.cgi)

<!-- more -->

We really value the contributions of these non committers, so this section is
focused on those individuals. Descriptions of the issues fixed can be found at
the [end of these release notes](#Details).

Issue Reporters of this release:

* [MNG-5705] Ondra Žižka
* [MNG-5965] Matthias Schmalz
* [MNG-6059] Andreas Sewe
* [MNG-6159] Christian Aistleitner
* [MNG-6213] Jin Kwon
* [MNG-6256] Christoph Etzel
* [MNG-6261] Dawid Weiss
* [MNG-6262] Gene Smith
* [MNG-6346] Patrik Jetzer
* [MNG-6374] Rohan Padhye
* [MNG-6495] Elliotte Rusty Harold
* [MNG-6506] Andreas Veithen
* [MNG-6526] Olaf Otto
* [MNG-6529] Michael Istria
* [MNG-6530] Michael Istria
* [MNG-6533] Michael Istria
* [MNG-6543] Romain Manni-Bucau
* [MNG-6558] Guy Brand
* [MNG-6577] Rohan Padhye
* [MNG-6591] Olaf Otto
* [MNG-6605] Gunnar Wagenknecht
* [MNG-6618] Viacheslav Yakunin

Code Contributors of this release:

* [MNG-6374] Gabriel Belingueres (indirectly via plexus-utils PR)
* [MNG-6529] Michael Istria
* [MNG-6530] Michael Istria
* [MNG-6558] Guy Brand
* [MNG-6261] Fabiano C. de Oliveira
* [MNG-6533] Michael Istria


Many thanks to all reporters and contributors for their time and support.

(Please send an email to the dev list if we missed one to mention).

## Preliminary Testers

Thanks to the following preliminary testers:

* Gabriel Belingueres
* Francois Papon
* Eric Lilja

## Known Issues

If you are using Maven reporting, it might happen that you will get an exception which looks like this:

```
[INFO] Scanning for projects...
[ERROR] Internal error: java.lang.NullPointerException -> [Help 1]
org.apache.maven.InternalErrorException: Internal error: java.lang.NullPointerException
    at org.apache.maven.DefaultMaven.execute (DefaultMaven.java:120)
...
Caused by: java.lang.NullPointerException
    at org.apache.maven.model.plugin.DefaultReportingConverter.convert (DefaultReportingConverter.java:243)
...
```

This is caused by using a `<reportSet>..</reportSet>` which does not contain
a `<report></report>` element.

Temporarily this issue can circumvent by adding an empty `<report></report>` element
inside the `<reportSet></reportSet>`.

An [issue has been created][MNG-6636] to track the fix.

[MNG-6636]: https://issues.apache.org/jira/browse/MNG-6636

## Overview about the changes

- An issue has been fixed causing multiple executions of plugin goals, related to
  using parallel build options like `mvn plugin:goal -T 4`. This resulted in duplicated
  executions of phases. This has been fixed with [MNG-5965].

- NullPointerException related to call in parallel build like `mvn -T 1C clean javadoc:aggregate`
  [MNG-5705]

- A performance issue related to artifact transfer has been found related to [WAGON-537]. It
  has been solved via the update to [Maven Wagon 3.3.1][MNG-6526].

- There had been issues related calling Maven script like this: `mvn -f ..`
  - Having parentheses within the path, which has been fixed with [MNG-6346].
  - Script can break having special characters as part of the path, which has
    been solved with [MNG-6256].


- Issue related to the Maven Resolver API which broke some IDEs (for example https://youtrack.jetbrains.com/issue/IDEA-201282);
  this has been fixed by [MNG-6538].

- Issue related to missing event for ToolchainsBuildingResult on EventSpy [MNG-6558].

- Issue related to support Java 9+ `ClassLoader.findClass(String moduleName, String name)` in Mojos.
  This has been fixed with [MNG-6543].

- Improvement about the memory consumption has been done with [MNG-6571].

- Issue related to relative parent POM resolution failing in 3.5.0 with complex multimodule builds
  has been fixed with [MNG-6261].

- Missing export for org.slf4j.event.Level has been done with [MNG-6618]


## User visible Changes

Maven has now a an option to suppress the transfer progress when downloading/uploading
in interactive mode.

```
mvn --no-transfer-progress ....
```
or in short:

```
mvn -ntp ... ....
```

There had been an issues like [MNG-6505] and [MNG-6059] related to the construction of
URL's etc. within `distributionManagement` and `scm` part in the pom for multi module
builds like this:


```
<scm child.scm.connection.inherit.append.path="true"
     child.scm.developerConnection.inherit.append.path="true"
     child.scm.url.inherit.append.path="true" />
<distributionManagement>
   <site child.site.url.inherit.append.path="true" />
 </distributionManagement>
```

Detailed explanations can be found in [Inheritance Assembly][inheritance-assembly] and in [MNG-6059]


[inheritance-assembly]: https://maven.apache.org/ref/3.6.1/maven-model-builder/index.html#Inheritance_Assembly

## The detailed issue list[](#Details)

### Bugs:

- [MNG-5705](https://issues.apache.org/jira/browse/MNG-5705) - NPE on parallel build in BuilderCommon.handleBuildError(BuilderCommon.java:147)
- [MNG-5965](https://issues.apache.org/jira/browse/MNG-5965) - Parallel build multiplies work if multiple goals are given
- [MNG-5995](https://issues.apache.org/jira/browse/MNG-5995) - Maven itself cannot run without maven-compat
- [MNG-6256](https://issues.apache.org/jira/browse/MNG-6256) - Maven script can break if "-f" path contains special characters
- [MNG-6261](https://issues.apache.org/jira/browse/MNG-6261) - Relative parent POM resolution failing in 3.5.0 with complex multimodule builds
- [MNG-6262](https://issues.apache.org/jira/browse/MNG-6262) - getCanonicalFile() is not used consistently during project resolution
- [MNG-6346](https://issues.apache.org/jira/browse/MNG-6346) - ... was unexpected at this time when using -f option and path contains brackets
- [MNG-6374](https://issues.apache.org/jira/browse/MNG-6374) - ModelBuilder hangs with malformed pom.xml
- [MNG-6429](https://issues.apache.org/jira/browse/MNG-6429) - Integration Test site publishing requires Java 7 (or javadoc errors ignored)
- [MNG-6495](https://issues.apache.org/jira/browse/MNG-6495) - ModelResolver cannot be null
- [MNG-6505](https://issues.apache.org/jira/browse/MNG-6505) - child.(x.y).inherit.append.path value should be inherited
- [MNG-6506](https://issues.apache.org/jira/browse/MNG-6506) - Mojos are unable to load package annotations on Java >= 9
- [MNG-6529](https://issues.apache.org/jira/browse/MNG-6529) - `ProjectBuilder.build(List<File> projects, boolean, ProjectBuildingRequest)` doesn't honor `ProjectBuildingRequest.isResolveDependencies()`
- [MNG-6530](https://issues.apache.org/jira/browse/MNG-6530) - Regression in ProjectBuilder when file change between invocations (introduced by MNG-6311)
- [MNG-6533](https://issues.apache.org/jira/browse/MNG-6533) - `ProjectBuilder.build(list_of_projects,...)` does not contain MavenProject in exception report
- [MNG-6543](https://issues.apache.org/jira/browse/MNG-6543) - Upgrade plexus classworld to support java 9+ `ClassLoader.findClass(String moduleName, String name)` in Mojos
- [MNG-6558](https://issues.apache.org/jira/browse/MNG-6558) - ToolchainsBuildingResult event is not sent on EventSpy
- [MNG-6577](https://issues.apache.org/jira/browse/MNG-6577) - pom.xml: Uncaught IllegalArgumentException when parsing unicode entity ref
- [MNG-6590](https://issues.apache.org/jira/browse/MNG-6590) - DefaultProjectArtifactsCache java.lang.IllegalStateException: Duplicate artifact resolution result
- [MNG-6599](https://issues.apache.org/jira/browse/MNG-6599) - unknown version in model id when version is defined from parent

### Improvements

- [MNG-6059](https://issues.apache.org/jira/browse/MNG-6059) - Important use cases not covered, as child.inherit.append.path affects all children
- [MNG-6159](https://issues.apache.org/jira/browse/MNG-6159) - Child path adjustments break git scm urls
- [MNG-6213](https://issues.apache.org/jira/browse/MNG-6213) - Maven doesn't check the validity of scope value
- [MNG-6481](https://issues.apache.org/jira/browse/MNG-6481) - Allow to compile and test Maven with Java 11
- [MNG-6513](https://issues.apache.org/jira/browse/MNG-6513) - Replace depreated Plexus javadoc tags with annotations in ITs
- [MNG-6515](https://issues.apache.org/jira/browse/MNG-6515) - Fix javadoc build errors under Java 8 and 11
- [MNG-6520](https://issues.apache.org/jira/browse/MNG-6520) - Update assembly descriptors to 2.0.0
- [MNG-6522](https://issues.apache.org/jira/browse/MNG-6522) - Prepare Maven's Core Integration Test Suite to test with Java 12 and 13-ea
- [MNG-6572](https://issues.apache.org/jira/browse/MNG-6572) - use int or long instead of BigIntegers for little numbers in ComparableVersion
- [MNG-6593](https://issues.apache.org/jira/browse/MNG-6593) - track input location for super-pom
- [MNG-6597](https://issues.apache.org/jira/browse/MNG-6597) - add input location tracking for plugins configuration
- [MNG-6600](https://issues.apache.org/jira/browse/MNG-6600) - add input location tracking for default lifecycle bindings executions
- [MNG-6601](https://issues.apache.org/jira/browse/MNG-6601) - add input location tracking for site's reportPlugins injected by reports conversion
- [MNG-6605](https://issues.apache.org/jira/browse/MNG-6605) - Allow to suppress download messages in interactive mode
- [MNG-6611](https://issues.apache.org/jira/browse/MNG-6611) - Update animal-sniffer-maven-plugin to 1.17

### Wish

- [MNG-6571](https://issues.apache.org/jira/browse/MNG-6571) - Maven memory consumption issue

### Task

- [MNG-6538](https://issues.apache.org/jira/browse/MNG-6538) - Upgrade Maven Artifact Resolver to 1.3.3 to restore API
- [MNG-6544](https://issues.apache.org/jira/browse/MNG-6544) - Replace CacheUtils#{eq,hash} with Objects
- [MNG-6573](https://issues.apache.org/jira/browse/MNG-6573) - Use latest Maven 3.6.0 to build Maven Core and plugins with ASF CI
- [MNG-6618](https://issues.apache.org/jira/browse/MNG-6618) - Maven doesn't export org.slf4j.event.Level

### Dependency upgrade

- [MNG-6526](https://issues.apache.org/jira/browse/MNG-6526) - Upgrade to Wagon 3.3.1 (from 3.2.0)
- [MNG-6591](https://issues.apache.org/jira/browse/MNG-6591) - Upgrade to Wagon 3.3.2


The full list of changes can be found in our [issue management system][4].

## Complete Release Notes

See [complete release notes for all versions][5]

- The Apache Maven Team.


[0]: ../../download.html
[1]: ../../plugins/index.html
[2]: https://maven.apache.org/
[4]: https://issues.apache.org/jira/secure/ReleaseNote.jspa?version=12344378&projectId=12316922
[5]: ../../docs/history.html
[MNG-5705]: https://issues.apache.org/jira/browse/MNG-5705
[MNG-5965]: https://issues.apache.org/jira/browse/MNG-5965
[MNG-5995]: https://issues.apache.org/jira/browse/MNG-5995
[MNG-6256]: https://issues.apache.org/jira/browse/MNG-6256
[MNG-6261]: https://issues.apache.org/jira/browse/MNG-6261
[MNG-6262]: https://issues.apache.org/jira/browse/MNG-6262
[MNG-6346]: https://issues.apache.org/jira/browse/MNG-6346
[MNG-6374]: https://issues.apache.org/jira/browse/MNG-6374
[MNG-6429]: https://issues.apache.org/jira/browse/MNG-6429
[MNG-6495]: https://issues.apache.org/jira/browse/MNG-6495
[MNG-6505]: https://issues.apache.org/jira/browse/MNG-6505
[MNG-6506]: https://issues.apache.org/jira/browse/MNG-6506
[MNG-6529]: https://issues.apache.org/jira/browse/MNG-6529
[MNG-6530]: https://issues.apache.org/jira/browse/MNG-6530
[MNG-6533]: https://issues.apache.org/jira/browse/MNG-6533
[MNG-6543]: https://issues.apache.org/jira/browse/MNG-6543
[MNG-6558]: https://issues.apache.org/jira/browse/MNG-6558
[MNG-6577]: https://issues.apache.org/jira/browse/MNG-6577
[MNG-6590]: https://issues.apache.org/jira/browse/MNG-6590
[MNG-6599]: https://issues.apache.org/jira/browse/MNG-6599
[MNG-6059]: https://issues.apache.org/jira/browse/MNG-6059
[MNG-6159]: https://issues.apache.org/jira/browse/MNG-6159
[MNG-6213]: https://issues.apache.org/jira/browse/MNG-6213
[MNG-6481]: https://issues.apache.org/jira/browse/MNG-6481
[MNG-6513]: https://issues.apache.org/jira/browse/MNG-6513
[MNG-6515]: https://issues.apache.org/jira/browse/MNG-6515
[MNG-6520]: https://issues.apache.org/jira/browse/MNG-6520
[MNG-6522]: https://issues.apache.org/jira/browse/MNG-6522
[MNG-6572]: https://issues.apache.org/jira/browse/MNG-6572
[MNG-6593]: https://issues.apache.org/jira/browse/MNG-6593
[MNG-6597]: https://issues.apache.org/jira/browse/MNG-6597
[MNG-6600]: https://issues.apache.org/jira/browse/MNG-6600
[MNG-6601]: https://issues.apache.org/jira/browse/MNG-6601
[MNG-6605]: https://issues.apache.org/jira/browse/MNG-6605
[MNG-6611]: https://issues.apache.org/jira/browse/MNG-6611
[MNG-6571]: https://issues.apache.org/jira/browse/MNG-6571
[MNG-6538]: https://issues.apache.org/jira/browse/MNG-6538
[MNG-6544]: https://issues.apache.org/jira/browse/MNG-6544
[MNG-6573]: https://issues.apache.org/jira/browse/MNG-6573
[MNG-6618]: https://issues.apache.org/jira/browse/MNG-6618
[MNG-6526]: https://issues.apache.org/jira/browse/MNG-6526
[MNG-6591]: https://issues.apache.org/jira/browse/MNG-6591

[WAGON-537]: https://issues.apache.org/jira/browse/WAGON-537
