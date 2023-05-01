---
layout: post
title: "Apache Maven EJB Plugin Version 3.1.0 Released"
date: '2020-06-12T23:45:12+00:00'
permalink: apache-maven-ejb-plugin-3-1-0
categories:
  - Maven-EJB-Plugin
  - Maven-Plugin-Releases
---
The Apache Maven team is pleased to announce the release of the
[Apache Maven EJB Plugin Version 3.1.0](https://maven.apache.org/plugins/maven-ejb-plugin/).

This plugin generates J2EE Enterprise Javabean (EJB) file as well as the
associated client jar.

```xml
<plugin>
  <groupId>org.apache.maven.plugins</groupId>
  <artifactId>maven-ejb-plugin</artifactId>
  <version>3.1.0</version>
</plugin>
```

<!-- more -->

[Release Notes - Apache Maven EJB Plugin - Version 3.1.0](https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317421&version=12343161)

* New Feature:

    * [MEJB-128](https://issues.apache.org/jira/browse/MEJB-128) - Reproducible Builds: make entries in output jar files reproducible (order + timestamp)

* Improvements:

    * [MEJB-126](https://issues.apache.org/jira/browse/MEJB-126) - make build Reproducible
    * [MEJB-129](https://issues.apache.org/jira/browse/MEJB-129) - Refactor IncludesExcludes to reduce code duplication

* Dependency upgrades

    * [MEJB-122](https://issues.apache.org/jira/browse/MEJB-122) - Upgrade maven-plugins parent to version 32
    * [MEJB-123](https://issues.apache.org/jira/browse/MEJB-123) - Upgrade plexus-interpolation to 1.25
    * [MEJB-124](https://issues.apache.org/jira/browse/MEJB-124) - Upgrade plexus-archiver to 3.6.0
    * [MEJB-125](https://issues.apache.org/jira/browse/MEJB-125) - Upgrade JUnit to 4.12

Enjoy,

-The Apache Maven team
