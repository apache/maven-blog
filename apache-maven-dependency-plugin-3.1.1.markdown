---
layout: post
title: "Apache Maven Dependency Plugin Version 3.1.1 Released"
date: '2018-05-24T13:43:56+00:00'
permalink: apache-maven-dependency-plugin-3-1-1
categories:
- Maven
- Maven-Plugin-Releases
---
The Apache Maven team is pleased to announce the release of the
[Apache Maven Dependency Plugin, version 3.1.1](https://maven.apache.org/plugins/maven-dependency-plugin/).

The dependency plugin provides the capability to manipulate artifacts. It
can copy and/or unpack artifacts from local or remote repositories to a
specified location.

https://maven.apache.org/plugins/maven-dependency-plugin/

You should specify the version in your project's plugin configuration:

```xml
<plugin>
    <groupId>org.apache.maven.plugins</groupId>
    <artifactId>maven-dependency-plugin</artifactId>
    <version>3.1.1</version>
</plugin>
``` 

You can download the appropriate sources etc. from the download page:

https://maven.apache.org/plugins/maven-dependency-plugin/download.cgi


<!-- more -->

[Release Notes - Maven Dependency Plugin - Version 3.1.1](https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317227&version=12343248)

Bug:

* [MDEP-607](https://issues.apache.org/jira/browse/MDEP-607) - maven-dependency-plugin:3.1.0:analyze failed.: NullPointerException

Dependency upgrades:

* [MDEP-611](https://issues.apache.org/jira/browse/MDEP-611) - Upgrade plexus-archiver to 3.6.0
* [MDEP-612](https://issues.apache.org/jira/browse/MDEP-612) - Upgrade maven-dependency-analyzer to 1.10
* [MDEP-614](https://issues.apache.org/jira/browse/MDEP-614) - Upgrade file-management to 3.0.0

Many thanks to all reporters/contributors/testers of this release.

Reporters:

* MDEP-607: Filipe Sousa


Enjoy,

-The Apache Maven team
