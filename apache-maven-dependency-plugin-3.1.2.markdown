---
layout: post
title: "Apache Maven Dependency Plugin Version 3.1.2 Released"
date: '2020-03-12T20:43:23+00:00'
permalink: apache-maven-dependency-plugin-3-1-2
categories:
- Maven
- Maven-Plugin-Releases
---
The Apache Maven team is pleased to announce the release of the
[Apache Maven Dependency Plugin, version 3.1.2](https://maven.apache.org/plugins/maven-dependency-plugin/).

The dependency plugin provides the capability to manipulate artifacts. It
can copy and/or unpack artifacts from local or remote repositories to a
specified location.

https://maven.apache.org/plugins/maven-dependency-plugin/

You should specify the version in your project's plugin configuration:

```xml
<plugin>
    <groupId>org.apache.maven.plugins</groupId>
    <artifactId>maven-dependency-plugin</artifactId>
    <version>3.1.2</version>
</plugin>
``` 

You can download the appropriate sources etc. from the download page:

https://maven.apache.org/plugins/maven-dependency-plugin/download.cgi


<!-- more -->

[Release Notes - Maven Dependency Plugin - Version 3.1.2](https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317227&version=12343772)

* Bugs:

    * [MDEP-204](https://issues.apache.org/jira/browse/MDEP-204) - go-offline fails to resolve artifact available in maven reactor
    * [MDEP-545](https://issues.apache.org/jira/browse/MDEP-545) - Several classes create mixed-style line endings
    * [MDEP-579](https://issues.apache.org/jira/browse/MDEP-579) - Regression: get goal does not pass server credentials to BasicRepositoryConnector
    * [MDEP-613](https://issues.apache.org/jira/browse/MDEP-613) - Analyze failed: Unsupported class file major version 55 (Java 11)
    * [MDEP-655](https://issues.apache.org/jira/browse/MDEP-655) - The unpack integration test fails intermittent.
    * [MDEP-663](https://issues.apache.org/jira/browse/MDEP-663) - Analyze failed: Unsupported class file major version 57 (Java 13)

* New Feature:

    * [MDEP-628](https://issues.apache.org/jira/browse/MDEP-628) - Unpacking File Mappers

* Improvements:

    * [MDEP-653](https://issues.apache.org/jira/browse/MDEP-653) - add info message to purge-local-repository goal even in non-verbose mode
    * [MDEP-664](https://issues.apache.org/jira/browse/MDEP-664) - Get goal misses unit tests
    * [MDEP-672](https://issues.apache.org/jira/browse/MDEP-672) - make build Reproducible

* Dependency upgrades:

    * [MDEP-624](https://issues.apache.org/jira/browse/MDEP-624) - Upgrade maven-plugins parent to version 32
    * [MDEP-625](https://issues.apache.org/jira/browse/MDEP-625) - Upgrade maven-artifact-transfer to 0.11.0
    * [MDEP-626](https://issues.apache.org/jira/browse/MDEP-626) - Upgrade struts and xerces due to CVEs
    * [MDEP-634](https://issues.apache.org/jira/browse/MDEP-634) - Upgrade plexus-io to 3.1.0
    * [MDEP-635](https://issues.apache.org/jira/browse/MDEP-635) - Upgrade dependency-analyzer 1.11.0
    * [MDEP-636](https://issues.apache.org/jira/browse/MDEP-636) - Upgrade maven-shared-utils 3.2.1
    * [MDEP-637](https://issues.apache.org/jira/browse/MDEP-637) - Upgrade dependency-analyzer 1.11.0
    * [MDEP-641](https://issues.apache.org/jira/browse/MDEP-641) - Upgrade plexus-archiver to 4.1.0
    * [MDEP-642](https://issues.apache.org/jira/browse/MDEP-642) - Upgrade plexus-utils to 3.2.0
    * [MDEP-647](https://issues.apache.org/jira/browse/MDEP-647) - Upgrade maven-common-artifact-filters to 3.1.0
    * [MDEP-656](https://issues.apache.org/jira/browse/MDEP-656) - Upgrade plexus-utils to 3.3.0
    * [MDEP-668](https://issues.apache.org/jira/browse/MDEP-668) - Upgrade plexus-interpolation 1.26
    * [MDEP-673](https://issues.apache.org/jira/browse/MDEP-673) - Upgrade asm to 7.3.1

Enjoy,

-The Apache Maven team
