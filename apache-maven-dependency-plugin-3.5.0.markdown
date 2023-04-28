---
layout: post
title: "Apache Maven Dependency Plugin Version 3.5.0 Released"
date: '2023-01-11T21:58:58+00:00'
permalink: apache-maven-dependency-plugin-3-5-0
categories:
- Maven
- Maven-Plugin-Releases
---
The Apache Maven team is pleased to announce the release of the
[Apache Maven Dependency Plugin, version 3.5.0](https://maven.apache.org/plugins/maven-dependency-plugin/).

The dependency plugin provides the capability to manipulate artifacts. It
can copy and/or unpack artifacts from local or remote repositories to a
specified location.

https://maven.apache.org/plugins/maven-dependency-plugin/

You should specify the version in your project's plugin configuration:

```xml
<plugin>
    <groupId>org.apache.maven.plugins</groupId>
    <artifactId>maven-dependency-plugin</artifactId>
    <version>3.5.0</version>
</plugin>
``` 

You can download the appropriate sources etc. from the download page:

https://maven.apache.org/plugins/maven-dependency-plugin/download.cgi


[Release Notes - Maven Dependency Plugin - Version 3.5.0](https://issues.apache.org/jira/secure/ReleaseNote.jspa?version=12340588&styleName=Text&projectId=12317227)

* Improvement

    * [MDEP-831](https://issues.apache.org/jira/browse/MDEP-831) - Remove not used dependencies / Replace parts

* Task
    * [MDEP-841](https://issues.apache.org/jira/browse/MDEP-841) - Explicitly start and end tables with Doxia Sinks in report renderers

* Dependency upgrade
    * [MDEP-837](https://issues.apache.org/jira/browse/MDEP-837) - Upgrade Parent to 38


Enjoy,

-The Apache Maven team
