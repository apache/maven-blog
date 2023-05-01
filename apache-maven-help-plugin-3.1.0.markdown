---
layout: post
title: "Apache Maven Help Plugin Version 3.1.0 Released"
date: '2018-06-09T13:49:29+00:00'
permalink: apache-maven-help-plugin-3-1-0
categories:
  - Maven-Help-Plugin
  - Maven-Plugin-Releases
---
The Apache Maven team is pleased to announce the release of the
[Apache Maven Help Plugin, version 3.1.0](https://maven.apache.org/plugins/maven-help-plugin/)

The Maven Help Plugin is used to get relative information about a project or
the system. It can be used to get a description of a particular plugin,
including the plugin's goals with their parameters and component requirements,
the effective POM and effective settings of the current build, and the profiles
applied to the current project being built.

Important Notes since Version 3.0.0

* Maven 3+ only
* JDK 7 minimum requirement


You should specify the version in your project's plugin configuration:

```xml
<plugin>
  <groupId>org.apache.maven.plugins</groupId>
  <artifactId>maven-help-plugin</artifactId>
  <version>3.1.0</version>
</plugin>
```

You can download the appropriate [sources etc. from the download page](https://maven.apache.org/plugins/maven-help-plugin/download.cgi).


<!-- more -->

[Release Notes - Maven Help Plugin - Version 3.1.0](https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317522&version=12343004)

New Feature:

* [MPH-144](https://issues.apache.org/jira/browse/MPH-144) - Add ability to print mvn help:evaluate output to stdout in quiet mode

Improvement:

* [MPH-151](https://issues.apache.org/jira/browse/MPH-151) - Add documentation information for GitHub

Tasks:

* [MPH-145](https://issues.apache.org/jira/browse/MPH-145) - Upgrade mave-surefire/failsafe-plugin 2.21.0
* [MPH-146](https://issues.apache.org/jira/browse/MPH-146) - JavaDoc Issues / Code cleanups

Dependency upgrades:

* [MPH-147](https://issues.apache.org/jira/browse/MPH-147) - plexus-interactivity-api to 1.0-alpha-6
* [MPH-148](https://issues.apache.org/jira/browse/MPH-148) - Upgrade xstream to 1.4.10
* [MPH-149](https://issues.apache.org/jira/browse/MPH-149) - Upgrade jdom-legacy to jdom2 2.0.6

Enjoy,

-The Apache Maven team

