---
layout: post
title: "Apache Maven Parent POM Version 34 Released"
date: '2020-02-03T20:12:13+00:00'
permalink: apache-maven-parent-pom-34
categories:
  - Maven-Parent-POM
---
The Apache Maven team is pleased to announce the release of the
[Maven Parent POMs Version 34](https://maven.apache.org/pom/maven/)

Maven Parent POMs include [Maven Parent POM](https://maven.apache.org/pom/maven/)
itself, but also [Maven Plugins Parent POM](https://maven.apache.org/pom/maven/maven-plugins/),
[Maven Shared Components Parent POM](https://maven.apache.org/pom/maven/maven-shared-components/),
[Maven Skins Parent POM](https://maven.apache.org/pom/maven/maven-skins/) and
Maven Doxia Tools Parent POM.

https://maven.apache.org/pom/maven/

You should specify the version in your project as parent like the following:

```xml
<parent>
   <groupId>org.apache.maven</groupId>
   <artifactId>maven-parent</artifactId>
   <version>34</version>
</parent>
```

You can download the appropriate sources etc. from the download page:

https://maven.apache.org/pom/maven/download.html


[Release Notes - Apache Maven Parent POM - Version 34](https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12311250&version=12343766)

* Bugs:

    * [MPOM-221](https://issues.apache.org/jira/browse/MPOM-221) - All Links for Diff produce Forbidden
    * [MPOM-235](https://issues.apache.org/jira/browse/MPOM-235) - Google Custom Search broken

* New Feature:

    * [MPOM-223](https://issues.apache.org/jira/browse/MPOM-223) - Introduce parent for extensions

* Improvements:

    * [MPOM-216](https://issues.apache.org/jira/browse/MPOM-216) - Update java minimum version to 7
    * [MPOM-226](https://issues.apache.org/jira/browse/MPOM-226) - Ignore .asf.yaml for license check in apache-rat-plugin
    * [MPOM-230](https://issues.apache.org/jira/browse/MPOM-230) - Remove maven-report

* Task:

    * [MPOM-217](https://issues.apache.org/jira/browse/MPOM-217) - remove plexus javadoc taglet configuration

* Dependency upgrades:

    * [MPOM-212](https://issues.apache.org/jira/browse/MPOM-212) - upgrade plexus-component-metadata to 2.0.0 to get reproducible plexus/components.xml
    * [MPOM-234](https://issues.apache.org/jira/browse/MPOM-234) - Upgrade apache-rat-plugin to 0.13

Enjoy,
- The Apache Maven Team

