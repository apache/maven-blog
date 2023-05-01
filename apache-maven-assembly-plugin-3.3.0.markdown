---
layout: post
title: "Apache Maven Assembly Plugin Version 3.3.0 Released"
date: '2020-05-01T13:00:00+00:00'
permalink: apache-maven-assembly-plugin-3-3-0
categories:
  - Maven-Assembly-Plugin
  - Maven-Plugin-Releases
---
The Apache Maven team is pleased to announce the release of the [Apache
Maven Assembly Plugin, version 3.3.0](https://maven.apache.org/plugins/maven-assembly-plugin/).

The Assembly Plugin for Maven is primarily intended to allow users to aggregate
the project output along with its dependencies, modules, site documentation,
and other files into a single distributable archive.

You can download the appropriate sources etc. from the [download page](https://maven.apache.org/plugins/maven-assembly-plugin/download.cgi).

You should specify the version in your project's plugin configuration:

```xml
<plugin>
  <groupId>org.apache.maven.plugins</groupId>
  <artifactId>maven-assembly-plugin</artifactId>
  <version>3.3.0</version>
</plugin>
```

<!-- more -->

[Release Notes - Maven Assembly Plugin - Version 3.3.0](https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317220&version=12344774)

* Bugs:

    * [MASSEMBLY-879](https://issues.apache.org/jira/browse/MASSEMBLY-879) - useDefaultExcludes has no effect in dependencySet/unpack
    * [MASSEMBLY-920](https://issues.apache.org/jira/browse/MASSEMBLY-920) - ContainerDescriptorHandler for MetaInf-Services breaks folder structure
    * [MASSEMBLY-932](https://issues.apache.org/jira/browse/MASSEMBLY-932) - resource filtering skipped for resources in the current project

* New Features:

    * [MASSEMBLY-922](https://issues.apache.org/jira/browse/MASSEMBLY-922) - allow to override UID/GID and user name and group name for files stored in TAR (and other formats that store UID/GID)
    * [MASSEMBLY-927](https://issues.apache.org/jira/browse/MASSEMBLY-927) - Support for properties mapping on executions of maven-assembly-plugin
    * [MASSEMBLY-934](https://issues.apache.org/jira/browse/MASSEMBLY-934) - Support concatenation of files

* Improvements:

    * [MASSEMBLY-765](https://issues.apache.org/jira/browse/MASSEMBLY-765) - add property groupIdPath
    * [MASSEMBLY-849](https://issues.apache.org/jira/browse/MASSEMBLY-849) - Add nonFilteredFileExtensions to avoid filtering of binary files
    * [MASSEMBLY-933](https://issues.apache.org/jira/browse/MASSEMBLY-933) - make build Reproducible

* Dependency upgrade:

    * [MASSEMBLY-924](https://issues.apache.org/jira/browse/MASSEMBLY-924) - Upgrade commons-compress to 1.19

Enjoy,

-The Apache Maven team
