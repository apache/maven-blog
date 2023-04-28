---
layout: post
title: "Apache Maven Dependency Plugin Version 3.3.0 Released"
date: '2022-03-11T17:38:44+00:00'
permalink: apache-maven-dependency-plugin-3-3-0
categories:
- Maven
- Maven-Plugin-Releases
---
The Apache Maven team is pleased to announce the release of the
[Apache Maven Dependency Plugin, version 3.3.0](https://maven.apache.org/plugins/maven-dependency-plugin/).

The dependency plugin provides the capability to manipulate artifacts. It
can copy and/or unpack artifacts from local or remote repositories to a
specified location.

https://maven.apache.org/plugins/maven-dependency-plugin/

You should specify the version in your project's plugin configuration:

```xml
<plugin>
    <groupId>org.apache.maven.plugins</groupId>
    <artifactId>maven-dependency-plugin</artifactId>
    <version>3.3.0</version>
</plugin>
``` 

You can download the appropriate sources etc. from the download page:

https://maven.apache.org/plugins/maven-dependency-plugin/download.cgi


<!-- more -->

[Release Notes - Maven Dependency Plugin - Version 3.3.0](https://issues.apache.org/jira/secure/ReleaseNote.jspa?version=12340588&styleName=Text&projectId=12317227)


* Bugs:
    * [MDEP-679](https://issues.apache.org/jira/browse/MDEP-679) - mvn dependency:analyze detected wrong transitive dependency
    * [MDEP-742](https://issues.apache.org/jira/browse/MDEP-742) - dependency plugin does not work with JDK 16
    * [MDEP-752](https://issues.apache.org/jira/browse/MDEP-752) - skip dependency analyze in ear packaging
    * [MDEP-753](https://issues.apache.org/jira/browse/MDEP-753) - Non-test dependency reported as Non-test scoped test only dependency
    * [MDEP-759](https://issues.apache.org/jira/browse/MDEP-759) - 'Dependency not found' with 3.2.0 and Java-17 while analyzing
    * [MDEP-761](https://issues.apache.org/jira/browse/MDEP-761) - Tree plugin does not terminate with 3.2.0
    * [MDEP-769](https://issues.apache.org/jira/browse/MDEP-769) - Minor improvement - continue
    * [MDEP-774](https://issues.apache.org/jira/browse/MDEP-774) - analyze-only failed: PermittedSubclasses requires ASM9
    * [MDEP-781](https://issues.apache.org/jira/browse/MDEP-781) - Broken Link to "Introduction to Dependency Mechanism Page"
    * [MDEP-783](https://issues.apache.org/jira/browse/MDEP-783) - TreeMojo docs say scope doesn't work due to MSHARED-4
    * [MDEP-786](https://issues.apache.org/jira/browse/MDEP-786) - Sealed classes not supported

* New Feature:
    * [MDEP-787](https://issues.apache.org/jira/browse/MDEP-787) - Allow ignoring non-test-scoped dependencies

* Improvements:
    * [MDEP-763](https://issues.apache.org/jira/browse/MDEP-763) - Minor improvements
    * [MDEP-768](https://issues.apache.org/jira/browse/MDEP-768) - GitHub Action build improvement
    * [MDEP-779](https://issues.apache.org/jira/browse/MDEP-779) - dependency:analyze should list the classes that cause a used undeclared dependency
    * [MDEP-789](https://issues.apache.org/jira/browse/MDEP-789) - Improve documentation of analyze - Non-test scoped

* Task:
    * [MDEP-760](https://issues.apache.org/jira/browse/MDEP-760) - Java 1.8 as minimum

* Dependency upgrades:
    * [MDEP-766](https://issues.apache.org/jira/browse/MDEP-766) - Upgrade maven-invoker-plugin to version 3.2.2
    * [MDEP-784](https://issues.apache.org/jira/browse/MDEP-784) - Upgrade maven-dependency-analyzer to 1.12.0
    * [MDEP-788](https://issues.apache.org/jira/browse/MDEP-788) - Upgrade maven-reporting-impl to version 3.1.0
    * [MDEP-795](https://issues.apache.org/jira/browse/MDEP-795) - Update Jetty to 9.4.45.v20220203
    * [MDEP-796](https://issues.apache.org/jira/browse/MDEP-796) - Upgrade Maven Parent to 35
    * [MDEP-797](https://issues.apache.org/jira/browse/MDEP-797) - Update transitive dependency commons-beanutils to 1.9.4
    * [MDEP-798](https://issues.apache.org/jira/browse/MDEP-798) - Upgrade maven-dependency-tree from 3.0.1 to 3.1.0

Enjoy,

-The Apache Maven team

