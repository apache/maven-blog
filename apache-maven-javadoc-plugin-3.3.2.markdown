---
layout: post
title: "Apache Maven JavaDoc Plugin Version 3.3.2 Released"
date: '2022-02-11T12:14:14+00:00'
permalink: apache-maven-javadoc-plugin-3-3-2
categories:
  - Maven-Javadoc-Plugin
  - Maven-Plugin-Releases
---
---
date: 2022-02-11T12:14:14
lastmod: 2022-02-11T12:14:14
---
The Apache Maven team is pleased to announce the release of the
[Apache Maven JavaDoc Plugin, version 3.3.2](https://maven.apache.org/plugins/maven-javadoc-plugin).

The Javadoc Plugin uses the Javadoc tool to generate javadocs for the
specified project.


```xml
<plugin>
  <groupId>org.apache.maven.plugins</groupId>
  <artifactId>maven-javadoc-plugin</artifactId>
  <version>3.3.2</version>
</plugin>
```

You can download the appropriate sources etc. from the download page:

https://maven.apache.org/plugins/maven-javadoc-plugin/download.cgi

<!-- more -->

[Release Notes - Apache Maven JavaDoc Plugin - Version 3.3.2](https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317529&version=12345698)



* Bugs:

    * [MJAVADOC-693](https://issues.apache.org/jira/browse/MJAVADOC-693) - NPE if URL is not defined in a dependency
    * [MJAVADOC-694](https://issues.apache.org/jira/browse/MJAVADOC-694) - Empty warning with maven-javadoc-plugin 3.3.1

* Dependency upgrade:

    * [MJAVADOC-705](https://issues.apache.org/jira/browse/MJAVADOC-705) - Upgrade Maven Reporting API to 3.1.0


Enjoy,

-The Apache Maven team 
