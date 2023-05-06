---
layout: post
title: "Apache Maven Parent POM Version 32 Released"
date: '2018-07-20T10:00:00+00:00'
permalink: apache-maven-parent-pom-32
categories:
  - Maven-Parent-POM
---
The Apache Maven team is pleased to announce the release of the
[Maven Parent POMs Version 32](https://maven.apache.org/pom/maven/)

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
   <version>32</version>
</parent>
```

You can download the appropriate sources etc. from the download page:

https://maven.apache.org/pom/maven/download.html


<!-- more -->

[Release Notes - Maven POMs - Version MAVEN-32](https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12311250&version=12342723)

Improvements:

* [MPOM-187](https://issues.apache.org/jira/browse/MPOM-187) - Add autoVersionSubmodules=true to maven-release-plugin configuration
* [MPOM-189](https://issues.apache.org/jira/browse/MPOM-189) - Ensure that Jenkins will fail when maven-invoker-plugin has failures
* [MPOM-190](https://issues.apache.org/jira/browse/MPOM-190) - Change to https instead of http

Task:

* [MPOM-183](https://issues.apache.org/jira/browse/MPOM-183) - remove maven-archetype-bundles

Dependency upgrades:

* [MPOM-184](https://issues.apache.org/jira/browse/MPOM-184) - Upgrade maven-surefire/failsafe to 2.21.0 based on JDK 10 issues
* [MPOM-188](https://issues.apache.org/jira/browse/MPOM-188) - maven-invoker-plugin should copy value of https.protocols system property during invocation
* [MPOM-193](https://issues.apache.org/jira/browse/MPOM-193) - Upgrade extra-enforcer-rule to 1.0-beta-9

Changes since version 31:

https://gitbox.apache.org/repos/asf?p=maven-parent.git;a=blobdiff;f=pom.xml;hb=maven-parent-32;hpb=maven-parent-31


Enjoy,
- The Apache Maven Team


