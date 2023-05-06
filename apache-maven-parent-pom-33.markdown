---
layout: post
title: "Apache Maven Parent POM Version 33 Released"
date: '2018-09-22T10:54:27+00:00'
permalink: apache-maven-parent-pom-33
categories:
  - Maven-Parent-POM
---
The Apache Maven team is pleased to announce the release of the
[Maven Parent POMs Version 33](https://maven.apache.org/pom/maven/)

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
   <version>33</version>
</parent>
```

You can download the appropriate sources etc. from the download page:

https://maven.apache.org/pom/maven/download.html


[Release Notes - Apache Maven Parent POM - Version 33](https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12311250&version=12343766)

Bug:

* [MPOM-202](https://issues.apache.org/jira/browse/MPOM-202) - Links to nabble archive only work with http

Improvement:

* [MPOM-203](https://issues.apache.org/jira/browse/MPOM-203) - Links to mailing list will not open mail

Wish:

* [MPOM-197](https://issues.apache.org/jira/browse/MPOM-197) - Remove deprecated plexus-maven-plugin from pluginManagement

Tasks:

* [MPOM-199](https://issues.apache.org/jira/browse/MPOM-199) - remove Archetypes parent POM from menu
* [MPOM-201](https://issues.apache.org/jira/browse/MPOM-201) - configure m2e lifecyle-mapping to ignore rat:check
* [MPOM-206](https://issues.apache.org/jira/browse/MPOM-206) - use sha512 instead of sha1 for source release distribution

Dependency upgrade:

* [MPOM-198](https://issues.apache.org/jira/browse/MPOM-198) - Update plexus-utils to 3.1.0 for Doxia Tools

Enjoy,
- The Apache Maven Team

