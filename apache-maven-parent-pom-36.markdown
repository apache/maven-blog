---
layout: post
title: "Apache Maven Parent POM Version 36 Released"
date: '2022-04-22T10:32:33+00:00'
permalink: apache-maven-parent-pom-36
categories:
  - Maven-Parent-POM
---
The Apache Maven team is pleased to announce the release of the
[Maven Parent POMs Version 36](https://maven.apache.org/pom/maven/)

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
   <version>36</version>
</parent>
```

You can download the appropriate sources etc. from the download page:

https://maven.apache.org/pom/maven/download.html


<!-- more -->

[Release Notes - Apache Maven Parent POM - Version 36](https://issues.apache.org/jira/secure/ReleaseNote.jspa?version=12351408&styleName=Text&projectId=12311250)


* Improvements:

    * [MPOM-300](https://issues.apache.org/jira/browse/MPOM-300) - Replace Google Analytics with ASF Matomo
    * [MPOM-313](https://issues.apache.org/jira/browse/MPOM-313) - Execute checkstyle in early phase of the build

* Dependency upgrades:

    * [MPOM-308](https://issues.apache.org/jira/browse/MPOM-308) - Upgrade Maven PMD Plugin from 3.15.0 to 3.16.0
    * [MPOM-309](https://issues.apache.org/jira/browse/MPOM-309) - Upgrade TagList Maven Plugin from 2.4 to 3.0.0
    * [MPOM-311](https://issues.apache.org/jira/browse/MPOM-311) - Upgrade Maven JXR Plugin from 3.1.1 to 3.2.0
    * [MPOM-314](https://issues.apache.org/jira/browse/MPOM-314) - Upgrade modello-maven-plugin from 1.11 to 2.0.0
    * [MPOM-316](https://issues.apache.org/jira/browse/MPOM-316) - Upgrade ASF Parent to 26


Enjoy,
- The Apache Maven Team

