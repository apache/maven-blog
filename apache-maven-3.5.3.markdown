---
layout: post
title: "Apache Maven 3.5.3 Released"
date: '2018-03-08T16:30:40+00:00'
permalink: apache-maven-3-5-3
categories:
  - Maven-Core-Releases
---
The Apache Maven team is pleased to announce the release of the Apache
Maven 3.5.3

You can download the appropriate sources etc. from the [download page](https://maven.apache.org/download.html)

Contributors
------------

The Apache Maven team would like to thank the following contributors,
without whom this release would not have been possible:

Code contributors:

- Sylwester Lachiewicz
- Bengt Söderberg
- Robin Müller
- Romain Manni-Bucau

Issue reporters:

- Ryan Heaton
- Ryan J McDonough
- Andreas Kurth
- Ben Caradoc-Davies
- Romain Manni-Bucau
- Robin Müller
- Dejan Stojadinović
- Andrew Kennedy
- Sylwester Lachiewicz
- Andy Wilkinson
- Eugene Pliskin
- Tony Guan

Community testers participating in voting for this release:

- Sylwester Lachiewicz
- Grzegorz Grzybek

Thank you for your time and feedback.

Release Notes - Maven - Version 3.5.3

**Known issue:**

* [MNG-6372](https://issues.apache.org/jira/browse/MNG-6372) - On Windows with -T option, Maven can output spurious ANSI escapes such as [0m [0m

Bugs:

* [MNG-6188](https://issues.apache.org/jira/browse/MNG-6188) - Console color not properly reset when interrupting build process
* [MNG-6255](https://issues.apache.org/jira/browse/MNG-6255) - Maven script cannot parse jvm.config with CRLF
* [MNG-6282](https://issues.apache.org/jira/browse/MNG-6282) - Console output has no colors in shell (both Git Bash and Cygwin) [regression in Jansi 1.16 / Maven 3.5.1]
* [MNG-6296](https://issues.apache.org/jira/browse/MNG-6296) - New option -Dstyle.color is not working
* [MNG-6298](https://issues.apache.org/jira/browse/MNG-6298) - 3.5.2: ClassNotFoundException: javax.annotation.security.  RolesAllowed
* [MNG-6300](https://issues.apache.org/jira/browse/MNG-6300) - Multi module release creates empty directories in war file instead of jars
* [MNG-6305](https://issues.apache.org/jira/browse/MNG-6305) - Validation of CI friendly version incorrect
* [MNG-6320](https://issues.apache.org/jira/browse/MNG-6320) - Apparently wrong encoding of non-ascii java class filename in error messages in the maven log
* [MNG-6323](https://issues.apache.org/jira/browse/MNG-6323) - Deadlock in multithreaded dependency resolution
* [MNG-6330](https://issues.apache.org/jira/browse/MNG-6330) - [regression] Parents relativePath not verified anymore

New Feature:

* [MNG-6302](https://issues.apache.org/jira/browse/MNG-6302) - Provide some "progress" hints

Improvement:

* [MNG-5992](https://issues.apache.org/jira/browse/MNG-5992) - Git passwords are exposed as the Super POM still uses Maven Release Plugin 2.3.2
* [MNG-6306](https://issues.apache.org/jira/browse/MNG-6306) - Replace use of Guava in maven-resolver-provider with a lighter weight alternative
* [MNG-6308](https://issues.apache.org/jira/browse/MNG-6308) - display packaging & groupId:artifactId when building a module
* [MNG-6332](https://issues.apache.org/jira/browse/MNG-6332) - Cleaned up mvn.cmd Script
* [MNG-6340](https://issues.apache.org/jira/browse/MNG-6340) - [Performance]To make System.gc() call configurable in target summary code
* [MNG-6342](https://issues.apache.org/jira/browse/MNG-6342) - Emit a WARNING about LATEST/RELEASE in parent
* [MNG-6352](https://issues.apache.org/jira/browse/MNG-6352) - Printout version information at the end of the build

Task:

* [MNG-6331](https://issues.apache.org/jira/browse/MNG-6331) - Remove maven-bundle-pugin from build pluginManagement

Dependency upgrade:

* [MNG-6312](https://issues.apache.org/jira/browse/MNG-6312) - Update Maven Wagon dependency
* [MNG-6335](https://issues.apache.org/jira/browse/MNG-6335) - Update test framework Mockito from 1.10 to 2.12
* [MNG-6353](https://issues.apache.org/jira/browse/MNG-6353) - Upgrade maven-shared-utils to 3.2.1

Enjoy,

-The Apache Maven team
