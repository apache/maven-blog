---
layout: post
title: "Apache Maven Checkstyle Plugin Version 3.2.0 Released"
date: '2022-08-23T19:31:31+00:00'
permalink: apache-maven-checkstyle-plugin-version2
categories:
  - Maven-Checkstyle-Plugin
  - Maven-Plugin-Releases
---
The Maven team is pleased to announce the release of the
[Apache Maven Checkstyle Plugin, version 3.2.0](https://maven.apache.org/plugins/maven-checkstyle-plugin/).

The Checkstyle Plugin generates a report regarding the code style used by the
developers. For more information about Checkstyle, see
https://checkstyle.sourceforge.net/.

You should specify the version in your project's plugin configuration:

```xml
<plugin>
  <groupId>org.apache.maven.plugins</groupId>
  <artifactId>maven-checkstyle-plugin</artifactId>
  <version>3.2.0</version>
</plugin>
``` 

You can download the appropriate [sources etc. from the download page](https://maven.apache.org/plugins/maven-checkstyle-plugin/download.cgi).

[Release Notes - Apache Maven Checkstyle Plugin - Version 3.2.0](https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317223&version=12345559)

* Task:

    * [MCHECKSTYLE-418](https://issues.apache.org/jira/browse/MCHECKSTYLE-418) - Deprecate RSS feature and disable by default

* Dependency upgrades:

    * [MCHECKSTYLE-393](https://issues.apache.org/jira/browse/MCHECKSTYLE-393) - upgrade Doxia Sitetools to 1.9.2 to remove dependency on Struts
    * [MCHECKSTYLE-399](https://issues.apache.org/jira/browse/MCHECKSTYLE-399) - Upgrade Checkstyle to 8.41.1
    * [MCHECKSTYLE-402](https://issues.apache.org/jira/browse/MCHECKSTYLE-402) - Require Maven 3.1.1 (drop dependency to Maven 3.0)
    * [MCHECKSTYLE-406](https://issues.apache.org/jira/browse/MCHECKSTYLE-406) - Make plugin compatible with Checkstyle 8.44 (Upgraded to 9.1)
    * [MCHECKSTYLE-410](https://issues.apache.org/jira/browse/MCHECKSTYLE-410) - Require Maven 3.2.5+
    * [MCHECKSTYLE-417](https://issues.apache.org/jira/browse/MCHECKSTYLE-417) - Upgrade Maven Reporting API to 3.1.1/Maven Reporting Impl to 3.2.0
    * [MCHECKSTYLE-419](https://issues.apache.org/jira/browse/MCHECKSTYLE-419) - Upgrade Parent to 37 and cleanup

Compatibility Notice:
* For technical reasons the parameter `encoding` has been replaced with
  `inputEncoding`. For details please see
    * [MCHECKSTYLE-417](https://issues.apache.org/jira/browse/MCHECKSTYLE-417).
    * [Git Commit](https://github.com/apache/maven-checkstyle-plugin/commit/627fa4f684866a579f2c105fcc1dbf3ed776daa8).

Enjoy,

-The Apache Maven team 
