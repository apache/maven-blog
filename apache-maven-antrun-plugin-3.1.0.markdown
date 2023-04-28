---
layout: post
title: "Apache Maven AntRun Plugin Version 3.1.0 Released"
date: '2022-04-22T00:11:11+00:00'
permalink: apache-maven-antrun-plugin-3-1-0
categories:
  - Maven
  - Maven-Plugin-Releases
---
The Apache Maven team is pleased to announce the release of the [Apache
Maven AntRun Plugin, version 3.1.0](https://maven.apache.org/plugins/maven-antrun-plugin/).

This plugin provides the ability to run Ant tasks from within Maven. You can even embed your Ant
scripts in the POM!

You should specify the version in your project's plugin configuration:

```xml
<plugin>
  <groupId>org.apache.maven.plugins</groupId>
  <artifactId>maven-antrun-plugin</artifactId>
  <version>3.1.0</version>
</plugin>
```

You can download the [appropriate sources etc. from the download page][download-page]

<!-- more -->


[Release Notes - Maven AntRunPlugin - Version 3.1.0](https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317921&version=12346981)

* Improvement:

    * [MANTRUN-228](https://issues.apache.org/jira/browse/MANTRUN-228) - Add schema for Ant Tasks

* Tasks:

    * [MANTRUN-224](https://issues.apache.org/jira/browse/MANTRUN-224) - Require Java 8
    * [MANTRUN-232](https://issues.apache.org/jira/browse/MANTRUN-232) - Upgrade Maven to 3.2.5

* Dependency upgrades:

    * [MANTRUN-225](https://issues.apache.org/jira/browse/MANTRUN-225) - Upgrade Ant to 1.10.7
    * [MANTRUN-226](https://issues.apache.org/jira/browse/MANTRUN-226) - Bump minimum required Maven for Plugin to 3.1.1
    * [MANTRUN-227](https://issues.apache.org/jira/browse/MANTRUN-227) - Upgrade Ant to 1.10.12
    * [MANTRUN-236](https://issues.apache.org/jira/browse/MANTRUN-236) - Upgrade Maven Plugin Plugin to 3.6.4

Enjoy,

-The Apache Maven team

[download-page]: https://maven.apache.org/shared/maven-archiver/download.cgi
