---
layout: post
title: "Apache Maven Help Plugin Version 3.2.0 Released"
date: '2019-04-23T17:26:21+00:00'
permalink: apache-maven-help-plugin-3-2-0
categories:
  - Maven-Help-Plugin
  - Maven-Plugin-Releases
---
The Apache Maven team is pleased to announce the release of the
[Apache Maven Help Plugin, version 3.2.0](https://maven.apache.org/plugins/maven-help-plugin/)

The Maven Help Plugin is used to get relative information about a project or
the system. It can be used to get a description of a particular plugin,
including the plugin's goals with their parameters and component requirements,
the effective POM and effective settings of the current build, and the profiles
applied to the current project being built.

Important Notes since Version 3.0.0

* Maven 3+ only
* JDK 7 minimum requirement


You should specify the version in your project's plugin configuration:

```xml
<plugin>
  <groupId>org.apache.maven.plugins</groupId>
  <artifactId>maven-help-plugin</artifactId>
  <version>3.2.0</version>
</plugin>
```

You can download the appropriate [sources etc. from the download page](https://maven.apache.org/plugins/maven-help-plugin/download.cgi).


<!-- more -->

[Release Notes - Maven Help Plugin - Version 3.2.0](https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317522&version=12345382)


New Feature:

- [MPH-160](https://issues.apache.org/jira/browse/MPH-160) - help:effective-pom -Dverbose: add source location as comments in effective pom.xml

Improvement:

- [MPH-161](https://issues.apache.org/jira/browse/MPH-161) - add color to goal or plugin description

Enjoy,

-The Apache Maven team

