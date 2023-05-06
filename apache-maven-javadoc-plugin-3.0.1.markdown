---
layout: post
title: "Apache Maven JavaDoc Plugin Version 3.0.1 Released"
date: '2018-06-01T18:48:34+00:00'
permalink: apache-maven-javadoc-plugin-3-0-1
categories:
  - Maven-Javadoc-Plugin
  - Maven-Plugin-Releases
---
The Apache Maven team is pleased to announce the release of the
[Apache Maven JavaDoc Plugin, version 3.0.1](https://maven.apache.org/plugins/maven-javadoc-plugin).

The Javadoc Plugin uses the Javadoc tool to generate javadocs for the
specified project.


```xml
<plugin>
  <groupId>org.apache.maven.plugins</groupId>
  <artifactId>maven-javadoc-plugin</artifactId>
  <version>3.0.1</version>
</plugin>
```

You can download the appropriate sources etc. from the download page:

https://maven.apache.org/plugins/maven-javadoc-plugin/download.cgi

<!-- more -->

[Release Notes - Apache Maven JavaDoc Plugin - Version 3.0.1](https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317529&version=12342283)

Bugs:

* [MJAVADOC-427](https://issues.apache.org/jira/browse/MJAVADOC-427) - "Error fetching URL" for valid non-Java API links
* [MJAVADOC-504](https://issues.apache.org/jira/browse/MJAVADOC-504) - NullPointerException in JavadocUtil.getJavaHome() when JAVA_HOME isn't set
* [MJAVADOC-512](https://issues.apache.org/jira/browse/MJAVADOC-512) - Even when <javadocVersion>1.8.0</javadocVersion> matches there still is a warning.
* [MJAVADOC-517](https://issues.apache.org/jira/browse/MJAVADOC-517) - NPE under Java 10 RC

Improvements:

* [MJAVADOC-487](https://issues.apache.org/jira/browse/MJAVADOC-487) - Follow redirects
* [MJAVADOC-508](https://issues.apache.org/jira/browse/MJAVADOC-508) - Option to fail in case of javadoc warning

Dependency upgrades:

* [MJAVADOC-515](https://issues.apache.org/jira/browse/MJAVADOC-515) - Upgrade parent to 31
* [MJAVADOC-520](https://issues.apache.org/jira/browse/MJAVADOC-520) - Upgrade plexus-utils/qdox/plexus-archiver/
* [MJAVADOC-521](https://issues.apache.org/jira/browse/MJAVADOC-521) - Add documentation information for GitHub


Enjoy,

-The Apache Maven team 
