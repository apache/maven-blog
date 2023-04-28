---
layout: post
title: "Apache Maven Clean Plugin Version 3.1.0 Released"
date: '2018-04-14T13:43:18+00:00'
permalink: apache-maven-clean-plugin-version
categories:
  - Maven
  - Maven-Plugin-Releases
---
The Apache Maven team is pleased to announce the release of the
[Apache Maven Clean Plugin, version 3.1.0](https://maven.apache.org/plugins/maven-clean-plugin/).

The Clean Plugin is used when you want to remove files generated at build-time
in a project's directory.

Important Note:

* Maven 3.X only
* JDK 7 minimum requirement

You should specify the version in your project's plugin configuration:

```xml
<plugin>
  <groupId>org.apache.maven.plugins</groupId>
  <artifactId>maven-clean-plugin</artifactId>
  <version>3.1.0</version>
</plugin>
```

<!-- more -->

[Release Notes - Maven Clean Plugin - Version 3.1.0](https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317224&version=12337984)

Bug:

* [MCLEAN-77](https://issues.apache.org/jira/browse/MCLEAN-77) - Remove link to non-existing Codehaus wiki

Tasks:

* [MCLEAN-73](https://issues.apache.org/jira/browse/MCLEAN-73) - Upgrade of maven-shared-utils to 3.0.1.
* [MCLEAN-74](https://issues.apache.org/jira/browse/MCLEAN-74) - Upgrade of commons-io to 2.5.
* [MCLEAN-83](https://issues.apache.org/jira/browse/MCLEAN-83) - Upgrade mave-surefire/failsafe-plugin 2.21.0
* [MCLEAN-84](https://issues.apache.org/jira/browse/MCLEAN-84) - Lift JDK minimum to JDK 7

Dependency upgrades:

* [MCLEAN-75](https://issues.apache.org/jira/browse/MCLEAN-75) - Upgrade maven-plugins to version 30
* [MCLEAN-80](https://issues.apache.org/jira/browse/MCLEAN-80) - Upgrade maven-shared-utils to 3.2.0
* [MCLEAN-81](https://issues.apache.org/jira/browse/MCLEAN-81) - Upgrade parent to 31
* [MCLEAN-85](https://issues.apache.org/jira/browse/MCLEAN-85) - Upgrade maven-shared-utils to 3.2.1


Enjoy,

-The Apache Maven team
