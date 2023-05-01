---
layout: post
title: "Apache Maven EAR Plugin Version 3.0.2 Released"
date: '2019-11-16T17:03:10+00:00'
permalink: apache-maven-ear-plugin-3-0-2
categories:
  - Maven-Ear-plugin
  - Maven-Plugin-Releases
---
The Apache Maven team is pleased to announce the release of the
[Apache Maven EAR Plugin, version 3.0.2](https://maven.apache.org/plugins/maven-ear-plugin/)

This plugin generates Java EE Enterprise Archive (EAR) file. It can also
generate the deployment descriptor file (e.g. application.xml).

You should specify the version in your project's plugin configuration:

```xml
<plugin>
  <groupId>org.apache.maven.plugins</groupId>
  <artifactId>maven-ear-plugin</artifactId>
  <version>3.0.2</version>
</plugin>
```

You can download the appropriate [sources etc. from the download page](https://maven.apache.org/plugins/maven-ear-plugin/download.cgi).


<!-- more -->

[Release Notes - Maven EAR Plugin - Version 3.0.2](https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317422&version=12343262)

Bug:

* [MEAR-273](https://issues.apache.org/jira/browse/MEAR-273) - Adding extra slash causing issues on eclipse editors

Wish:

* [MEAR-271](https://issues.apache.org/jira/browse/MEAR-271) - Support lookup-name in resource-ref section

Dependency upgrades:

* [MEAR-270](https://issues.apache.org/jira/browse/MEAR-270) - Upgrade maven-plugins parent to version 32
* [MEAR-274](https://issues.apache.org/jira/browse/MEAR-274) - Upgrade plexus-interpolation to 1.25
* [MEAR-275](https://issues.apache.org/jira/browse/MEAR-275) - Upgrade plexus-archiver to 4.1.0
* [MEAR-277](https://issues.apache.org/jira/browse/MEAR-277) - Upgrade maven-invoker-plugin to 3.2.1

Enjoy,

-The Apache Maven team
