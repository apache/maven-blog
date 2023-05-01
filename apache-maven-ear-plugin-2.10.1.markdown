---
layout: post
title: "Apache Maven EAR Plugin Version 2.10.1 Released"
date: '2015-07-02T07:46:00+00:00'
permalink: apache-maven-ear-plugin-2-10-1
categories:
  - Maven-Ear-Plugin
  - Maven-Plugin-Releases
---
The Apache Maven team is pleased to announce the release of the
[Apache Maven EAR Plugin, version 2.10.1](http://maven.apache.org/plugins/maven-ear-plugin/)

This plugin generates Java EE Enterprise Archive (EAR) file. It can also
generate the deployment descriptor file (e.g. application.xml).

You should specify the version in your project's plugin configuration:

```xml
<plugin>
  <groupId>org.apache.maven.plugins</groupId>
  <artifactId>maven-ear-plugin</artifactId>
  <version>2.10.1</version>
</plugin>
```
<!-- more -->

[Release Notes - Maven EAR Plugin - Version 2.10.1](https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317422&version=12330698)

Bug:

* [MEAR-214](https://issues.apache.org/jira/browse/MEAR-214) - RarModule not seen as standard artifact type

Improvements:

* [MEAR-159](https://issues.apache.org/jira/browse/MEAR-159) - encoding when filtering resources
* [MEAR-218](https://issues.apache.org/jira/browse/MEAR-218) - Upgrade plexus-archiver to 2.10.3
* [MEAR-219](https://issues.apache.org/jira/browse/MEAR-219) - Upgrade to fluido skin
* [MEAR-220](https://issues.apache.org/jira/browse/MEAR-220) - Upgrade plexus-utils to 3.0.22

Enjoy,

-The Apache Maven team
