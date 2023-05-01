---
layout: post
title: "Apache Maven Artifact Plugin Version 3.3.0 Released"
date: '2022-04-07T09:30:30+00:00'
permalink: apache-maven-artifact-plugin-3-3-0
categories:
  - Maven-Artifact-Plugin
  - Maven-Plugin-Releases
---
The Apache Maven team is pleased to announce the release of the
[Apache Maven Artifact Plugin, version 3.3.0](https://maven.apache.org/plugins/maven-artifact-plugin/).

The Artifact Plugin is used to manage artifacts tasks.

You should specify the version in your project's plugin configuration:

```xml
<plugin>
  <groupId>org.apache.maven.plugins</groupId>
  <artifactId>maven-artifact-plugin</artifactId>
  <version>3.3.0</version>
</plugin>
```

<!-- more -->

[Release Notes - Maven Artifact Plugin - Version 3.3.0](https://issues.apache.org/jira/secure/ReleaseNote.jspa?version=12350902&styleName=Text&projectId=12324322)

Release Notes - Maven Artifact Plugin - Version 3.3.0

* Bug:

    * [MARTIFACT-31](https://issues.apache.org/jira/browse/MARTIFACT-31) - wrong comparison results when buildinfo has been published to Central

* New Feature:

    * [MARTIFACT-24](https://issues.apache.org/jira/browse/MARTIFACT-24) - add artifact:check-buildplan goal to check that plugins versions do not have known reproducibility issues


Enjoy,

-The Apache Maven team
