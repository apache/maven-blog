---
layout: post
title: "Apache Maven Install Plugin Version 3.0.0 Released"
date: '2022-07-19T14:14:14+00:00'
permalink: apache-maven-install-plugin-3-0-0
categories:
  - Maven-Install-Plugin
  - Maven-Plugin-Releases
---
The Apache Maven team is pleased to announce the release of the
[Apache Maven Install Plugin, version 3.0.0](https://maven.apache.org/plugins/maven-install-plugin/).

The maven-install-plugin is used during the install phase to add artifact(s) to the
local repository. The install plugin uses the information in the POM (groupId,
artifactId, version) to determine the proper location for the artifact within
¡the local repository.

NOTE:
* Plugin requires Java runtime 7+
* Plugin requires Maven 3.2.5+

```xml
<plugin>
  <groupId>org.apache.maven.plugins</groupId>
  <artifactId>maven-install-plugin</artifactId>
  <version>3.0.0</version>
</plugin>
```
You can download the appropriate sources etc. from the [download page](https://maven.apache.org/plugins/maven-install-plugin/download.cgi).

[Release Notes - Maven Install Plugin Version 3.0.0](https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317524&version=12344165)

* Bug:

  * [MINSTALL-115](https://issues.apache.org/jira/browse/MINSTALL-115) - Setting installAtEnd causes no installs to occur when a multimodule project has multiple class realms
  * [MINSTALL-154](https://issues.apache.org/jira/browse/MINSTALL-154) - Remove link on index page to checksum example page

* Tasks:
  * [MINSTALL-153](https://issues.apache.org/jira/browse/MINSTALL-153) - Remove the updateReleaseInfo parameter's leftovers
  * [MINSTALL-171](https://issues.apache.org/jira/browse/MINSTALL-171) - Update plugin (requires Maven 3.2.5+)
  * [MINSTALL-177](https://issues.apache.org/jira/browse/MINSTALL-177) - Cleanup the plugin

* Dependency upgrades:

  * [MINSTALL-155](https://issues.apache.org/jira/browse/MINSTALL-155) - Upgrade maven-artifact-transfer 0.10.1
  * [MINSTALL-158](https://issues.apache.org/jira/browse/MINSTALL-158) - Upgrade maven-artifact-transfer to 0.11.0
  * [MINSTALL-166](https://issues.apache.org/jira/browse/MINSTALL-166) - Upgrade maven-artifact-transfer 0.13.1
  * [MINSTALL-167](https://issues.apache.org/jira/browse/MINSTALL-167) - Upgrade parent to version 34
  * [MINSTALL-172](https://issues.apache.org/jira/browse/MINSTALL-172) - Upgrade maven-plugin parent to 35
  * [MINSTALL-174](https://issues.apache.org/jira/browse/MINSTALL-174) - Upgrade maven-plugin parent to 36

Enjoy,

-The Apache Maven team

Karl-Heinz Marbaise
