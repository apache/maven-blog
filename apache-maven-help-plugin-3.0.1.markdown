---
layout: post
title: "Apache Maven Help Plugin Version 3.0.1 Released"
date: '2018-03-28T17:29:11+00:00'
permalink: apache-maven-help-plugin-3-0-1
categories:
- Maven-Help-Plugin
- Maven-Plugin-Releases
---
The Apache Maven team is pleased to announce the release of the
[Apache Maven Help Plugin, version 3.0.1](https://maven.apache.org/plugins/maven-help-plugin/)

The Maven Help Plugin is used to get relative information about a project or
the system. It can be used to get a description of a particular plugin,
including the plugin's goals with their parameters and component requirements,
the effective POM and effective settings of the current build, and the profiles
applied to the current project being built.

You should specify the version in your project's plugin configuration:

```xml
<plugin>
  <groupId>org.apache.maven.plugins</groupId>
  <artifactId>maven-help-plugin</artifactId>
  <version>3.0.1</version>
</plugin>
```

You can download the appropriate [sources etc. from the download page](https://maven.apache.org/plugins/maven-help-plugin/download.cgi).


<!-- more -->

[Release Notes - Maven Help Plugin - Version 3.0.1](https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317522&version=12342960)

Bugs:

* [MPH-135](https://issues.apache.org/jira/browse/MPH-135) - help:effective-pom crashes with NPE in multi module builds with -Doutput set
* [MPH-139](https://issues.apache.org/jira/browse/MPH-139) - Invalid default namespace set for effective settings
* [MPH-140](https://issues.apache.org/jira/browse/MPH-140) - Multiple XML declarations written

Tasks:

* [MPH-137](https://issues.apache.org/jira/browse/MPH-137) - Use JDOM's PrettyFormatter throughout
* [MPH-138](https://issues.apache.org/jira/browse/MPH-138) - Drop AbstractEffectiveMojo#addMavenNamespace()
* [MPH-141](https://issues.apache.org/jira/browse/MPH-141) - Use non-deprecated field in DateFormatUtils

Dependency upgrade:

* [MPH-136](https://issues.apache.org/jira/browse/MPH-136) - Upgrade JDOM to 1.1.3

Enjoy,

-The Apache Maven team

