---
layout: post
title: "Apache Maven JDeps Plugin 3.1.1 Released"
date: '2018-03-01T17:09:08+00:00'
permalink: apache-maven-jdeps-plugin-3-1-1
categories:
  - Maven-JDeps-Plugin
  - Maven-Plugin-Releases
---
The Apache Maven team is pleased to announce the release of the
[Apache Maven JDeps Plugin, version 3.1.1](https://maven.apache.org/plugins/maven-jdeps-plugin/).

The JDeps Plugin uses the jdeps tool to analyze classes for internal API calls.
For more information about the standard jdeps tool, please refer to
https://wiki.openjdk.java.net/display/JDK8/Java+Dependency+Analysis+Tool

You should specify the version in your project's plugin configuration:

```xml
<plugin>
  <groupId>org.apache.maven.plugins</groupId>
  <artifactId>maven-jdeps-plugin</artifactId>
  <version>3.1.1</version>
</plugin>
```

[You can download the appropriate sources etc. from the download page.](https://maven.apache.org/plugins/maven-jdeps-plugin/download.cgi).

<!-- more -->

[Release Notes Maven JDeps Plugin Release Notes Version 3.1.1](https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12319223&version=12341552&styleName=Text)

Bugs:

* [MJDEPS-10](https://issues.apache.org/jira/browse/MJDEPS-10) - Error: unknown option: -M while using module option of maven-jdeps-plugin

New Features:

* [MJDEPS-9](https://issues.apache.org/jira/browse/MJDEPS-9) - Introduce failOnWarning as a named property
* [MJDEPS-11](https://issues.apache.org/jira/browse/MJDEPS-11) - Introduce --multi-release option

Improvement:

* [MJDEPS-12](https://issues.apache.org/jira/browse/MJDEPS-12) - Add support for the '-package' options

Dependency upgrade:

* [MJDEPS-8](https://issues.apache.org/jira/browse/MJDEPS-8) - Upgrade plexus-utils to version 3.1.0
* [MJDEPS-13](https://issues.apache.org/jira/browse/MJDEPS-13) - Upgrade parent to 31

Enjoy,

-The Apache Maven team 
