---
layout: post
title: "Apache Maven Help Plugin Version 3.0.0 Released"
date: '2018-03-18T09:42:47+00:00'
permalink: maven-help-plugin-3-0-0
categories:
  - Maven-Help-Plugin
  - Maven-Plugin-Releases
---
The Apache Maven team is pleased to announce the release of the
[Apache Maven Help Plugin, version 3.0.0](https://maven.apache.org/plugins/maven-help-plugin/)

The Maven Help Plugin is used to get relative information about a project or
the system. It can be used to get a description of a particular plugin,
including the plugin's goals with their parameters and component requirements,
the effective POM and effective settings of the current build, and the profiles
applied to the current project being built.

You should specify the version in your project's plugin configuration:

```xml
<plugin>
  <groupId>org.apache.maven.plugins</groupId>
  <artifactId>maven-help-plugin</artifactId>
  <version>3.0.0</version>
</plugin>
```

You can download the appropriate [sources etc. from the download page](https://maven.apache.org/plugins/maven-help-plugin/download.cgi).


<!-- more -->

[Release Notes - Maven Help Plugin - Version 3.0.0](https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317522&version=12330788)

Bugs:

* [MPH-53](https://issues.apache.org/jira/browse/MPH-53) - mvn help:describe returns the version that is specified in metadata instead of  the one in the parent pom
* [MPH-87](https://issues.apache.org/jira/browse/MPH-87) - help:effective-pom/effective-settings uses platform encoding and garbles non-ASCII characters, emits invalid XML
* [MPH-97](https://issues.apache.org/jira/browse/MPH-97) - [Patch] maven-help-plugin does not build with latest version of maven-plugin-testing-harness
* [MPH-99](https://issues.apache.org/jira/browse/MPH-99) - Evaluate has no output in quiet mode
* [MPH-105](https://issues.apache.org/jira/browse/MPH-105) - Effective pom aggregation is not triggered
* [MPH-107](https://issues.apache.org/jira/browse/MPH-107) - Mojos use inconsistent line endings throughout
* [MPH-108](https://issues.apache.org/jira/browse/MPH-108) - Patch for MPH-72 not fully applied
* [MPH-110](https://issues.apache.org/jira/browse/MPH-110) - Cannot run ITs successfully
* [MPH-111](https://issues.apache.org/jira/browse/MPH-111) - IT 'effective-pom_properties' fails if run with -Dinvoker.mergeUserSettings
* [MPH-114](https://issues.apache.org/jira/browse/MPH-114) - Goal fails with “Unable to get the POM for the artifact”
* [MPH-119](https://issues.apache.org/jira/browse/MPH-119) - The "artifact" parameter is not taken into account with Maven 3
* [MPH-121](https://issues.apache.org/jira/browse/MPH-121) - incorrect text in help:describe for cmd
* [MPH-123](https://issues.apache.org/jira/browse/MPH-123) - all-profiles does not show right active status

Improvements:

* [MPH-106](https://issues.apache.org/jira/browse/MPH-106) - add gav parameter to calculate effective pom for any gav, not only reactor
* [MPH-109](https://issues.apache.org/jira/browse/MPH-109) - Use ISO 8601 date format for the remaining goals
* [MPH-116](https://issues.apache.org/jira/browse/MPH-116) - Printout the information if a goal is a report goal or not
* [MPH-120](https://issues.apache.org/jira/browse/MPH-120) - Migrate plugin to Maven 3.0
* [MPH-124](https://issues.apache.org/jira/browse/MPH-124) - Show parameter aliases in describe goal

Tasks:

* [MPH-103](https://issues.apache.org/jira/browse/MPH-103) - Remove unused dependency maven-monitor
* [MPH-112](https://issues.apache.org/jira/browse/MPH-112) - Upgrade to Commons Lang3
* [MPH-126](https://issues.apache.org/jira/browse/MPH-126) - Require Java 7
* [MPH-132](https://issues.apache.org/jira/browse/MPH-132) - Drop parameter 'medium'
* [MPH-133](https://issues.apache.org/jira/browse/MPH-133) - Drop deprecated alias 'full'
* [MPH-134](https://issues.apache.org/jira/browse/MPH-134) - Drop deprecated alias 'mojo'

Dependency upgrades:

* [MPH-102](https://issues.apache.org/jira/browse/MPH-102) - Upgrade to maven-plugins parent version 27
* [MPH-104](https://issues.apache.org/jira/browse/MPH-104) - Upgrade maven-plugin-testing-harness to 1.3
* [MPH-117](https://issues.apache.org/jira/browse/MPH-117) - Upgrade plexus-utils to 3.0.22
* [MPH-118](https://issues.apache.org/jira/browse/MPH-118) - Upgrade maven-plugins to version 30
* [MPH-125](https://issues.apache.org/jira/browse/MPH-125) - Upgrade parent to 31
* [MPH-127](https://issues.apache.org/jira/browse/MPH-127) - Upgrade Maven  Artifact Transfer to 0.9.1
* [MPH-128](https://issues.apache.org/jira/browse/MPH-128) - Upgrade Maven Reporting Exec to 1.4
* [MPH-129](https://issues.apache.org/jira/browse/MPH-129) - Upgrade Plexus Utils to 3.1.0
* [MPH-130](https://issues.apache.org/jira/browse/MPH-130) - Upgrade XStream to 1.4.7
* [MPH-131](https://issues.apache.org/jira/browse/MPH-131) - Ugprade Commons Lang to 3.7


Enjoy,

-The Apache Maven team

