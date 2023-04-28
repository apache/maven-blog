---
layout: post
title: "Apache Maven Clean Plugin Version 3.2.0 Released"
date: '2022-04-05T17:26:31+00:00'
permalink: apache-maven-clean-plugin-version1
categories:
  - Maven
  - Maven-Plugin-Releases
---
The Apache Maven team is pleased to announce the release of the
[Apache Maven Clean Plugin, version 3.2.0](https://maven.apache.org/plugins/maven-clean-plugin/).

The Clean Plugin is used when you want to remove files generated at build-time
in a project's directory.

Important Note:

* Maven 3.2.5+ only
* JDK 8 minimum requirement

You should specify the version in your project's plugin configuration:

```xml
<plugin>
  <groupId>org.apache.maven.plugins</groupId>
  <artifactId>maven-clean-plugin</artifactId>
  <version>3.2.0</version>
</plugin>
```

<!-- more -->

[Release Notes - Maven Clean Plugin - Version 3.2.0](https://issues.apache.org/jira/secure/ReleaseNote.jspa?version=12343770&styleName=Text&projectId=12317224)

Release Notes - Maven Clean Plugin - Version 3.2.0

* New Feature

    * [MCLEAN-95] - Provide a fast deletion option

* Improvements:

    * [MCLEAN-89] - Add GitHub Information
    * [MCLEAN-90] - Custom search broken on pages rendered using Fluido Skin 1.7
    * [MCLEAN-91] - Upgrade maven-plugins to 34
    * [MCLEAN-98] - Upgrade maven-plugin parent to 35

* Tasks:

    * [MCLEAN-94] - Update plugin dependencies
    * [MCLEAN-97] - Require Java 8

* Dependency upgrades:

    * [MCLEAN-87] - Upgrade maven-plugins parent to version 32
    * [MCLEAN-92] - Require Maven 3.1.1 (drop dependency to Maven 3.0)
    * [MCLEAN-96] - Require Maven 3.2.5+

Enjoy,

-The Apache Maven team
