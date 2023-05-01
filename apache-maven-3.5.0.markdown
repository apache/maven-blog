---
layout: post
title: "Apache Maven 3.5.0 Released"
date: '2017-04-07T23:34:34+00:00'
permalink: apache-maven-3-5-0
categories:
  - Maven-Core-Releases
---
The Apache Maven team would like to announce the release of Apache Maven
3.5.0.

You can download the appropriate sources etc. from the [download page](https://maven.apache.org/download.cgi).


Notable changes
===============

- ANSI colors added to the console output
- Fix various bugs in mvn scripts regarding spaces, quotations, special
  characters, etc. also in combination with .mvn/ -files
- Switch from Eclipse Aether to Maven Artifact Resolver

What happened to Maven 3.4.0?
=============================

After Maven 3.3.9 was released, the Eclipse Aether project was retired and
the code base was migrated to the Apache Maven project.

The original goal for the 3.4.0 release was to replace Aether with the
exact same code after migration to the Apache Maven project and then
proceed with bug fixes to the resolver code as well as other areas of Maven.

The migration of the code between the two foundations took longer than
expected and as a result there were other changes committed to Maven core
that were outside the scope of intent for 3.4.0.

In order to refocus on the original intent for 3.4.0, the decision was
taken to revert the Maven core history to the point of the 3.3.9 release
and merge in the desired changes one at a time.

Because there had been a lot of communication about different features
being delivered and bugs fixed in Maven 3.4.0 and the new history may not
contain them in the first release, the decision was taken to forever burn
the 3.4.x release line.

More detail on this decision can be read in the mailing list archive[1].

<!-- more -->

Contributors
============

The Apache Maven team would like to thank the following contributors,
without whom this release would not have been possible:

Code contributors:

- Alex Henrie
- Andriy
- Archimedes Trajano
- Arlo Louis O'Keeffe
- August Shi
- Christoph Böhme
- Harald Wellmann
- Jason Dillon
- Joseph Walton
- Josh Soref
- Miriam Lee
- Nemo Chen
- Sébastian Le Merdy
- Stuart McCulloch
- Tobias Oberlies
- Robert Patrick

Issue reporters:

- Alex Henrie
- Andreas Sewe
- Andrew Haines
- Andriy
- Anthony Whitford
- Archimedes Trajano
- August Shi
- Ben Caradoc-Davies
- Christoph Böhme
- Daniel Spilker
- Falko Modler
- Fred Bricon
- Harald Wellmann
- Jeffrey Alexander
- Josh Soref
- Kengo TODA
- Konrad Windszus
- Laird Nelson
- Larry Singer
- Meytal Genah
- Mike Drob
- Miriam Lee
- Nemo Chen
- Peter Kjær Guldbæk
- Rahul Thakur
- Richard Raumberger
- Stuart McCulloch
- Tobias Oberlies
- Zac Thompson

Community testers participating in voting for this release series:

-  Grzegorz Grzybek
-  Petr Široký
-  Mark Derricutt,
-  Dejan Stojadinović
-  Thomas Collignon
-  Fred Cooke
-  Raphael Ackermann
-  Elliot Metsger
-  Chas Honton
-  Dennis Kieselhorst

The Apache Maven Project Management Committee would also like to thank all
the committers to the project for their efforts during the chaos that was
the great reset when the 3.4.x release lines were burned.

[Release Notes - Maven - Version 3.5.0][release-notes-3.5.0]
=====================================

Bugs:

* [MNG-5297](https://issues.apache.org/jira/browse/MNG-5297) - - Site should tell 'prerequisites.maven is deprecated'
* [MNG-5368](https://issues.apache.org/jira/browse/MNG-5368) - - UnsupportedOperationException thrown when version range is not correct in dependencyManagement definitions
* [MNG-5629](https://issues.apache.org/jira/browse/MNG-5629) - - ClosedChannelException from DefaultUpdateCheckManager.read
* [MNG-5815](https://issues.apache.org/jira/browse/MNG-5815) - - "mvn.cmd" does not indicate failure properly when using "&&"
* [MNG-5823](https://issues.apache.org/jira/browse/MNG-5823) - - mvnDebug doesn't work with M2_HOME with spaces - missing quotes
* [MNG-5829](https://issues.apache.org/jira/browse/MNG-5829) - - mvn shell script fails with syntax error on Solaris 10
* [MNG-5836](https://issues.apache.org/jira/browse/MNG-5836) - - logging config is overridden by $M2_HOME/lib/ext/*.jar
* [MNG-5852](https://issues.apache.org/jira/browse/MNG-5852) - - mvn shell script invokes /bin/sh but requires Bash functions
* [MNG-5895](https://issues.apache.org/jira/browse/MNG-5895) - - Problem with CI friendly usage of ${..} which is already defined via property in pom file.
* [MNG-5958](https://issues.apache.org/jira/browse/MNG-5958) - - java.lang.String cannot be cast to org.apache.maven.lifecycle.mapping.LifecyclePhase
* [MNG-5961](https://issues.apache.org/jira/browse/MNG-5961) - - Maven possibly not aware of log4j2
* [MNG-5962](https://issues.apache.org/jira/browse/MNG-5962) - - mvn.cmd fails when the current directory has spaces in between
* [MNG-5963](https://issues.apache.org/jira/browse/MNG-5963) - - mvn.cmd does not return ERROR_CODE
* [MNG-6022](https://issues.apache.org/jira/browse/MNG-6022) - - mvn.cmd fails if directory contains an ampersand (&)
* [MNG-6053](https://issues.apache.org/jira/browse/MNG-6053) - - Unsafe System Properties copy in MavenRepositorySystemUtils, causing NPEs
* [MNG-6057](https://issues.apache.org/jira/browse/MNG-6057) - - Problem with CI friendly usage of ${..} reactor order is changed
* [MNG-6090](https://issues.apache.org/jira/browse/MNG-6090) - - CI friendly properties break submodule builds
* [MNG-6105](https://issues.apache.org/jira/browse/MNG-6105) - - properties.internal.SystemProperties.addSystemProperties() is not really thread-safe
* [MNG-6109](https://issues.apache.org/jira/browse/MNG-6109) - - PluginDescriptor doesn't read since value of parameter
* [MNG-6117](https://issues.apache.org/jira/browse/MNG-6117) - - ${session.parallel} not correctly set
* [MNG-6144](https://issues.apache.org/jira/browse/MNG-6144) - - DefaultWagonManagerTest#testGetMissingJarForced() passed incorrect value
* [MNG-6166](https://issues.apache.org/jira/browse/MNG-6166) - - mvn dependency:go-offline fails due to missing transitive dependency jdom:jdom:jar:1.1
* [MNG-6168](https://issues.apache.org/jira/browse/MNG-6168) - - Fix unclosed streams
* [MNG-6170](https://issues.apache.org/jira/browse/MNG-6170) - - NPE in cases using Multithreaded -T X versions:set -DnewVersion=1.0-SNAPSHOT
* [MNG-6171](https://issues.apache.org/jira/browse/MNG-6171) - - REGRESSION: WARNING about usage of a non threadsafe marked plugin is not showed anymore
* [MNG-6172](https://issues.apache.org/jira/browse/MNG-6172) - - Precedence of command-line system property options has changed
* [MNG-6173](https://issues.apache.org/jira/browse/MNG-6173) - - MavenSession.getAllProjects() should return all projects in the reactor
* [MNG-6176](https://issues.apache.org/jira/browse/MNG-6176) - - Javadoc errors prevent release with Java 8
* [MNG-6177](https://issues.apache.org/jira/browse/MNG-6177) - - The --file command line option of the Windows and Unix launchers does not work for directory names like "Spaces & Special Char"
* [MNG-6180](https://issues.apache.org/jira/browse/MNG-6180) - - groupId has plain color when goal fails
* [MNG-6181](https://issues.apache.org/jira/browse/MNG-6181) - - HttpClient produces a lot of noise at debug loglevel
* [MNG-6183](https://issues.apache.org/jira/browse/MNG-6183) - - Dependency management debug message corrections.
* [MNG-6190](https://issues.apache.org/jira/browse/MNG-6190) - - maven-resolver-provider's DefaultArtifactDescriptorReader has mismatched constructor and initService methods
* [MNG-6191](https://issues.apache.org/jira/browse/MNG-6191) - - mvn -f complains about illegal readlink option under macOS
* [MNG-6192](https://issues.apache.org/jira/browse/MNG-6192) - - distribution zip file has unordered entries
* [MNG-6195](https://issues.apache.org/jira/browse/MNG-6195) - - Use consistent quoting forms in mvn launcher script
* [MNG-6198](https://issues.apache.org/jira/browse/MNG-6198) - - mvn script fails to locate .mvn directory when pom location specified with -f

Dependency upgrades:

* [MNG-5967](https://issues.apache.org/jira/browse/MNG-5967) - - Dependency updates
* [MNG-6110](https://issues.apache.org/jira/browse/MNG-6110) - - Upgrade Aether to Maven Resolver

Improvements:

* [MNG-5579](https://issues.apache.org/jira/browse/MNG-5579) - - Unify error output/check logic from shell and batch scripts
* [MNG-5607](https://issues.apache.org/jira/browse/MNG-5607) - - Don't use M2_HOME in mvn shell/command scripts anymore
* [MNG-5883](https://issues.apache.org/jira/browse/MNG-5883) - - Silence unnecessary legacy local repository warning
* [MNG-5889](https://issues.apache.org/jira/browse/MNG-5889) - - .mvn directory should be picked when using --file
* [MNG-5904](https://issues.apache.org/jira/browse/MNG-5904) - - Remove the whole Ant build
* [MNG-5931](https://issues.apache.org/jira/browse/MNG-5931) - - Fixing documentation
* [MNG-5934](https://issues.apache.org/jira/browse/MNG-5934) - - String handling issues identified by PMD
* [MNG-5946](https://issues.apache.org/jira/browse/MNG-5946) - - Fix links etc. in README.txt which is part of the delivery
* [MNG-5968](https://issues.apache.org/jira/browse/MNG-5968) - - Default plugin version updates
* [MNG-5975](https://issues.apache.org/jira/browse/MNG-5975) - - Use Java 7's SimpleDateFormat in CLIReportingUtils# formatTimestamp
* [MNG-5977](https://issues.apache.org/jira/browse/MNG-5977) - - Improve output readability of our MavenTransferListener implementations
* [MNG-5993](https://issues.apache.org/jira/browse/MNG-5993) - - Confusing error message in case of missing/empty artifactId and version in pluginManagement
* [MNG-6001](https://issues.apache.org/jira/browse/MNG-6001) - - Replace %HOME% with %USERPROFILE% in mvn.cmd
* [MNG-6003](https://issues.apache.org/jira/browse/MNG-6003) - - Drastically reduce JAVA_HOME discovery code
* [MNG-6014](https://issues.apache.org/jira/browse/MNG-6014) - - Removing ArtifactHandler for ejb3
* [MNG-6017](https://issues.apache.org/jira/browse/MNG-6017) - - Removing ArtifactHandler for par LifeCycle
* [MNG-6030](https://issues.apache.org/jira/browse/MNG-6030) - - ReactorModelCache do not used effectively after maven version 3.0.5 which cause a large memory footprint
* [MNG-6032](https://issues.apache.org/jira/browse/MNG-6032) - - WARNING during build based on absolute path in assembly-descriptor.
* [MNG-6068](https://issues.apache.org/jira/browse/MNG-6068) - - Document default scope compile in pom XSD and reference documentation
* [MNG-6078](https://issues.apache.org/jira/browse/MNG-6078) - - Can't overwrite properties which have been defined in .mvn/maven.config
* [MNG-6081](https://issues.apache.org/jira/browse/MNG-6081) - - Log refactoring - Method Invocation Replaced By Variable
* [MNG-6102](https://issues.apache.org/jira/browse/MNG-6102) - - Introduce ${maven.conf} in m2.conf
* [MNG-6115](https://issues.apache.org/jira/browse/MNG-6115) - - Add Jansi native library search path to our start scripts to avoid extraction to temp file on each run
* [MNG-6145](https://issues.apache.org/jira/browse/MNG-6145) - -  Remove non-existent m2 include in component.xml
* [MNG-6146](https://issues.apache.org/jira/browse/MNG-6146) - - Several small stylistic and spelling improvements to code and documentation
* [MNG-6147](https://issues.apache.org/jira/browse/MNG-6147) - - MetadataResolutionResult#getGraph() contains duplicate if clause
* [MNG-6150](https://issues.apache.org/jira/browse/MNG-6150) - - Javadoc improvements for 3.5.0
* [MNG-6163](https://issues.apache.org/jira/browse/MNG-6163) - - Introduce CLASSWORLDS_JAR in shell startup scripts
* [MNG-6165](https://issues.apache.org/jira/browse/MNG-6165) - - Deprecate and replace incorrectly spelled public API
* [MNG-6179](https://issues.apache.org/jira/browse/MNG-6179) - - Remove unused prerequisites
* [MNG-6185](https://issues.apache.org/jira/browse/MNG-6185) - - Replace doclettag explanation with annotations in AbstractMojo javadoc
* [MNG-6189](https://issues.apache.org/jira/browse/MNG-6189) - - WARN if maven-site-plugin configuration contains reportPlugins element

New Features:

* [MNG-3507](https://issues.apache.org/jira/browse/MNG-3507) - - ANSI color logging for improved output visibility
* [MNG-5878](https://issues.apache.org/jira/browse/MNG-5878) - - add support for module name != artifactId in every calculated URLs (project, SCM, site): special project.directory property
* [MNG-6093](https://issues.apache.org/jira/browse/MNG-6093) - - create a slf4j-simple provider extension that supports level color rendering
* [MNG-6182](https://issues.apache.org/jira/browse/MNG-6182) - - ModelResolver interface enhancement: addition of resolveModel( Dependency ) supporting version ranges

Tasks:

* [MNG-5954](https://issues.apache.org/jira/browse/MNG-5954) - - Remove outdated maven-embedder/src/main/ resources/META-INF/MANIFEST.MF
* [MNG-6106](https://issues.apache.org/jira/browse/MNG-6106) - - Remove maven.home default value setter from m2.conf
* [MNG-6136](https://issues.apache.org/jira/browse/MNG-6136) - - Upgrade Maven Wagon from 2.10 to 2.12
* [MNG-6137](https://issues.apache.org/jira/browse/MNG-6137) - - Clean up duplicate dependencies caused by incomplete Wagon HTTP Provider exclusions
* [MNG-6138](https://issues.apache.org/jira/browse/MNG-6138) - - Remove obsolete message_*.properties form maven-core
* [MNG-6140](https://issues.apache.org/jira/browse/MNG-6140) - - update documentation's dependency graph with resolver + resolver-provider + slf4j-provider
* [MNG-6151](https://issues.apache.org/jira/browse/MNG-6151) - - Force Push master from 737de43e392fc15a0ce366db98d70aa18b3f6c03
* [MNG-6152](https://issues.apache.org/jira/browse/MNG-6152) - - Add a Jenkinsfile so that builds.apache.org can use multibranch pipeline

Wishes:

* [MNG-2199](https://issues.apache.org/jira/browse/MNG-2199) - - Support version ranges in parent elements
* [MNG-6088](https://issues.apache.org/jira/browse/MNG-6088) - - after forked execution success, add an empty line
* [MNG-6092](https://issues.apache.org/jira/browse/MNG-6092) - - warn if prerequisites.maven is used for non-plugin projects

Enjoy,

- The Apache Maven team

[1]: https://www.mail-archive.com/dev@maven.apache.org/msg112103.html
[release-notes-3.5.0]: https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12316922&version=12336084
