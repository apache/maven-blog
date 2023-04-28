---
layout: post
title: "Apache Maven Deploy Plugin - Release 2.8"
date: '2018-10-01T19:30:55+00:00'
permalink: apache-maven-deploy-plugin-2-8-0
categories:
  - Maven
  - Maven-Plugin-Releases
---
The new release of the [Apache Maven Deploy Plugin 2.8](https://maven.apache.org/plugins/maven-deploy-plugin/) is available.

The new release of the Maven Deploy Plugin contains two bug fixes, an improvement and an very important
new feature [MDEPLOY-157](https://issues.apache.org/jira/browse/MDEPLOY-157). This will address the problem of deploying artifacts within a multi-module build
where not all artifacts have successfully installed.

Bug

* [MDEPLOY-68](https://issues.apache.org/jira/browse/MDEPLOY-68) - altDeploymentRepository allows dangerous deploy processes
* [MDEPLOY-145](https://issues.apache.org/jira/browse/MDEPLOY-145) - Documentation does not list layouts

Improvement

* [MDEPLOY-154](https://issues.apache.org/jira/browse/MDEPLOY-154) - Rewrite page 'deploy with classifier'

New Feature

* [MDEPLOY-157](https://issues.apache.org/jira/browse/MDEPLOY-157) - Add deployAtEnd option for multimodule projects

Task

* [MDEPLOY-151](https://issues.apache.org/jira/browse/MDEPLOY-151) - use maven-plugin-tools' java 5 annotations

