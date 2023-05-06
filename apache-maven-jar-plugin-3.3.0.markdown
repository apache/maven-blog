---
layout: post
title: "Apache Maven Jar Plugin Version 3.3.0 Released"
date: '2022-09-16T07:13:13+00:00'
permalink: apache-maven-jar-plugin-3-3-0
categories:
  - Maven-Jar-Plugin
  - Maven-Plugin-Releases
---
The Apache Maven team is pleased to announce the release of the
[Apache Maven Jar Plugin, version 3.3.0](https://maven.apache.org/plugins/maven-jar-plugin/).

This plugin provides the capability to build jars.

```xml
<plugin>
  <groupId>org.apache.maven.plugins</groupId>
  <artifactId>maven-jar-plugin</artifactId>
  <version>3.3.0</version>
</plugin>
```

<!-- more -->

[Release Notes - Maven JAR Plugin - Version 3.3.0](https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317526&version=12351126)

* Bug:

    * [MJAR-275](https://issues.apache.org/jira/browse/MJAR-275) - outputTimestamp not applied to module-info; breaks reproducible builds

* Tasks:

    * [MJAR-278](https://issues.apache.org/jira/browse/MJAR-278) - Update plugin (requires Maven 3.2.5+)
    * [MJAR-280](https://issues.apache.org/jira/browse/MJAR-280) - Java 8 as minimum

* Dependency upgrades:

    * [MJAR-288](https://issues.apache.org/jira/browse/MJAR-288) - Upgrade Parent to 36
    * [MJAR-290](https://issues.apache.org/jira/browse/MJAR-290) - Update Plexus Utils to 3.4.2
    * [MJAR-291](https://issues.apache.org/jira/browse/MJAR-291) - Upgrade Parent to 37

Enjoy,

- The Apache Maven team
