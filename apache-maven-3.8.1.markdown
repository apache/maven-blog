---
layout: post
title: "Apache Maven 3.8.1 Released"
date: '2021-04-04T19:26:21+00:00'
permalink: apache-maven-3-8-1
categories:
  - Maven-Core-Releases
---
The Apache Maven team is pleased to announce the release of the [Apache Maven 3.8.1](https://maven.apache.org/ref/3.8.1/)

Apache Maven is a software project management and comprehension tool. Based on the concept
of a project object model (POM), Maven can manage a project's build, reporting and documentation
from a central piece of information.

Maven 3.8.1 is available via https://maven.apache.org/download.cgi

The core release is independent of plugin releases. Further releases of plugins will be made
separately.

If you have any questions, please consult:

- the web site: https://maven.apache.org/
- the maven-user mailing list: https://maven.apache.org/mailing-lists.html
- the reference documentation: https://maven.apache.org/ref/3.8.1/

RELEASE DETAILS

This release with CVE fixes is a result based on the findings and feedback of Jonathan Leitschuh and Olaf Flebbe.

One of the changes that might impact your builds is the way custom repositories defined in dependency
POMs will be handled.
By default external insecure repositories will now be blocked (localhost over HTTP will still work).
Configuration can be adjusted via the conf/settings.xml.

Release Notes - Maven - Version 3.8.1

* Bug:
    * [MNG-7128](https://issues.apache.org/jira/browse/MNG-7128) - improve error message when blocked repository defined in build POM

* New Features:

    * [MNG-7116](https://issues.apache.org/jira/browse/MNG-7116) - Add support for mirror selector on external:http:*
    * [MNG-7117](https://issues.apache.org/jira/browse/MNG-7117) - Add support for blocking mirrors
    * [MNG-7118](https://issues.apache.org/jira/browse/MNG-7118) - Block external HTTP repositories by default

* Dependency upgrades:

    * [MNG-7119](https://issues.apache.org/jira/browse/MNG-7119) - Upgrade Maven Wagon to 3.4.3
    * [MNG-7123](https://issues.apache.org/jira/browse/MNG-7123) - Upgrade Maven Resolver to 1.6.2

For more information read https://maven.apache.org/docs/3.8.1/release-notes.html

Enjoy!

- The Maven Team
