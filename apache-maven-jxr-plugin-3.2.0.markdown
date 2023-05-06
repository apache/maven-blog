---
layout: post
title: "Apache Maven JXR Plugin Version 3.2.0 Released"
date: '2022-03-20T21:27:29+00:00'
permalink: apache-maven-jxr-plugin-3-2-0
categories:
  - Maven-JXR-Plugin
  - Maven-Plugin-Releases
---
The Apache Maven team is pleased to announce the release of the
[Apache Maven JXR, version 3.2.0](https://maven.apache.org/jxr/maven-jxr-plugin/).

This module generates browsable HTML pages from Java source code.

You should specify the version in your project's plugin configuration:

```xml
<plugin>
   <groupId>org.apache.maven.plugins</groupId>
   <artifactId>maven-jxr-plugin</artifactId>
   <version>3.2.0</version>
</plugin>
```

NOTE: Special thanks for the contributions retrieved during the hackathon at JCreate.

<!-- more -->

[Release Notes - Maven JXR - Version 3.2.0](https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317527&version=12330848)

* Bug:

    * [JXR-164](https://issues.apache.org/jira/browse/JXR-164) - Full path to local code sources in page title

* Task:

    * [JXR-162](https://issues.apache.org/jira/browse/JXR-162) - Lift Minimum Java to Java 8

* Dependency upgrades:

    * [JXR-157](https://issues.apache.org/jira/browse/JXR-157) - Upgrade Velocity templating engine
    * [JXR-163](https://issues.apache.org/jira/browse/JXR-163) - Require Maven 3.2.5+
    * [JXR-165](https://issues.apache.org/jira/browse/JXR-165) - Upgrade Maven Reporting to 3.1.0
    * [JXR-167](https://issues.apache.org/jira/browse/JXR-167) - Upgrade Parent to 35
    * [JXR-168](https://issues.apache.org/jira/browse/JXR-168) - Dependency upgrade and cleanup

Enjoy,

-The Apache Maven team 
