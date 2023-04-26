---
layout: post
title: "Apache Maven Checkstyle Plugin Version 3.2.1 Released"
date: '2019-05-30T12:31:02+00:00'
permalink: apache-maven-checkstyle-plugin-3.2.1
categories:
  - Maven
  - Maven-Plugin-Releases
---
The Apache Maven team is pleased to announce the release of the
[Apache Maven Checkstyle Plugin, version 3.2.1](https://maven.apache.org/plugins/maven-checkstyle-plugin/).

The Checkstyle Plugin generates a report regarding the code style used by the
developers. For more information about Checkstyle, see
https://checkstyle.sourceforge.net/.

You should specify the version in your project's plugin configuration:

```xml
<plugin>
  <groupId>org.apache.maven.plugins</groupId>
  <artifactId>maven-checkstyle-plugin</artifactId>
  <version>3.2.1</version>
</plugin>
``` 

You can download the appropriate [sources etc. from the download page](https://maven.apache.org/plugins/maven-checkstyle-plugin/download.cgi).

[Release Notes - Apache Maven Checkstyle Plugin - Version 3.2.1](https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317223&version=12352729)

* Task:

    * [MCHECKSTYLE-423] - Explicitly start and end tables with Doxia Sinks in report renderers

Enjoy,

- The Apache Maven team 
