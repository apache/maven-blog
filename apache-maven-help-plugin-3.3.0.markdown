---
layout: post
title: "Apache Maven Help Plugin Version 3.3.0 Released"
date: '2022-08-16T20:02:02+00:00'
permalink: apache-maven-help-plugin-3-3-0
categories:
  - Maven-Help-Plugin
  - Maven-Plugin-Releases
---
The Apache Maven team is pleased to announce the release of the
[Apache Maven Help Plugin, version 3.3.0](https://maven.apache.org/plugins/maven-help-plugin/)

The Maven Help Plugin is used to get relative information about a project or
the system. It can be used to get a description of a particular plugin,
including the plugin's goals with their parameters and component requirements,
the effective POM and effective settings of the current build, and the profiles
applied to the current project being built.

Important Notes since Version 3.3.0

* JDK 8 minimum requirement
* Minimum Maven version 3.2.5

You should specify the version in your project's plugin configuration:

```xml
<plugin>
  <groupId>org.apache.maven.plugins</groupId>
  <artifactId>maven-help-plugin</artifactId>
  <version>3.3.0</version>
</plugin>
```

You can download the appropriate [sources etc. from the download page](https://maven.apache.org/plugins/maven-help-plugin/download.cgi).


[Release Notes - Maven Help Plugin - Version 3.3.0](https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317522&version=12345417)

* Bugs:

    * [MPH-164](https://issues.apache.org/jira/browse/MPH-164) - Effective-pom ignores artifact argument
    * [MPH-171](https://issues.apache.org/jira/browse/MPH-171) - Plugin repositories are not preserved from project pom

* Improvements:

    * [MPH-162](https://issues.apache.org/jira/browse/MPH-162) - Allow all mojos to be configured to produce repeatable output
    * [MPH-167](https://issues.apache.org/jira/browse/MPH-167) - make build Reproducible
    * [MPH-170](https://issues.apache.org/jira/browse/MPH-170) - Require Maven 3.1.1 (drop dependency to Maven 3.0)

* Tasks:

    * [MPH-187](https://issues.apache.org/jira/browse/MPH-187) - Upgrade to JDK minimum
    * [MPH-188](https://issues.apache.org/jira/browse/MPH-188) - Cleanup - Pom

* Dependency upgrades:

    * [MPH-174](https://issues.apache.org/jira/browse/MPH-174) - Upgrade XStream to 1.4.17
    * [MPH-179](https://issues.apache.org/jira/browse/MPH-179) - Upgrade XStream to 1.4.18
    * [MPH-186](https://issues.apache.org/jira/browse/MPH-186) - maven-parent to 37
    * [MPH-190](https://issues.apache.org/jira/browse/MPH-190) -¡ Upgrade Maven Reporting API to 3.1.1

Enjoy,

-The Apache Maven team

