---
layout: post
title: "Apache Maven 3.5.4 Released"
date: '2018-06-22T18:57:38+00:00'
permalink: apache-maven-release-3-5-4
categories:
- Maven
- Maven-Releases
---
The Apache Maven team is pleased to announce the release of the Apache
Maven 3.5.4.

Apache Maven is a software project management and comprehension tool. Based
on the concept of a project object model (POM), Maven can manage a
project's build, reporting and documentation from a central piece of
information.

You can find out more about Apache Maven at https://maven.apache.org

You can download the appropriate sources etc. from the download page:
https://maven.apache.org/download.cgi


Contributors
============
The Apache Maven value community before code and so firstly the team would
like to thank the following contributors, without whom this release would
not have been possible:

Code contributors:

- https://github.com/eis
- Florian Brunner
- Łukasz Dywicki
- Sylwester Lachiewicz

Issue reporters:

- Falko Modler
- Jarkko Rantavuori
- Łukasz Dywicki
- Mike Kelly
- Sylwester Lachiewicz

Community testers participating in voting for this release:

- Dejan Stojadinovic
- Enrico Olivelli
- Romain Manni-Bucau

Thank you all for your time and feedback (and apologies if we have missed
anyone)

Release Notes - Maven - Version 3.5.4
=====================================

Bugs:

* [MNG-6370](https://issues.apache.org/jira/browse/MNG-6370) - ConcurrencyDependencyGraph#getNumberOfBuilds() does not remove finished projects from unfinished ones
* [MNG-6372](https://issues.apache.org/jira/browse/MNG-6372) - On Windows Maven can output spurious ANSI escapes such as [0m [0m
* [MNG-6382](https://issues.apache.org/jira/browse/MNG-6382) - JANSI fails frequently with NumberFormatException when building in parallel
* [MNG-6386](https://issues.apache.org/jira/browse/MNG-6386) - ${project.baseUri} is not a valid URI (according to RFC 3986)
* [MNG-6388](https://issues.apache.org/jira/browse/MNG-6388) - Error Fetching Artifacts: "[B cannot be cast to java.lang.String"
* [MNG-6403](https://issues.apache.org/jira/browse/MNG-6403) - Artifact#VERSION_FILE_PATTERN does not escape period between date and time
* [MNG-6410](https://issues.apache.org/jira/browse/MNG-6410) - Add groupId to --resume-from suggestion if artifactId is not unique in reactor

Improvements:

* [MNG-5756](https://issues.apache.org/jira/browse/MNG-5756) - Java home output in mvn -v is misleading
* [MNG-5940](https://issues.apache.org/jira/browse/MNG-5940) - Change the maven-source-plugin jar goal into jar-no-fork in Maven Super POM
* [MNG-6362](https://issues.apache.org/jira/browse/MNG-6362) - Add documentation information for GitHub
* [MNG-6363](https://issues.apache.org/jira/browse/MNG-6363) - Remove secret thread configuration property from code
* [MNG-6364](https://issues.apache.org/jira/browse/MNG-6364) - Enhanced Jenkinsfile to test Core with JDK 9
* [MNG-6411](https://issues.apache.org/jira/browse/MNG-6411) - Improve readability of project list returned when --resume-from option value is invalid

Task:

* [MNG-6377](https://issues.apache.org/jira/browse/MNG-6377) - switch from Git-WIP to Gitbox

Dependency upgrades:

* [MNG-6344](https://issues.apache.org/jira/browse/MNG-6344) - Upgrade Guice to 4.2.0
* [MNG-6423](https://issues.apache.org/jira/browse/MNG-6423) - Upgrade to Wagon 3.1.0

Share and Enjoy,

-The Apache Maven team

