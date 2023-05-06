---
layout: post
title: "Apache Maven JXR Plugin Version 3.0.0 Released"
date: '2018-09-25T00:00:00+00:00'
permalink: apache-maven-jxr-plugin-3-0-0
categories:
  - Maven-JXR-Plugin
  - Maven-Plugin-Releases
---
The Apache Maven team is pleased to announce the release of the
[Apache Maven JXR, version 3.0.0](https://maven.apache.org/jxr/maven-jxr-plugin/).

This module generates browsable HTML pages from Java source code.

You should specify the version in your project's plugin configuration:

```xml
<plugin>
   <groupId>org.apache.maven.plugins</groupId>
   <artifactId>maven-jxr-plugin</artifactId>
   <version>3.0.0</version>
</plugin>
```

NOTE: Special thanks for the contributions retrieved during the hackathon at JCreate.

<!-- more -->

[Release Notes - Maven JXR - Version 3.0.0](https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317527&version=12330848)


Bugs:

* [JXR-68](https://issues.apache.org/jira/browse/JXR-68) - ignores classes with same name in other packages
* [JXR-98](https://issues.apache.org/jira/browse/JXR-98) - Nested classes aren't linked correctly
* [JXR-100](https://issues.apache.org/jira/browse/JXR-100) - Method declaration: using spaces before or after parenthesis prevents cross references generation
* [JXR-126](https://issues.apache.org/jira/browse/JXR-126) - File write using platform default encoding
* [JXR-135](https://issues.apache.org/jira/browse/JXR-135) - Invalid representation of inner class
* [JXR-140](https://issues.apache.org/jira/browse/JXR-140) - Proper URL handling

Improvements:

* [JXR-110](https://issues.apache.org/jira/browse/JXR-110) - Use equivalent css/images of javadoc
* [JXR-124](https://issues.apache.org/jira/browse/JXR-124) - Remove excluded DEPENDENCIES file if new parent is used.
* [JXR-125](https://issues.apache.org/jira/browse/JXR-125) - Upgrade to Maven 3.0 compatiblity
* [JXR-127](https://issues.apache.org/jira/browse/JXR-127) - Create anchor for classes generated from a Java source file
* [JXR-131](https://issues.apache.org/jira/browse/JXR-131) - Reports 'jxr' and 'test-jxr' do not contain generated sources.
* [JXR-132](https://issues.apache.org/jira/browse/JXR-132) - Aggregator reports should not require modules to be installed/deployed.

Task:

* [JXR-134](https://issues.apache.org/jira/browse/JXR-134) - switch to Git

Dependency upgrades:

* [JXR-128](https://issues.apache.org/jira/browse/JXR-128) - Upgrade maven parent to version 30
* [JXR-129](https://issues.apache.org/jira/browse/JXR-129) - Upgrade of plexus-utils to 3.0.24.
* [JXR-130](https://issues.apache.org/jira/browse/JXR-130) - Upgrade of commons-io to 2.5.
* [JXR-136](https://issues.apache.org/jira/browse/JXR-136) - Upgrade plexus-utils 3.1.0
* [JXR-138](https://issues.apache.org/jira/browse/JXR-138) - Upgrade parent to 31

Enjoy,

-The Apache Maven team 
