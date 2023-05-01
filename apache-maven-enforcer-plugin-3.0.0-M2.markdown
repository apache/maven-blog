---
layout: post
title: "Apache Maven Enforcer Plugin Version 3.0.0-M2 Released"
date: '2018-06-17T10:00:00+00:00'
permalink: apache-maven-enforcer-plugin-3-0-0-M2
categories:
  - Maven-Enforcer-Plugin
  - Maven-Plugin-Releases
---
The Apache Maven team is pleased to announce the release of the
[Apache Maven Enforcer Plugin, version 3.0.0-M2](https://maven.apache.org/plugins/maven-enforcer-plugin/).

You should specify the version in your project's plugin configuration:

```xml
<plugin>
  <groupId>org.apache.maven.plugins</groupId>
  <artifactId>maven-enforcer-plugin</artifactId>
  <version>3.0.0-M2</version>
</plugin>
```

You can download the appropriate sources etc. from the download page:

https://maven.apache.org/enforcer/download.cgi

<!-- more -->

[Release Notes - Maven Enforcer Plugin Version 3.0.0-M2 (including 3.0.0-M1)](https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317520&version=12343432&styleName=Text)


Bugs:

* [MENFORCER-234](https://issues.apache.org/jira/browse/MENFORCER-234) - Link to plugin's web site is reported as redirected by maven linkcheck plugin.
* [MENFORCER-239](https://issues.apache.org/jira/browse/MENFORCER-239) - Fix link in navigation (enforcer/maven-enforcer-plugin/index.html) RESOURCES
* [MENFORCER-240](https://issues.apache.org/jira/browse/MENFORCER-240) - Link to page does not work
* [MENFORCER-265](https://issues.apache.org/jira/browse/MENFORCER-265) - Get site generation working
* [MENFORCER-268](https://issues.apache.org/jira/browse/MENFORCER-268) - Usage of CI friendly version placeholders does not work
* [MENFORCER-274](https://issues.apache.org/jira/browse/MENFORCER-274) - Use of RequireJavaVersion with Java-9 breaking starting at b175
* [MENFORCER-281](https://issues.apache.org/jira/browse/MENFORCER-281) - RequirePluginVersions broken with "CI Friendly versions"

New Features:

* [MENFORCER-204](https://issues.apache.org/jira/browse/MENFORCER-204) - Add new rule: should be able to make sure that project artifact is a Snapshot
* [MENFORCER-247](https://issues.apache.org/jira/browse/MENFORCER-247) - Add a "require file checksum" rule
* [MENFORCER-273](https://issues.apache.org/jira/browse/MENFORCER-273) - RequireUpperBoundDeps.excludes
* [MENFORCER-282](https://issues.apache.org/jira/browse/MENFORCER-282) - Add RequireProfileIdsExist to ensure al mentioned cmdline profiles exist

Improvements:

* [MENFORCER-228](https://issues.apache.org/jira/browse/MENFORCER-228) - DependencyConvergence: Simplify logging errors
* [MENFORCER-253](https://issues.apache.org/jira/browse/MENFORCER-253) - Upgrade maven-shared-components parent to version 30
* [MENFORCER-259](https://issues.apache.org/jira/browse/MENFORCER-259) - The rule BanDuplicatePomDependencyVersions is not documented
* [MENFORCER-263](https://issues.apache.org/jira/browse/MENFORCER-263) - Upgrade mrm-maven-plugin to 1.0.0
* [MENFORCER-266](https://issues.apache.org/jira/browse/MENFORCER-266) - Remove usage of prerequisites in parent pom
* [MENFORCER-291](https://issues.apache.org/jira/browse/MENFORCER-291) - Cleanup ReactorModuleConvergence implementation
* [MENFORCER-292](https://issues.apache.org/jira/browse/MENFORCER-292) - Remove getModelsRecursively from EnforcerRuleUtils
* [MENFORCER-293](https://issues.apache.org/jira/browse/MENFORCER-293) - Remove deprecated marked ignoreParent from BanDistributionManagement

Tasks:

* [MENFORCER-221](https://issues.apache.org/jira/browse/MENFORCER-221) - Removed deprecated marked constructor from EnforcerExpressionEvaluator
* [MENFORCER-272](https://issues.apache.org/jira/browse/MENFORCER-272) - Allow site generation to work
* [MENFORCER-284](https://issues.apache.org/jira/browse/MENFORCER-284) - switch to Git
* [MENFORCER-296](https://issues.apache.org/jira/browse/MENFORCER-296) - Update URL for CI System

Dependency upgrades:

* [MENFORCER-278](https://issues.apache.org/jira/browse/MENFORCER-278) - Upgrade mockito to 2.X to prevent JDK 9 WARNINGs
* [MENFORCER-289](https://issues.apache.org/jira/browse/MENFORCER-289) - Upgrade maven-plugin-plugin to 3.5
* [MENFORCER-290](https://issues.apache.org/jira/browse/MENFORCER-290) - Upgrade plexus-utils 3.1.0
* [MENFORCER-297](https://issues.apache.org/jira/browse/MENFORCER-297) - Upgrade parent to 31
* [MENFORCER-303](https://issues.apache.org/jira/browse/MENFORCER-303) - Upgrade mave-surefire/failsafe-plugin 2.21.0


Enjoy,

-The Apache Maven team

