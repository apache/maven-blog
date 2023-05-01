---
layout: post
title: "Apache Maven Deploy Plugin Version 3.0.0 Released"
date: '2022-07-19T14:14:14+00:00'
permalink: apache-maven-deploy-plugin-3-0-0-M1
categories:
  - Maven-Deploy-Plugin
  - Maven-Plugin-Releases
---
The Apache Maven team is pleased to announce the release of the
[Apache Maven Deploy Plugin, version 3.0.0](https://maven.apache.org/plugins/maven-deploy-plugin/).

The maven-deploy-plugin is primarily used during the `deploy` phase, to add your
artifact(s) to a remote repository for sharing with other developers and
projects. This is usually done in an integration or release environment.

Important Note since 3.0.0:

* Maven 3.2.5+ only
* Minimum JDK 7

```xml
<plugin>
  <groupId>org.apache.maven.plugins</groupId>
  <artifactId>maven-deploy-plugin</artifactId>
  <version>3.0.0</version>
</plugin>
```

You can download the appropriate sources etc. from the [download page](https://maven.apache.org/plugins/maven-deploy-plugin/download.cgi).


[Release Notes - Maven Deploy Plugin Version 3.0.0](https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317228&version=12351654).


* Bug:

  * [MDEPLOY-193](https://issues.apache.org/jira/browse/MDEPLOY-193) - deployAtEnd does not deploy artifacts for multi-module project with build extensions

* Task:

  * [MDEPLOY-291](https://issues.apache.org/jira/browse/MDEPLOY-291) - Update POM parent and Maven
  * [MDEPLOY-296](https://issues.apache.org/jira/browse/MDEPLOY-296) - Cleanup the plugin


Enjoy,

-The Apache Maven team
