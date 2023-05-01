---
layout: post
title: "Apache Maven Install Plugin Version 3.0.1 Released"
date: '2022-07-23T19:12:12+00:00'
permalink: apache-maven-install-plugin-3-0-1
categories:
  - Maven-Install-Plugin
  - Maven-Plugin-Releases
---
The Apache Maven team is pleased to announce the release of the
[Apache Maven Install Plugin, version 3.0.1](https://maven.apache.org/plugins/maven-install-plugin/).

The Maven-Install-Plugin is used during the install phase to add artifact(s) to the
local repository. The Install-Plugin uses the information in the POM (groupId,
artifactId, version) to determine the proper location for the artifact within
the local repository.

NOTE:
* Plugin is Java7 level and compatible with Maven 3.2.5+

```xml
<plugin>
  <groupId>org.apache.maven.plugins</groupId>
  <artifactId>maven-install-plugin</artifactId>
  <version>3.0.1</version>
</plugin>
```
You can download the appropriate sources etc. from the [download page](https://maven.apache.org/plugins/maven-install-plugin/download.cgi).

[Release Notes - Maven Install Plugin Version 3.0.1](https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317524&version=12352096)

* Bug:

    * [MINSTALL-160](https://issues.apache.org/jira/browse/MINSTALL-160) - generatePom=true with 3.0.0-M1 does not generate minimal POM but copies existing one


Enjoy,

-The Apache Maven team
