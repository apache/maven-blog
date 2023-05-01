---
layout: post
title: "Apache Maven Install Plugin Version 3.0.0-M1 Released"
date: '2018-10-01T09:28:00+00:00'
permalink: apache-maven-install-plugin-3-0-0-M1
categories:
  - Maven-Install-Plugin
  - Maven-Plugin-Releases
---
The Apache Maven team is pleased to announce the release of the
[Apache Maven Install Plugin, version 3.0.0-M1](https://maven.apache.org/plugins/maven-install-plugin/).

The Maven-Install-Plugin is used during the install phase to add artifact(s) to the
local repository. The Install-Plugin uses the information in the POM (groupId,
artifactId, version) to determine the proper location for the artifact within
the local repository.

Important Note since 3.0.0-M1:

* Maven 3.X only
* Minimum JDK 7+
* The maven-install-plugin does not generate any kind of checksum
  anymore.

Usage Note:

* Use the maven-install-plugin 3.0.0-M1 only in combination
  with the maven-deploy-plugin 3.0.0-M1.

```xml
<plugin>
  <groupId>org.apache.maven.plugins</groupId>
  <artifactId>maven-install-plugin</artifactId>
  <version>3.0.0-M1</version>
</plugin>
```
You can download the appropriate sources etc. from the [download page](https://maven.apache.org/plugins/maven-install-plugin/download.cgi).

<!-- more -->

[Release Notes - Maven Install Plugin Version 3.0.0-M1](https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317524&version=12334343)

Bugs:

* [MINSTALL-121](https://issues.apache.org/jira/browse/MINSTALL-121) - The packaging property should not be used for the file extension
* [MINSTALL-130](https://issues.apache.org/jira/browse/MINSTALL-130) - Remove link to non-existing Codehaus wiki

Improvements:

* [MINSTALL-110](https://issues.apache.org/jira/browse/MINSTALL-110) - install-file should also install bundled pom.xml from artifact.
* [MINSTALL-114](https://issues.apache.org/jira/browse/MINSTALL-114) - Plugin shouldn't depend on maven-compat dependency
* [MINSTALL-118](https://issues.apache.org/jira/browse/MINSTALL-118) - MavenProject with only attachments must have packaging "pom"
* [MINSTALL-124](https://issues.apache.org/jira/browse/MINSTALL-124) - Remove hard code version for maven-invoker-plugin
* [MINSTALL-128](https://issues.apache.org/jira/browse/MINSTALL-128) - Replace usage of the deprecated ArtifactFactory
* [MINSTALL-134](https://issues.apache.org/jira/browse/MINSTALL-134) - Remove checksum generation
* [MINSTALL-136](https://issues.apache.org/jira/browse/MINSTALL-136) - Removed unused dependency
* [MINSTALL-143](https://issues.apache.org/jira/browse/MINSTALL-143) - Move checksum generation from install to deploy plugin

Tasks:

* [MINSTALL-129](https://issues.apache.org/jira/browse/MINSTALL-129) - Use released version of maven-artifact-transfer
* [MINSTALL-131](https://issues.apache.org/jira/browse/MINSTALL-131) - Rename package to org.apache.maven.plugins
* [MINSTALL-145](https://issues.apache.org/jira/browse/MINSTALL-145) - Remove unused dependencies in pom
* [MINSTALL-148](https://issues.apache.org/jira/browse/MINSTALL-148) - Document change about createChecksums
* [MINSTALL-149](https://issues.apache.org/jira/browse/MINSTALL-149) - Remove updateReleaseInfo parameter
* [MINSTALL-150](https://issues.apache.org/jira/browse/MINSTALL-150) - Lift JDK minimum to JDK 7

Dependency upgrades:

* [MINSTALL-109](https://issues.apache.org/jira/browse/MINSTALL-109) - Update version of plexus-utils to 3.0.18
* [MINSTALL-111](https://issues.apache.org/jira/browse/MINSTALL-111) - Upgrade to maven-plugins parent version 27
* [MINSTALL-112](https://issues.apache.org/jira/browse/MINSTALL-112) - Upgrade maven-plugin-testing-harness to 1.3
* [MINSTALL-113](https://issues.apache.org/jira/browse/MINSTALL-113) - Upgrade maven-shared-utils to 0.7
* [MINSTALL-117](https://issues.apache.org/jira/browse/MINSTALL-117) - Upgrade maven-shared-utils to 3.0.0
* [MINSTALL-122](https://issues.apache.org/jira/browse/MINSTALL-122) - Upgrade maven-shared-components parent to version 30
* [MINSTALL-123](https://issues.apache.org/jira/browse/MINSTALL-123) - Upgrade maven-shared-utils to 3.0.1
* [MINSTALL-125](https://issues.apache.org/jira/browse/MINSTALL-125) - Upgrade of commons-io to 2.5.
* [MINSTALL-127](https://issues.apache.org/jira/browse/MINSTALL-127) - Upgrade maven-shared-utils to 3.1.0
* [MINSTALL-137](https://issues.apache.org/jira/browse/MINSTALL-137) - Upgrade maven-artifact-transfer to version 0.9.1
* [MINSTALL-140](https://issues.apache.org/jira/browse/MINSTALL-140) - maven-shared-utils 3.1.0 to 3.2.0
* [MINSTALL-141](https://issues.apache.org/jira/browse/MINSTALL-141) - plexus-utils 3.0.24 to 3.1.0
* [MINSTALL-142](https://issues.apache.org/jira/browse/MINSTALL-142) - Upgrade parent to 31
* [MINSTALL-144](https://issues.apache.org/jira/browse/MINSTALL-144) - Upgrade mave-surefire/failsafe-plugin 2.21.0
* [MINSTALL-146](https://issues.apache.org/jira/browse/MINSTALL-146) - Upgrade maven-plugin parent to version 32
* [MINSTALL-147](https://issues.apache.org/jira/browse/MINSTALL-147) - Upgrade JUnit to 4.12

Enjoy,

-The Apache Maven team

Karl-Heinz Marbaise
