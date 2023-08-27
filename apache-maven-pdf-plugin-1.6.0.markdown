---
layout: post
title: "Apache Maven PDF Plugin Version 1.6.0 Released"
date: '2022-04-21T23:48:56+00:00'
permalink: apache-maven-pdf-plugin-1-6-0
categories:
  - Maven-PDF-Plugin
  - Maven-Plugin-Releases
---
The Apache Maven team is pleased to announce the release of the
[Apache Maven PDF Plugin, version 1.6.0](https://maven.apache.org/plugins/maven-pdf-plugin/).

This plug-in allows you to generate a PDF version of your project's
documentation.

```xml
<plugin>
  <groupId>org.apache.maven.plugins</groupId>
  <artifactId>maven-pdf-plugin</artifactId>
  <version>1.6.0</version>
</plugin>
```

[Release Notes - Maven PDF Plugin - Version 1.6.0](https://issues.apache.org/jira/secure/ReleaseNote.jspa?version=12351601&styleName=Text&projectId=12317620)

* Task:

    * [MPDF-100](https://issues.apache.org/jira/browse/MPDF-100) - Remove remains of org.codehaus.doxia.sink.Sink

* Dependency upgrades:

    * [MPDF-101](https://issues.apache.org/jira/browse/MPDF-101) - Upgrade Maven to 3.2.5
    * [MPDF-102](https://issues.apache.org/jira/browse/MPDF-102) - Upgrade Maven Plugin Plugin to 3.6.4
    * [MPDF-103](https://issues.apache.org/jira/browse/MPDF-103) - Upgrade plugins in ITs

Enjoy,

-The Apache Maven team
