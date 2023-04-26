---
layout: post
title: "Apache Maven Assembly Plugin Version 3.4.2 Released"
date: '2022-07-23T12:22:22+00:00'
permalink: apache-maven-assembly-plugin-version2
categories:
  - Maven-Plugin-Releases
---
The Apache Maven team is pleased to announce the release of the [Apache
Maven Assembly Plugin, version 3.4.2](https://maven.apache.org/plugins/maven-assembly-plugin/).

The Assembly Plugin for Maven is primarily intended to allow users to aggregate
the project output along with its dependencies, modules, site documentation,
and other files into a single distributable archive.

You can download the appropriate sources etc. from the [download page](https://maven.apache.org/plugins/maven-assembly-plugin/download.cgi).

You should specify the version in your project's plugin configuration:

```xml
<plugin>
  <groupId>org.apache.maven.plugins</groupId>
  <artifactId>maven-assembly-plugin</artifactId>
  <version>3.4.2</version>
</plugin>
```

<!-- more -->

[Release Notes - Maven Assembly Plugin - Version 3.4.2](https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317220&version=12352095)

* Bug:

    * [MASSEMBLY-969](https://issues.apache.org/jira/browse/MASSEMBLY-969) - Excludes filtering in 3.4.0 and 3.4.1 differs from 3.3.0

* Task:

    * [MASSEMBLY-949](https://issues.apache.org/jira/browse/MASSEMBLY-949) - Examples should refer to https instead of http

Enjoy,

-The Apache Maven team
