---
layout: post
title: "Apache Maven Compiler Plugin Version 3.8.0 Released"
date: '2018-07-29T20:50:16+00:00'
permalink: apache-maven-compiler-plugin-3-8-0
categories:
  - Maven-Compiler-Plugin
  - Maven-Plugin-Releases
---
The Apache Maven team is pleased to announce the release of the
[Apache Maven Compiler Plugin, version 3.8.0](https://maven.apache.org/plugins/maven-compiler-plugin/).

The Compiler Plugin is used to compile the sources of your project.

Important Notes since Version 3.8.0

* The default value for source/target has been lifted
  from 1.5 to 1.6 see [MCOMPILER-335](https://issues.apache.org/jira/browse/MCOMPILER-335).


You should specify the version in your project's plugin configuration:

```xml
<plugin>
  <groupId>org.apache.maven.plugins</groupId>
  <artifactId>maven-compiler-plugin</artifactId>
  <version>3.8.0</version>
</plugin>
```

<!-- more -->

[Release Notes - Maven Compiler Plugin - Version 3.8.0](https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317225&version=12341563)


Bugs:

* [MCOMPILER-311](https://issues.apache.org/jira/browse/MCOMPILER-311) - NPE when --patch-module is used
* [MCOMPILER-321](https://issues.apache.org/jira/browse/MCOMPILER-321) - Problematic Java 9 modules are silently ignored
* [MCOMPILER-332](https://issues.apache.org/jira/browse/MCOMPILER-332) - Java 10 not supported
* [MCOMPILER-338](https://issues.apache.org/jira/browse/MCOMPILER-338) - Build Issue based on MCOMPILER-192 IT
* [MCOMPILER-342](https://issues.apache.org/jira/browse/MCOMPILER-342) - Unsupported class file major version 55
* [MCOMPILER-343](https://issues.apache.org/jira/browse/MCOMPILER-343) - Tests fail to compile in modularized project due to wrong module descriptor path being passed to plexus-java

Improvements:

* [MCOMPILER-313](https://issues.apache.org/jira/browse/MCOMPILER-313) - Support mrjar dependency with module descriptor only in META-INF/versions/x
* [MCOMPILER-323](https://issues.apache.org/jira/browse/MCOMPILER-323) - Support multi-release jars
* [MCOMPILER-335](https://issues.apache.org/jira/browse/MCOMPILER-335) - Update default source/target from 1.5 to 1.6
* [MCOMPILER-341](https://issues.apache.org/jira/browse/MCOMPILER-341) - Compile module-info.java files located in test sources

Tasks:

* [MCOMPILER-336](https://issues.apache.org/jira/browse/MCOMPILER-336) - Dependency that should be on modulepath sometime put on classpath
* [MCOMPILER-344](https://issues.apache.org/jira/browse/MCOMPILER-344) - Deprecate <optimize> flag
* [MCOMPILER-350](https://issues.apache.org/jira/browse/MCOMPILER-350) - Add GitHub Documentation

Dependency upgrades:

* [MCOMPILER-324](https://issues.apache.org/jira/browse/MCOMPILER-324) - Upgrade parent to 31
* [MCOMPILER-351](https://issues.apache.org/jira/browse/MCOMPILER-351) - Upgrade maven-plugins parent to version 32
* [MCOMPILER-352](https://issues.apache.org/jira/browse/MCOMPILER-352) - Upgrade maven-shared-utils to 3.2.1
* [MCOMPILER-353](https://issues.apache.org/jira/browse/MCOMPILER-353) - Upgrade plexus-compiler to 2.8.4

Enjoy,

-The Apache Maven team
