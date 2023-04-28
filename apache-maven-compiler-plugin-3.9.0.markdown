---
layout: post
title: "Apache Maven Compiler Plugin Version 3.9.0 Released"
date: '2022-01-12T14:39:39+00:00'
permalink: apache-maven-compiler-plugin-3-9-0
categories:
  - Maven
  - Maven-Plugin-Releases
---
The Apache Maven team is pleased to announce the release of the
[Apache Maven Compiler Plugin, version 3.9.0](https://maven.apache.org/plugins/maven-compiler-plugin/).

The Compiler Plugin is used to compile the sources of your project.

You should specify the version in your project's plugin configuration:

```xml
<plugin>
  <groupId>org.apache.maven.plugins</groupId>
  <artifactId>maven-compiler-plugin</artifactId>
  <version>3.9.0</version>
</plugin>
```

<!-- more -->

[Release Notes - Maven Compiler Plugin - Version 3.9.0](https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317225&version=12345214)


* Bugs:

    * [MCOMPILER-272](https://issues.apache.org/jira/browse/MCOMPILER-272) - When annotationProcessorPaths has multiple entries, only the transitive dependencies of the first entry are added
    * [MCOMPILER-359](https://issues.apache.org/jira/browse/MCOMPILER-359) - plexus-java 0.9.10 causes a NullPointer in compiler-plugin 3.8.0
    * [MCOMPILER-373](https://issues.apache.org/jira/browse/MCOMPILER-373) - Unable to compile MR jar code against older directories
    * [MCOMPILER-410](https://issues.apache.org/jira/browse/MCOMPILER-410) - CI Broken by JDK 15 changes
    * [MCOMPILER-455](https://issues.apache.org/jira/browse/MCOMPILER-455) - preparePaths does not take toolchain into account when parsing module-info.class

* Improvements:

    * [MCOMPILER-376](https://issues.apache.org/jira/browse/MCOMPILER-376) - Change default source/target to 1.7 (new minimum for JDK 12)
    * [MCOMPILER-382](https://issues.apache.org/jira/browse/MCOMPILER-382) - Remove superfluous exception declarations
    * [MCOMPILER-383](https://issues.apache.org/jira/browse/MCOMPILER-383) - Use Java 7 type inference more
    * [MCOMPILER-384](https://issues.apache.org/jira/browse/MCOMPILER-384) - Remove null checks in conjunction with instanceof
    * [MCOMPILER-385](https://issues.apache.org/jira/browse/MCOMPILER-385) - Minor performance improvements in CompilerMojo
    * [MCOMPILER-404](https://issues.apache.org/jira/browse/MCOMPILER-404) - Update default source/target from 1.6 to 1.7
    * [MCOMPILER-405](https://issues.apache.org/jira/browse/MCOMPILER-405) - Update plexus-java to 1.1.0
    * [MCOMPILER-411](https://issues.apache.org/jira/browse/MCOMPILER-411) - make build Reproducible
    * [MCOMPILER-427](https://issues.apache.org/jira/browse/MCOMPILER-427) - Lack of guide for cross-compilation for JDK 9+
    * [MCOMPILER-428](https://issues.apache.org/jira/browse/MCOMPILER-428) - Documentation regarding useIncrementalCompilation not very useful
    * [MCOMPILER-449](https://issues.apache.org/jira/browse/MCOMPILER-449) - Improve <jdkToolchain> parameter description
    * [MCOMPILER-471](https://issues.apache.org/jira/browse/MCOMPILER-471) - Require Java 8
    * [MCOMPILER-475](https://issues.apache.org/jira/browse/MCOMPILER-475) - Shared GitHub Actions

* Tasks:

    * [MCOMPILER-189](https://issues.apache.org/jira/browse/MCOMPILER-189) - Source Xref report is missing classes due to simple name collision, update maven-jxr-plugin
    * [MCOMPILER-398](https://issues.apache.org/jira/browse/MCOMPILER-398) - Simplify the implementation of the inclusion/exclusion logic
    * [MCOMPILER-467](https://issues.apache.org/jira/browse/MCOMPILER-467) - Improve compile mojo parameter multiReleaseOutput docs

* Dependency upgrade:

    * [MCOMPILER-399](https://issues.apache.org/jira/browse/MCOMPILER-399) - Upgrade mockito to latest 2.x


Enjoy,

- The Apache Maven team
