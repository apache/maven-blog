---
layout: post
title: "Apache Maven Compiler Plugin Version 3.8.1 Released"
date: '2019-05-02T20:57:08+00:00'
permalink: apache-maven-compiler-plugin-version1
categories:
  - Maven
  - Maven-Plugin-Releases
---
The Apache Maven team is pleased to announce the release of the
[Apache Maven Compiler Plugin, version 3.8.1](https://maven.apache.org/plugins/maven-compiler-plugin/).

The Compiler Plugin is used to compile the sources of your project.

Important Notes since Version 3.8.1

* The default value for source/target has been lifted
  from 1.5 to 1.6 see [MCOMPILER-335](https://issues.apache.org/jira/browse/MCOMPILER-335).


You should specify the version in your project's plugin configuration:

```xml
<plugin>
  <groupId>org.apache.maven.plugins</groupId>
  <artifactId>maven-compiler-plugin</artifactId>
  <version>3.8.1</version>
</plugin>
```

<!-- more -->

[Release Notes - Maven Compiler Plugin - Version 3.8.1](https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317225&version=12343484)

Bugs:

* [MCOMPILER-306](https://issues.apache.org/jira/browse/MCOMPILER-306) - Incorrect `compilerArgs` example usage
* [MCOMPILER-349](https://issues.apache.org/jira/browse/MCOMPILER-349) - maven-compiler-plugin does not recompile a module if a dependency module has been updated & recompiled
* [MCOMPILER-360](https://issues.apache.org/jira/browse/MCOMPILER-360) - NPE when calculating modulepath with invalid entries
* [MCOMPILER-379](https://issues.apache.org/jira/browse/MCOMPILER-379) - Fatal error compiling: basedir ... arget/generated-sources/annotations does not exist

Improvements:

* [MCOMPILER-322](https://issues.apache.org/jira/browse/MCOMPILER-322) - Set the JPMS module version
* [MCOMPILER-366](https://issues.apache.org/jira/browse/MCOMPILER-366) - Warning about automodules should provide the list of offending libraries

Enjoy,

- The Apache Maven team
