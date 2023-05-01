---
layout: post
title: "Apache Maven EAR Plugin Version 3.0.1 Released"
date: '2018-05-13T10:11:38+00:00'
permalink: apache-maven-ear-plugin-3-0-1
categories:
  - Maven-Ear-Plugin
  - Maven-Plugin-Releases
---
The Apache Maven team is pleased to announce the release of the
[Apache Maven EAR Plugin, version 3.0.1](https://maven.apache.org/plugins/maven-ear-plugin/)

This plugin generates Java EE Enterprise Archive (EAR) file. It can also
generate the deployment descriptor file (e.g. application.xml).

You should specify the version in your project's plugin configuration:

```xml
<plugin>
  <groupId>org.apache.maven.plugins</groupId>
  <artifactId>maven-ear-plugin</artifactId>
  <version>3.0.1</version>
</plugin>
```

You can download the appropriate [sources etc. from the download page](https://maven.apache.org/plugins/maven-ear-plugin/download.cgi).


<!-- more -->

[Release Notes - Maven EAR Plugin - Version 3.0.1](https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317422&version=12342882)


Improvements:

* [MEAR-265](https://issues.apache.org/jira/browse/MEAR-265) - Add documentation information for GitHub
* [MEAR-266](https://issues.apache.org/jira/browse/MEAR-266) - Upgrade mave-surefire/failsafe-plugin 2.21.0

Dependency upgrade:

* [MEAR-268](https://issues.apache.org/jira/browse/MEAR-268) - Upgrade plexus-archiver to 3.6.0

Enjoy,

-The Apache Maven team
