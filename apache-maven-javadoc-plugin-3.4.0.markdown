---
layout: post
title: "Apache Maven JavaDoc Plugin Version 3.4.0 Released"
date: '2022-04-20T18:53:51+00:00'
permalink: apache-maven-javadoc-plugin-3-4-0
categories:
  - Maven-Javadoc-Plugin
  - Maven-Plugin-Releases
---
The Apache Maven team is pleased to announce the release of the
[Apache Maven JavaDoc Plugin, version 3.4.0](https://maven.apache.org/plugins/maven-javadoc-plugin).

The Javadoc Plugin uses the Javadoc tool to generate javadocs for the
specified project.


```xml
<plugin>
  <groupId>org.apache.maven.plugins</groupId>
  <artifactId>maven-javadoc-plugin</artifactId>
  <version>3.4.0</version>
</plugin>
```

You can download the appropriate sources etc. from the download page:

https://maven.apache.org/plugins/maven-javadoc-plugin/download.cgi

[Release Notes - Apache Maven JavaDoc Plugin - Version 3.4.0](https://issues.apache.org/jira/secure/ReleaseNote.jspa?version=12330874&styleName=Text&projectId=12317529)



* Bug:

    * [MJAVADOC-696](https://issues.apache.org/jira/browse/MJAVADOC-696) - Invalid anchors in Javadoc and plugin mojo

* Task:

    * [MJAVADOC-712](https://issues.apache.org/jira/browse/MJAVADOC-712) - Remove remains of org.codehaus.doxia.sink.Sink

* Dependency upgrades:

    * [MJAVADOC-711](https://issues.apache.org/jira/browse/MJAVADOC-711) - Upgrade plugins in ITs
    * [MJAVADOC-714](https://issues.apache.org/jira/browse/MJAVADOC-714) - Upgrade to Maven 3.2.5


Enjoy,

-The Apache Maven team 
