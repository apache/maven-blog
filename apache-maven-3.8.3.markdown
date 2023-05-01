---
layout: post
title: "Apache Maven 3.8.3 Released"
date: '2021-10-04T20:14:30+00:00'
permalink: apache-maven-3-8-3
categories:
  - Maven-Core-Releases
---
The Apache Maven team is pleased to announce the release of the [Apache Maven 3.8.3](https://maven.apache.org/ref/3.8.3/)

Apache Maven is a software project management and comprehension tool. Based on the concept
of a project object model (POM), Maven can manage a project's build, reporting and documentation
from a central piece of information.

Maven 3.8.3 is available via https://maven.apache.org/download.cgi

The core release is independent of plugin releases. Further releases of plugins will be made
separately.

If you have any questions, please consult:

- the web site: https://maven.apache.org/
- the maven-user mailing list: https://maven.apache.org/mailing-lists.html
- the reference documentation: https://maven.apache.org/ref/3.8.3/

Release Notes - Maven - Version 3.8.3

* Bugs:

    * [MNG-7045](https://issues.apache.org/jira/browse/MNG-7045) - Drop CDI API from Maven
    * [MNG-7214](https://issues.apache.org/jira/browse/MNG-7214) - Bad transitive dependency parent from CDI API
    * [MNG-7215](https://issues.apache.org/jira/browse/MNG-7215) - [Regression] Maven Site Plugin cannot resolve parent site descriptor without locale
    * [MNG-7216](https://issues.apache.org/jira/browse/MNG-7216) - Revert MNG-7170
    * [MNG-7218](https://issues.apache.org/jira/browse/MNG-7218) - [Regression] o.a.m.model.Build.getSourceDirectory() incorrectly returns absolute dir on 3.8.2
    * [MNG-7219](https://issues.apache.org/jira/browse/MNG-7219) - [Regression] plexus-cipher missing from transitive dependencies
    * [MNG-7220](https://issues.apache.org/jira/browse/MNG-7220) - [REGRESSION] test-classpath incorrectly resolved
    * [MNG-7251](https://issues.apache.org/jira/browse/MNG-7251) - Fix threadLocalArtifactsHolder leaking into cloned project
    * [MNG-7253](https://issues.apache.org/jira/browse/MNG-7253) - Relocation message is never shown

* New Feature:

    * [MNG-7164](https://issues.apache.org/jira/browse/MNG-7164) - Add constructor MojoExecutionException(Throwable)

* Improvements:

    * [MNG-7235](https://issues.apache.org/jira/browse/MNG-7235) - Speed improvements when calculating the sorted project graph
    * [MNG-7236](https://issues.apache.org/jira/browse/MNG-7236) - The DefaultPluginVersionResolver should cache results for the session

* Tasks:

    * [MNG-7252](https://issues.apache.org/jira/browse/MNG-7252) - Fix warnings issued by dependency:analyze
    * [MNG-7254](https://issues.apache.org/jira/browse/MNG-7254) - Expand Windows native libraries for Jansi due to JDK-8195129 (workaround)

* Dependency upgrades:

    * [MNG-6818](https://issues.apache.org/jira/browse/MNG-6818) - Upgrade Plexus Utils to 3.3.0
    * [MNG-6841](https://issues.apache.org/jira/browse/MNG-6841) - Upgrade Plexus Interpolation to 1.26
    * [MNG-7246](https://issues.apache.org/jira/browse/MNG-7246) - Upgrade Plexus Cipher and Sec Dispatcher to 2.0
    * [MNG-7250](https://issues.apache.org/jira/browse/MNG-7250) - Upgrade Sisu Inject/Plexus to 0.3.5

For more information read https://maven.apache.org/docs/3.8.3/release-notes.html

Enjoy!

- The Maven Team
