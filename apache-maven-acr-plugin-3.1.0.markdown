---
title: "Apache Maven ACR Plugin Version 3.1.0 Released"
date: '2018-06-23T19:36:56+00:00'
permalink: apache-maven-acr-plugin-3-1-0
categories:
  - Maven-ACR-Plugin
  - Maven-Plugin-Releases
---
The Apache Maven team is pleased to announce the release of the
[Apache Maven ACR Plugin, Version 3.1.0](https://maven.apache.org/plugins/maven-acr-plugin).

This plugin generates J2EE Application Client file.

Important Note: This is a Maven 3.X only plugin and needs JDK 7 to run.

```xml
<plugin>
  <groupId>org.apache.maven.plugins</groupId>
  <artifactId>maven-acr-plugin</artifactId>
  <version>3.1.0</version>
</plugin>
```

You can download the appropriate sources etc. from the [download page](https://maven.apache.org/plugins/maven-acr-plugin/download.cgi).

<!-- more -->

[Release Notes - Apache Maven ACR Version 3.1.0](https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317020&version=12334755)


Bugs:

* [MACR-41](https://issues.apache.org/jira/browse/MACR-41) - Upgrade of plexus-interpolation 1.24 to correct escaping issue.
* [MACR-44](https://issues.apache.org/jira/browse/MACR-44) - Upgrade mave-surefire/failsafe-plugin 2.21.0

Improvement:

* [MACR-30](https://issues.apache.org/jira/browse/MACR-30) - Add LifecycleMapping and ArtifactHandler from maven-core to target packaging plugin

Dependency upgrades:

* [MACR-28](https://issues.apache.org/jira/browse/MACR-28) - Upgrade plexus-archiver from 3.0.1 to 3.0.3
* [MACR-29](https://issues.apache.org/jira/browse/MACR-29) - Upgrade plexus-archiver from 3.0.3 to 3.1
* [MACR-31](https://issues.apache.org/jira/browse/MACR-31) - Upgrade plexus-archiver from 3.1 to 3.1.1 / maven-archiver from 3.0.0 to 3.0.2
* [MACR-32](https://issues.apache.org/jira/browse/MACR-32) - Dependency updates.
* [MACR-33](https://issues.apache.org/jira/browse/MACR-33) - Upgrade to maven-plugins version 30
* [MACR-34](https://issues.apache.org/jira/browse/MACR-34) - Upgrade of 'plexus-archiver' to version 3.3.
* [MACR-35](https://issues.apache.org/jira/browse/MACR-35) - Upgrade maven-archiver to 3.1.0
* [MACR-36](https://issues.apache.org/jira/browse/MACR-36) - Upgrade maven-filtering to 3.1.1
* [MACR-37](https://issues.apache.org/jira/browse/MACR-37) - Upgrade plexus-interpolation to 1.22
* [MACR-38](https://issues.apache.org/jira/browse/MACR-38) - Upgrade maven-archiver to 3.1.0
* [MACR-39](https://issues.apache.org/jira/browse/MACR-39) - Upgrade of plexus-archiver to 3.4.
* [MACR-40](https://issues.apache.org/jira/browse/MACR-40) - Upgrade of maven-archiver to 3.1.1.
* [MACR-42](https://issues.apache.org/jira/browse/MACR-42) - Upgrade parent to 31
* [MACR-43](https://issues.apache.org/jira/browse/MACR-43) - Upgrade plexus-utils 3.1.0 / maven-archiver / plexus-achiver
* [MACR-45](https://issues.apache.org/jira/browse/MACR-45) - Upgrade plexus-archiver to 3.6.0
* [MACR-46](https://issues.apache.org/jira/browse/MACR-46) - Upgrade plexus-interpolation to 1.25

Enjoy,

-The Apache Maven team
