---
layout: post
title: "Apache Maven EAR Plugin Version 3.3.0 Released"
date: '2022-10-22T09:28:28+00:00'
permalink: apache-maven-ear-plugin-3-3-0
categories:
  - Maven-Ear-Plugin
  - Maven-Plugin-Releases
---
The Apache Maven team is pleased to announce the release of the
[Apache Maven EAR Plugin, version 3.3.0](https://maven.apache.org/plugins/maven-ear-plugin/)

This plugin generates Java EE Enterprise Archive (EAR) file. It can also
generate the deployment descriptor file (e.g. application.xml).

You should specify the version in your project's plugin configuration:

NOTE:
* Requires JDK8 as minimum
* Requires Maven 3.2.5+ as minimum.

```xml
<plugin>
  <groupId>org.apache.maven.plugins</groupId>
  <artifactId>maven-ear-plugin</artifactId>
  <version>3.3.0</version>
</plugin>
```

You can download the appropriate [sources etc. from the download page](https://maven.apache.org/plugins/maven-ear-plugin/download.cgi).


[Release Notes - Maven EAR Plugin - Version 3.3.0](https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317422&version=12349537)

* Bugs:

    * [MEAR-297](https://issues.apache.org/jira/browse/MEAR-297) - failure when building javadoc: maven-plugin-tools-javadoc:jar:3.6.0 is missing
    * [MEAR-301](https://issues.apache.org/jira/browse/MEAR-301) - wrong repackaging when defaultLibBundleDir start with dot

* New Features:

    * [MEAR-302](https://issues.apache.org/jira/browse/MEAR-302) - jakarta EE 9 EAR compatibility
    * [MEAR-309](https://issues.apache.org/jira/browse/MEAR-309) - Support JakartaEE 10

* Improvements:

    * [MEAR-298](https://issues.apache.org/jira/browse/MEAR-298) - Improving EAR packaging performance with ZipFileSystem
    * [MEAR-319](https://issues.apache.org/jira/browse/MEAR-319) - Remove generated MANIFEST from outdated resources
    * [MEAR-321](https://issues.apache.org/jira/browse/MEAR-321) - Remove not implemented parameter - useBaseVersion

* Tasks:

    * [MEAR-304](https://issues.apache.org/jira/browse/MEAR-304) - Update dependencies used in IT tests
    * [MEAR-311](https://issues.apache.org/jira/browse/MEAR-311) - Require Java 8
    * [MEAR-318](https://issues.apache.org/jira/browse/MEAR-318) - Require Maven 3.2.5

* Dependency upgrades:

    * [MEAR-310](https://issues.apache.org/jira/browse/MEAR-310) - Upgrade Parent to 37
    * [MEAR-312](https://issues.apache.org/jira/browse/MEAR-312) - Upgrade Maven Verifier to 2.0.0-M1
    * [MEAR-313](https://issues.apache.org/jira/browse/MEAR-313) - Bump maven-filtering from 3.2.0 to 3.3.0
    * [MEAR-314](https://issues.apache.org/jira/browse/MEAR-314) - Bump plexus-archiver from 4.2.4 to 4.5.0
    * [MEAR-315](https://issues.apache.org/jira/browse/MEAR-315) - Bump maven-archiver from 3.5.1 to 3.6.0
    * [MEAR-316](https://issues.apache.org/jira/browse/MEAR-316) - Bump plexus-io from 3.2.0 to 3.4.0
    * [MEAR-317](https://issues.apache.org/jira/browse/MEAR-317) - Bump maven-shared-utils from 3.3.3 to 3.3.4
    * [MEAR-320](https://issues.apache.org/jira/browse/MEAR-320) - Bump plexus-utils from 3.3.0 to 3.4.2

Enjoy,

-The Apache Maven team
