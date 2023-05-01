---
layout: post
title: "Apache Maven 3.5.2 Released"
date: '2017-10-25T12:34:34+00:00'
permalink: apache-maven-3-5-2
categories:
  - Maven-Core-Releases
---
The Apache Maven team is pleased to announce the release of the Apache
Maven 3.5.2

You can download the appropriate sources etc. from the [download page](https://maven.apache.org/download.cgi).


Contributors
============
The Apache Maven team would like to thank the following contributors,
without whom this release would not have been possible:

Code contributors:

- Mario Krizmanic
- Dejan Stojadinovic
- Anton Tanasenko
- Stefan Eicher

Issue reporters:

- Marcel Schutte
- Mario Krizmanic
- Charles Gould
- Brian Oxley
- Anton Tanasenko
- Gregor B. Rosenauer
- Sylwester Lachiewicz
- Stefan Eicher
- Manuel Ryan

Community testers participating in voting for this release series:

- Mark Derricutt
- Dejan Stojadinovic
- Thomas Collignon
- Grzegorz Grzybek
- Petar Tahchiev
- jieryn
- Petr Široký

Thank you for your time and feedback.


[Release Notes - Maven - Version 3.5.2](https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12316922&version=12338964)

<!-- more -->

Sub-tasks:

* [MNG-6186](https://issues.apache.org/jira/browse/MNG-6186) - switch to improved HawtJNI
* [MNG-6280](https://issues.apache.org/jira/browse/MNG-6280) - ArrayIndexOutOfBoundsException caused by pom.xml with process instructions

Bugs:

* [MNG-5935](https://issues.apache.org/jira/browse/MNG-5935) - Optional true getting lost in managed dependencies when transitive
* [MNG-6127](https://issues.apache.org/jira/browse/MNG-6127) - Fix plugin execution configuration interference
* [MNG-6148](https://issues.apache.org/jira/browse/MNG-6148) - Can't package and assemble with JDK9/Jigsaw
* [MNG-6149](https://issues.apache.org/jira/browse/MNG-6149) - MetadataResolutionResult#getGraph() never resolves request type 'test'
* [MNG-6205](https://issues.apache.org/jira/browse/MNG-6205) - Non-ascii chars in name element are displayed as question marks in Win CLI output (regression)
* [MNG-6210](https://issues.apache.org/jira/browse/MNG-6210) - can't load @SessionScoped/@MojoExecutionScoped components from .mvn/extensions.xml
* [MNG-6223](https://issues.apache.org/jira/browse/MNG-6223) - mvn -f outputs invalid error when specifying POM directory
* [MNG-6233](https://issues.apache.org/jira/browse/MNG-6233) - maven-resolver-provider mixes JRS 330 and Plexus annotations
* [MNG-6234](https://issues.apache.org/jira/browse/MNG-6234) - Regression 6182a208: library.jansi.path does not point to proper directory
* [MNG-6240](https://issues.apache.org/jira/browse/MNG-6240) - Duplicate components in plugin extension realm when plugin depends on maven-aether-resolver
* [MNG-6242](https://issues.apache.org/jira/browse/MNG-6242) - No color for maven on Cygwin

Improvements:

* [MNG-5457](https://issues.apache.org/jira/browse/MNG-5457) - Show repository id when downloading or uploading from/to a remote repository
* [MNG-6025](https://issues.apache.org/jira/browse/MNG-6025) - Add a ProjectArtifactsCache similar to PluginArtifactsCache
* [MNG-6123](https://issues.apache.org/jira/browse/MNG-6123) - detect self references in POM and fail fast
* [MNG-6174](https://issues.apache.org/jira/browse/MNG-6174) - Clean Up Maven Model
* [MNG-6196](https://issues.apache.org/jira/browse/MNG-6196) - Update slf4j and simplify its color integration
* [MNG-6203](https://issues.apache.org/jira/browse/MNG-6203) - Minor cleanup in MavenCli.java
* [MNG-6206](https://issues.apache.org/jira/browse/MNG-6206) - We should produce a WARNING by using RELEASE, LATEST as versions
* [MNG-6207](https://issues.apache.org/jira/browse/MNG-6207) - Create WARNINGs in case of using system scope
* [MNG-6228](https://issues.apache.org/jira/browse/MNG-6228) - Optionality not displayed in dependency tree when run in debug mode

New Features:

* [MNG-6084](https://issues.apache.org/jira/browse/MNG-6084) - Support JSR 250 annotations
* [MNG-6220](https://issues.apache.org/jira/browse/MNG-6220) - Add CLI options to control color output

Tasks:

* [MNG-6167](https://issues.apache.org/jira/browse/MNG-6167) - Clean up dependency mess (reported by dependency:analyze)
* [MNG-6258](https://issues.apache.org/jira/browse/MNG-6258) - Upgrade to Maven Resolver 1.1.0

Enjoy,

-The Apache Maven team
