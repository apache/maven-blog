---
layout: post
title: "Apache Maven JXR Plugin Version 3.3.0 Released"
date: '2022-08-19T12:18:18+00:00'
permalink: apache-maven-jxr-plugin-3-3-0
categories:
  - Maven-JXR-Plugin
  - Maven-Plugin-Releases
---
The Apache Maven team is pleased to announce the release of the
[Apache Maven JXR, version 3.3.0](https://maven.apache.org/jxr/maven-jxr-plugin/).

This module generates browsable HTML pages from Java source code.

You should specify the version in your project's plugin configuration:

```xml
<plugin>
   <groupId>org.apache.maven.plugins</groupId>
   <artifactId>maven-jxr-plugin</artifactId>
   <version>3.3.0</version>
</plugin>
```


[Release Notes - Maven JXR - Version 3.3.0](https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317527&version=12351480)

* Bugs:

    * [JXR-166](https://issues.apache.org/jira/browse/JXR-166) - Two versions of velocity engines on plugin classpath
    * [JXR-170](https://issues.apache.org/jira/browse/JXR-170) - NullPointerException while parsing Java 15 multi-line String source

* Task:

    * [JXR-174](https://issues.apache.org/jira/browse/JXR-174) - Revert JXR-157 until next major version

* Dependency upgrades:

    * [JXR-171](https://issues.apache.org/jira/browse/JXR-171) - Bump plexus-utils from 3.4.1 to 3.4.2
    * [JXR-172](https://issues.apache.org/jira/browse/JXR-172) - Upgrade Parent to 37, project cleanup
    * [JXR-173](https://issues.apache.org/jira/browse/JXR-173) - Upgrade Maven Reporting API to 3.1.1/Maven Reporting Impl to 3.2.0


Enjoy,

-The Apache Maven team 
