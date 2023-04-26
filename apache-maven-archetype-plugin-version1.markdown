---
layout: post
title: "Apache Maven Archetype Plugin 3.2.0 Released"
date: '2020-07-22T22:35:55+00:00'
permalink: apache-maven-archetype-plugin-version1
categories:
  - Maven
  - Maven-Plugin-Releases
---
The Apache Maven team is pleased to announce the release of the
[Apache Maven Archetype Plugin, version 3.2.0](https://maven.apache.org/archetype/maven-archetype-plugin/).

In short, Archetype is a Maven project templating toolkit. An archetype is defined as an original pattern or model from which all other things of the same kind are made. The names fits as we are trying to provide a system that provides a consistent means of generating Maven projects. Archetype will help authors create Maven project templates for users, and provides users with the means to generate parameterized versions of those project templates.

https://maven.apache.org/archetype/maven-archetype-plugin/index.html

You should specify the version in your project's plugin configuration:

```xml
<plugin>
  <groupId>org.apache.maven.plugins</groupId>
  <artifactId>maven-archetype-plugin</artifactId>
  <version>3.2.0</version>
</plugin>
```

You can download the appropriate sources etc. from the [download page](https://maven.apache.org/plugins/maven-archetype-plugin/download.cgi).

<!-- more -->

[Release Notes - Maven Archetype Plugin - Version 3.2.0](https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317122&version=12346641)

* Bug:

    * [ARCHETYPE-585](https://issues.apache.org/jira/browse/ARCHETYPE-585) - Missing null check causes NullPointerException

* New Feature:

    * [ARCHETYPE-590](https://issues.apache.org/jira/browse/ARCHETYPE-590) - support Reproducible Builds for archetype:jar

* Improvements:

    * [ARCHETYPE-583](https://issues.apache.org/jira/browse/ARCHETYPE-583) - Skip parent non-archetype project when updating local catalog
    * [ARCHETYPE-586](https://issues.apache.org/jira/browse/ARCHETYPE-586) - make build Reproducible

* Dependency upgrades:

    * [ARCHETYPE-594](https://issues.apache.org/jira/browse/ARCHETYPE-594) - Update easymock
    * [ARCHETYPE-596](https://issues.apache.org/jira/browse/ARCHETYPE-596) - Update xmlunit

Enjoy,

-The Apache Maven team
