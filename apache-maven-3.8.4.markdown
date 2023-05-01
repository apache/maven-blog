---
layout: post
title: "Apache Maven 3.8.4 Released"
date: '2021-11-20T17:38:56+00:00'
permalink: apache-maven-3-8-4
categories:
  - Maven-Core-Releases
---
The Apache Maven team is pleased to announce the release of the [Apache Maven 3.8.4](https://maven.apache.org/ref/3.8.4/)

Apache Maven is a software project management and comprehension tool. Based on the concept
of a project object model (POM), Maven can manage a project's build, reporting and documentation
from a central piece of information.

Maven 3.8.4 is available via https://maven.apache.org/download.cgi

The core release is independent of plugin releases. Further releases of plugins will be made
separately.

If you have any questions, please consult:

- the web site: https://maven.apache.org/
- the maven-user mailing list: https://maven.apache.org/mailing-lists.html
- the reference documentation: https://maven.apache.org/ref/3.8.4/

Release Notes - Maven - Version 3.8.4

* Bugs:

    * [MNG-7270](https://issues.apache.org/jira/browse/MNG-7270) - Maven startup script (init) calls which(1) which is an external command
    * [MNG-7285](https://issues.apache.org/jira/browse/MNG-7285) - [Regression] MavenProject.getArtifacts() not returning correct value across multiple threads
    * [MNG-7300](https://issues.apache.org/jira/browse/MNG-7300) - [Regression] Reloading web application (Enter) fails due to java.lang.ClassNotFoundException

* Task:

    * [MNG-7312](https://issues.apache.org/jira/browse/MNG-7312) - Revert ThreadLocal approach from MNG-6843 and MNG-7251

* Dependency upgrade:

    * [MNG-7331](https://issues.apache.org/jira/browse/MNG-7331) - Upgrade Jansi to 2.4.0

For more information read https://maven.apache.org/docs/3.8.4/release-notes.html

Enjoy!

- The Maven Team
