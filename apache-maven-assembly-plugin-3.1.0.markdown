---
layout: post
title: "Apache Maven Assembly Plugin Version 3.1.1 Released"
date: '2019-01-02T23:50:25+00:00'
permalink: apache-maven-assembly-plugin-3-1-1
categories:
  - Maven
  - Maven-Plugin-Releases
---
The Apache Maven team is pleased to announce the release of the [Apache
Maven Assembly Plugin, version 3.1.1](https://maven.apache.org/plugins/maven-assembly-plugin/).

The Assembly Plugin for Maven is primarily intended to allow users to aggregate
the project output along with its dependencies, modules, site documentation,
and other files into a single distributable archive.

Note:

* Maven 3.X only
* JDK 7 miminum requirement.

You can download the appropriate sources etc. from the [download page](https://maven.apache.org/plugins/maven-assembly-plugin/download.cgi).

You should specify the version in your project's plugin configuration:

```xml
<plugin>
  <groupId>org.apache.maven.plugins</groupId>
  <artifactId>maven-assembly-plugin</artifactId>
  <version>3.1.1</version>
</plugin>
```

<!-- more -->

[Release Notes - Maven Assembly Plugin - Version 3.1.1](https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317220&version=12341358)

Bugs:

* [MASSEMBLY-675](https://issues.apache.org/jira/browse/MASSEMBLY-675) - Maven Assembly packaging wildcard-excluded dependencies
* [MASSEMBLY-762](https://issues.apache.org/jira/browse/MASSEMBLY-762) - Assembly plugin doesn't exclude transitive dependencies when excluded by wildcards in dependencies section
* [MASSEMBLY-799](https://issues.apache.org/jira/browse/MASSEMBLY-799) - Exclusion on wildcard, then the assembly would still package to include the excluded libraries
* [MASSEMBLY-861](https://issues.apache.org/jira/browse/MASSEMBLY-861) - exclusion * also packaged
* [MASSEMBLY-873](https://issues.apache.org/jira/browse/MASSEMBLY-873) - Maven-Assembly-Plugin freezes when building jar-with-dependencies of project depending on org.bouncycastle:bcprov-jdk15on:1.58
* [MASSEMBLY-893](https://issues.apache.org/jira/browse/MASSEMBLY-893) - Typo in FAQ

Tasks:

* [MASSEMBLY-885](https://issues.apache.org/jira/browse/MASSEMBLY-885) - remove unused unpack code
* [MASSEMBLY-898](https://issues.apache.org/jira/browse/MASSEMBLY-898) - upgrade to plexus-io 3.1.1
* [MASSEMBLY-899](https://issues.apache.org/jira/browse/MASSEMBLY-899) - Make deprecated and non used of parameter useJvmChmod parameter (plugin is now 1.7)
* [MASSEMBLY-901](https://issues.apache.org/jira/browse/MASSEMBLY-901) - Fix trivial javadocs HTML errors
* [MASSEMBLY-902](https://issues.apache.org/jira/browse/MASSEMBLY-902) - Some Integration tests fails if launched with an very large UID

Dependency upgrades:

* [MASSEMBLY-876](https://issues.apache.org/jira/browse/MASSEMBLY-876) - Upgrade parent to 31
* [MASSEMBLY-882](https://issues.apache.org/jira/browse/MASSEMBLY-882) - Upgrade mave-surefire/failsafe-plugin 2.21.0
* [MASSEMBLY-884](https://issues.apache.org/jira/browse/MASSEMBLY-884) - Upgrade plexus-archiver to 3.6.0
* [MASSEMBLY-890](https://issues.apache.org/jira/browse/MASSEMBLY-890) - Upgrade plexus-interpolation to 1.25
* [MASSEMBLY-892](https://issues.apache.org/jira/browse/MASSEMBLY-892) - Upgrade maven-plugins parent to version 33
* [MASSEMBLY-900](https://issues.apache.org/jira/browse/MASSEMBLY-900) - Upgrade plexus-archiver to 4.0.0

Enjoy,

-The Apache Maven team
