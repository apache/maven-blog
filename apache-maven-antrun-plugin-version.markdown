---
layout: post
title: "Apache Maven AntRun Plugin Version 3.0.0 Released"
date: '2020-04-15T23:58:15+00:00'
permalink: apache-maven-antrun-plugin-version
categories:
  - Maven
  - Maven-Plugin-Releases
---
The Apache Maven team is pleased to announce the release of the [Apache
Maven AntRun Plugin, version 3.0.0](https://maven.apache.org/plugins/maven-antrun-plugin/).

This plugin provides the ability to run Ant tasks from within Maven. You can even embed your Ant
scripts in the POM!

You should specify the version in your project's plugin configuration:

```xml
<plugin>
  <groupId>org.apache.maven.plugins</groupId>
  <artifactId>maven-antrun-plugin</artifactId>
  <version>3.0.0</version>
</plugin>
```

You can download the [appropriate sources etc. from the download page][download-page]

<!-- more -->


[Release Notes - Maven AntRunPlugin - Version 3.0.0](https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317921&version=12346981)


* Bugs:

    * [MANTRUN-172](https://issues.apache.org/jira/browse/MANTRUN-172) - Properties passed to Maven as -D don't get passed to <ant> invocations when a profile sets the same property
    * [MANTRUN-178](https://issues.apache.org/jira/browse/MANTRUN-178) - Ignore precedence of mvn command line over property defined in <properties> section
    * [MANTRUN-179](https://issues.apache.org/jira/browse/MANTRUN-179) - Seems impossible to use combine.* attributes with maven-antrun-plugin configuration
    * [MANTRUN-181](https://issues.apache.org/jira/browse/MANTRUN-181) - AttachArtifact task does not work in external Ant build file
    * [MANTRUN-192](https://issues.apache.org/jira/browse/MANTRUN-192) - filterArtifacts in DependencyFilesetsTask includes entire maven.local.repository
    * [MANTRUN-204](https://issues.apache.org/jira/browse/MANTRUN-204) - antrun loops the backing map of java.util.Properties withouth checking type safety
    * [MANTRUN-205](https://issues.apache.org/jira/browse/MANTRUN-205) - maven-antrun-plugin pages at maven.apache.org still have bad url codehaus references
    * [MANTRUN-221](https://issues.apache.org/jira/browse/MANTRUN-221) - Fails to pass maven properties set in user properties only

* Improvements:

    * [MANTRUN-201](https://issues.apache.org/jira/browse/MANTRUN-201) - Migrate plugin to Maven 3.0
    * [MANTRUN-202](https://issues.apache.org/jira/browse/MANTRUN-202) - Fail the build when deprecated parameters tasks, sourceRoot or testSourceRoot are used
    * [MANTRUN-217](https://issues.apache.org/jira/browse/MANTRUN-217) - Require Java 7
    * [MANTRUN-222](https://issues.apache.org/jira/browse/MANTRUN-222) - make build Reproducible, upgrade maven-plugins pom to 34

* Tasks:

    * [MANTRUN-209](https://issues.apache.org/jira/browse/MANTRUN-209) - Add documentation information for GitHub
    * [MANTRUN-211](https://issues.apache.org/jira/browse/MANTRUN-211) - Upgrade mave-surefire/failsafe-plugin 2.21.0

* Dependency upgrades:

    * [MANTRUN-203](https://issues.apache.org/jira/browse/MANTRUN-203) - Upgrade to maven-plugins 30
    * [MANTRUN-210](https://issues.apache.org/jira/browse/MANTRUN-210) - Upgrade parent to 31
    * [MANTRUN-212](https://issues.apache.org/jira/browse/MANTRUN-212) - Upgrade plexus-utils 3.1.0
    * [MANTRUN-213](https://issues.apache.org/jira/browse/MANTRUN-213) - Upgrade plexus-utils 3.1.0
    * [MANTRUN-214](https://issues.apache.org/jira/browse/MANTRUN-214) - upgrade default Ant version to 1.9.14
    * [MANTRUN-215](https://issues.apache.org/jira/browse/MANTRUN-215) - Upgrade maven-plugins parent to version 32
    * [MANTRUN-218](https://issues.apache.org/jira/browse/MANTRUN-218) - Upgrade JUnit to 4.13
    * [MANTRUN-219](https://issues.apache.org/jira/browse/MANTRUN-219) - Upgrade XMLUnit to 2.6.4 (test dependency)

Enjoy,

-The Apache Maven team

[download-page]: https://maven.apache.org/shared/maven-archiver/download.cgi
