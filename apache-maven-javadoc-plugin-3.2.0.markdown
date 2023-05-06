---
layout: post
title: "Apache Maven JavaDoc Plugin Version 3.2.0 Released"
date: '2020-03-17T19:00:04+00:00'
permalink: apache-maven-javadoc-plugin-3-2-0
categories:
  - Maven-Javadoc-Plugin
  - Maven-Plugin-Releases
---
The Apache Maven team is pleased to announce the release of the
[Apache Maven JavaDoc Plugin, version 3.2.0](https://maven.apache.org/plugins/maven-javadoc-plugin).

The Javadoc Plugin uses the Javadoc tool to generate javadocs for the
specified project.


```xml
<plugin>
  <groupId>org.apache.maven.plugins</groupId>
  <artifactId>maven-javadoc-plugin</artifactId>
  <version>3.2.0</version>
</plugin>
```

You can download the appropriate sources etc. from the download page:

https://maven.apache.org/plugins/maven-javadoc-plugin/download.cgi

[Release Notes - Apache Maven JavaDoc Plugin - Version 3.2.0](https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317529&version=12345698)

* Bugs:

    * [MJAVADOC-607](https://issues.apache.org/jira/browse/MJAVADOC-607) - followLinks fix to get redirect target breaks for certain sites
    * [MJAVADOC-609](https://issues.apache.org/jira/browse/MJAVADOC-609) - Include jars for which module name cannot be determined on the classpath
    * [MJAVADOC-612](https://issues.apache.org/jira/browse/MJAVADOC-612) - UnsupportedOperationException for javadoc:aggregate with multi modules with jpms
    * [MJAVADOC-616](https://issues.apache.org/jira/browse/MJAVADOC-616) - JavadocReportTest.testOptionsUmlautEncoding fails on Windows with default encoding that does not support umlauts
    * [MJAVADOC-620](https://issues.apache.org/jira/browse/MJAVADOC-620) - Maven Javadoc Plugin fails to resolve the dependencies when used with Java 11
    * [MJAVADOC-639](https://issues.apache.org/jira/browse/MJAVADOC-639) - aggregate should use all requires static from maven modules

* New Feature:

    * [MJAVADOC-627](https://issues.apache.org/jira/browse/MJAVADOC-627) - Reproducible Builds: make entries in output jar files reproducible (order + timestamp)

* Improvements:

    * [MJAVADOC-613](https://issues.apache.org/jira/browse/MJAVADOC-613) - Exclude some modules with aggregate goals
    * [MJAVADOC-626](https://issues.apache.org/jira/browse/MJAVADOC-626) - Detect stale files and skip generation if not needed
    * [MJAVADOC-632](https://issues.apache.org/jira/browse/MJAVADOC-632) - agggregate using jpms and non jar module is failing
    * [MJAVADOC-636](https://issues.apache.org/jira/browse/MJAVADOC-636) - Exclude some modules when building aggregate
    * [MJAVADOC-637](https://issues.apache.org/jira/browse/MJAVADOC-637) - make build Reproducible
    * [MJAVADOC-640](https://issues.apache.org/jira/browse/MJAVADOC-640) - Ability to exclude maven modules from javadoc aggregate goals

* Dependency upgrades:

    * [MJAVADOC-635](https://issues.apache.org/jira/browse/MJAVADOC-635) - upgrade plexus-java 1.0.4
    * [MJAVADOC-638](https://issues.apache.org/jira/browse/MJAVADOC-638) - upgrade Doxia Sitetools to 1.9.2 to remove dependency on Struts

Enjoy,

-The Apache Maven team 
