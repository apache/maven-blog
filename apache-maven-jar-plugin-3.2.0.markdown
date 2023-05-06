---
layout: post
title: "Apache Maven Jar Plugin Version 3.2.0 Released"
date: '2019-11-04T11:08:35+00:00'
permalink: apache-maven-jar-plugin-3-2-0
categories:
  - Maven-Jar-Plugin
  - Maven-Plugin-Releases
---
The Apache Maven team is pleased to announce the release of the
[Apache Maven Jar Plugin, version 3.2.0](https://maven.apache.org/plugins/maven-jar-plugin/).

This plugin provides the capability to build jars.

```xml
<plugin>
  <groupId>org.apache.maven.plugins</groupId>
  <artifactId>maven-jar-plugin</artifactId>
  <version>3.2.0</version>
</plugin>
```

<!-- more -->

[Release Notes - Maven JAR Plugin - Version 3.2.0](https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317526&version=12345503)


New Feature:

* [MJAR-263](https://issues.apache.org/jira/browse/MJAR-263) - Reproducible Builds: make entries in output jar files reproducible (order + timestamp)

Read https://maven.apache.org/guides/mini/guide-reproducible-builds.html for more information on Reproducible Builds with Maven.

Enjoy,

- The Apache Maven team
