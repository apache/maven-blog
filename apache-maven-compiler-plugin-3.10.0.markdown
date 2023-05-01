---
layout: post
title: "Apache Maven Compiler Plugin Version 3.10.0 Released"
date: '2022-02-14T12:57:57+00:00'
permalink: apache-maven-compiler-plugin-3-10-0
categories:
  - Maven-Compiler-Plugin
  - Maven-Plugin-Releases
---
The Apache Maven team is pleased to announce the release of the
[Apache Maven Compiler Plugin, version 3.10.0](https://maven.apache.org/plugins/maven-compiler-plugin/).

The Compiler Plugin is used to compile the sources of your project.

You should specify the version in your project's plugin configuration:

```xml
<plugin>
  <groupId>org.apache.maven.plugins</groupId>
  <artifactId>maven-compiler-plugin</artifactId>
  <version>3.10.0</version>
</plugin>
```

<!-- more -->

[Release Notes - Maven Compiler Plugin - Version 3.10.0](https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317225&version=12351256)


* Bugs:

    * [MCOMPILER-205](https://issues.apache.org/jira/browse/MCOMPILER-205) - incremental compilation broken for package-info classes
    * [MCOMPILER-225](https://issues.apache.org/jira/browse/MCOMPILER-225) - javac.bat and args file added to archive when fork and -X used
    * [MCOMPILER-460](https://issues.apache.org/jira/browse/MCOMPILER-460) - Compiler doesn't show detailed information with the Maven Toolchains
    * [MCOMPILER-470](https://issues.apache.org/jira/browse/MCOMPILER-470) - -parameters doesn't work with --release
    * [MCOMPILER-474](https://issues.apache.org/jira/browse/MCOMPILER-474) - Dependent modules are not recompiled if we run the "package" goal
    * [MCOMPILER-481](https://issues.apache.org/jira/browse/MCOMPILER-481) - JPMS Regression: cannot access <class> (requires static module not include anymore)

* Improvement:

    * [MCOMPILER-479](https://issues.apache.org/jira/browse/MCOMPILER-479) - Clarify `compilerArgs` Javadoc

* Task:

    * [MCOMPILER-484](https://issues.apache.org/jira/browse/MCOMPILER-484) - Remove deprecated mojos

Enjoy,

- The Apache Maven team
