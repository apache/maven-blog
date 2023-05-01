---
layout: post
title: "Apache Maven Compiler Plugin Version 3.10.1 Released"
date: '2022-03-11T12:21:30+00:00'
permalink: apache-maven-compiler-plugin-3-10-1
categories:
  - Maven-Compiler-Plugin
  - Maven-Plugin-Releases
---
The Apache Maven team is pleased to announce the release of the
[Apache Maven Compiler Plugin, version 3.10.1](https://maven.apache.org/plugins/maven-compiler-plugin/).

The Compiler Plugin is used to compile the sources of your project.

You should specify the version in your project's plugin configuration:

```xml
<plugin>
  <groupId>org.apache.maven.plugins</groupId>
  <artifactId>maven-compiler-plugin</artifactId>
  <version>3.10.1</version>
</plugin>
```

<!-- more -->

[Release Notes - Maven Compiler Plugin - Version 3.10.1](https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317225&version=12343484)

* Bugs:
    * [MCOMPILER-346](https://issues.apache.org/jira/browse/MCOMPILER-346) - workaround to jdk bug: assertionError inside javac when using javax.tools API
    * [MCOMPILER-485](https://issues.apache.org/jira/browse/MCOMPILER-485) - Incorrect internal string format in generated package-info.class files on Windows

* New Feature:
    * [MCOMPILER-426](https://issues.apache.org/jira/browse/MCOMPILER-426) - dedicated option for enabling preview feature

Enjoy,

- The Apache Maven team
