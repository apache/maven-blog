---
layout: post
title: "Apache Maven EJB Plugin Version 3.0.1 Released"
date: '2018-05-09T19:47:09+00:00'
permalink: apache-maven-ejb-plugin-3-0-1
categories:
  - Maven-EJB-Plugin
  - Maven-Plugin-Releases
---
The Apache Maven team is pleased to announce the release of the
[Apache Maven EJB Plugin Version 3.0.1](https://maven.apache.org/plugins/maven-ejb-plugin/).

This plugin generates J2EE Enterprise Javabean (EJB) file as well as the
associated client jar.

Important Note since 3.0.1:

* Maven 3.X only
* JDK 7 minimum requirement

```xml
<plugin>
  <groupId>org.apache.maven.plugins</groupId>
  <artifactId>maven-ejb-plugin</artifactId>
  <version>3.0.1</version>
</plugin>
```

<!-- more -->

[Release Notes - Apache Maven EJB Plugin - Version 3.0.1](https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317421&version=12334440)

Bug:

* [MEJB-115](https://issues.apache.org/jira/browse/MEJB-115) - Wrong default EJB version stated on Usage page

Tasks:

* [MEJB-116](https://issues.apache.org/jira/browse/MEJB-116) - Clarify "properties removed" on intro page of site
* [MEJB-117](https://issues.apache.org/jira/browse/MEJB-117) - Remove reference to old wiki page on intro page
* [MEJB-118](https://issues.apache.org/jira/browse/MEJB-118) - Remove "J2EE" from plugin description and site

Dependency upgrades:

* [MEJB-119](https://issues.apache.org/jira/browse/MEJB-119) - Upgrade parent to 31
* [MEJB-120](https://issues.apache.org/jira/browse/MEJB-120) - Upgrade mave-surefire/failsafe-plugin 2.21.0
* [MEJB-121](https://issues.apache.org/jira/browse/MEJB-121) - Add documentation information for GitHub


Enjoy,

-The Apache Maven team
