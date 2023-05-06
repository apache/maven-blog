---
layout: post
title: "Apache Maven Jar Plugin Version 3.1.1 Released"
date: '2018-12-12T19:22:00+00:00'
permalink: apache-maven-jar-plugin-3-1-1
categories:
  - Maven-Jar-Plugin
  - Maven-Plugin-Releases
---
The Apache Maven team is pleased to announce the release of the
[Apache Maven Jar Plugin, version 3.1.1](https://maven.apache.org/plugins/maven-jar-plugin/).

This plugin provides the capability to build jars.

Important Note:

* Maven 3.X only
* JDK 7 minimum requirement


```xml
<plugin>
  <groupId>org.apache.maven.plugins</groupId>
  <artifactId>maven-jar-plugin</artifactId>
  <version>3.1.1</version>
</plugin>
```

<!-- more -->

[Release Notes - Maven JAR Plugin - Version 3.1.1](https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317526&version=12343046)


Bug:

* [MJAR-241](https://issues.apache.org/jira/browse/MJAR-241) - Jar package does not have a size in ZipEntry

Improvement:

* [MJAR-260](https://issues.apache.org/jira/browse/MJAR-260) - Upgrade to Archiver 3.3.0 and add ITs

Task:

* [MJAR-251](https://issues.apache.org/jira/browse/MJAR-251) - Add documentation information for GitHub

Dependency upgrades:

* [MJAR-252](https://issues.apache.org/jira/browse/MJAR-252) - Upgrade plexus-archiver to 3.6.0
* [MJAR-255](https://issues.apache.org/jira/browse/MJAR-255) - Upgrade maven-plugins parent to version 32
* [MJAR-256](https://issues.apache.org/jira/browse/MJAR-256) - Upgrade JUnit to 4.12
* [MJAR-261](https://issues.apache.org/jira/browse/MJAR-261) - Upgrade plexus-archiver 3.7.0

Enjoy,

- The Apache Maven team
