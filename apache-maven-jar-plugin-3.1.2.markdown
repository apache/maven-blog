---
layout: post
title: "Apache Maven Jar Plugin Version 3.1.2 Released"
date: '2019-05-13T17:46:26+00:00'
permalink: apache-maven-jar-plugin-3-1-2
categories:
  - Maven-Jar-Plugin
  - Maven-Plugin-Releases
---
The Apache Maven team is pleased to announce the release of the
[Apache Maven Jar Plugin, version 3.1.2](https://maven.apache.org/plugins/maven-jar-plugin/).

This plugin provides the capability to build jars.

Important Note:

* Maven 3.X only
* JDK 7 minimum requirement


```xml
<plugin>
  <groupId>org.apache.maven.plugins</groupId>
  <artifactId>maven-jar-plugin</artifactId>
  <version>3.1.2</version>
</plugin>
```

<!-- more -->

[Release Notes - Maven JAR Plugin - Version 3.1.2](https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317526&version=12344629)


Bug:

* [MJAR-259] - Archiving to jar is very slow

Improvement:

* [MJAR-238] - Allow setting of module main class

Enjoy,

- The Apache Maven team


[MJAR-259]: https://issues.apache.org/jira/browse/MJAR-259
[MJAR-238]: https://issues.apache.org/jira/browse/MJAR-238
