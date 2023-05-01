---
layout: post
title: "Apache Maven EAR Plugin Version 3.0.0 Released"
date: '2018-03-12T21:14:03+00:00'
permalink: apache-maven-ear-plugin-3-0-0
categories:
  - Maven-Ear-Plugin
  - Maven-Plugin-Releases
---
The Apache Maven team is pleased to announce the release of the
[Apache Maven EAR Plugin, version 3.0.0](httpa://maven.apache.org/plugins/maven-ear-plugin/)

This plugin generates Java EE Enterprise Archive (EAR) file. It can also
generate the deployment descriptor file (e.g. application.xml).

You should specify the version in your project's plugin configuration:

```xml
<plugin>
  <groupId>org.apache.maven.plugins</groupId>
  <artifactId>maven-ear-plugin</artifactId>
  <version>3.0.0</version>
</plugin>
```

You can download the appropriate [sources etc. from the download page](https://maven.apache.org/plugins/maven-ear-plugin/download.cgi).


<!-- more -->

[Release Notes - Maven EAR Plugin - Version 3.0.0](https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317422&amp;version=12330696)

Bugs:

* [MEAR-171](https://issues.apache.org/jira/browse/MEAR-171) - Full customization of FileNameMapping is needed
* [MEAR-217](https://issues.apache.org/jira/browse/MEAR-217) - Snapshot dependencies are not deleted from skinny WARs
* [MEAR-243](https://issues.apache.org/jira/browse/MEAR-243) - Skinny WARs - JAR not removed from WAR if scope in EAR is set to provided
* [MEAR-244](https://issues.apache.org/jira/browse/MEAR-244) - Remove link to non-existing Codehaus wiki
* [MEAR-246](https://issues.apache.org/jira/browse/MEAR-246) - Upgrade the EAR lifecycle to use the maven-resources-plugin 3.0.2.
* [MEAR-250](https://issues.apache.org/jira/browse/MEAR-250) - IT skinny-wars-javaee5 fails while running with JDK 9

New Features:

* [MEAR-247](https://issues.apache.org/jira/browse/MEAR-247) - resource-ref in generated application.xml
* [MEAR-248](https://issues.apache.org/jira/browse/MEAR-248) - Support lookup-name in env-entry section

Improvements:

* [MEAR-198](https://issues.apache.org/jira/browse/MEAR-198) - Add LifecycleMapping and ArtifactHandler from maven-core to target packaging plugin
* [MEAR-223](https://issues.apache.org/jira/browse/MEAR-223) - Link to wiki on documentation page is pointing to shutdown codehaus
* [MEAR-226](https://issues.apache.org/jira/browse/MEAR-226) - bundleFileName functionality for the acr plugin
* [MEAR-228](https://issues.apache.org/jira/browse/MEAR-228) - Remove manifestFile parameter
* [MEAR-229](https://issues.apache.org/jira/browse/MEAR-229) - Change default value for version parameter
* [MEAR-232](https://issues.apache.org/jira/browse/MEAR-232) - Remove param properties that doesn't make sense for CLI usage
* [MEAR-234](https://issues.apache.org/jira/browse/MEAR-234) - Upgrade maven-shared-components parent to version 30
* [MEAR-241](https://issues.apache.org/jira/browse/MEAR-241) - Change package to o.a.m.plugins
* [MEAR-242](https://issues.apache.org/jira/browse/MEAR-242) - Update lifecycle mapping plugin version
* [MEAR-254](https://issues.apache.org/jira/browse/MEAR-254) - Support JavaEE version 8
* [MEAR-258](https://issues.apache.org/jira/browse/MEAR-258) - Upgrade site skin to 1.7
* [MEAR-260](https://issues.apache.org/jira/browse/MEAR-260) - Remove finalName as a parameter
* [MEAR-261](https://issues.apache.org/jira/browse/MEAR-261) - In cases where fileNameMapping is used fail the build
* [MEAR-262](https://issues.apache.org/jira/browse/MEAR-262) - Missing since for outputFileNameMapping parameter
* [MEAR-263](https://issues.apache.org/jira/browse/MEAR-263) - Wrong docs in examples/customize-file-name-mapping.html

Tasks:

* [MEAR-207](https://issues.apache.org/jira/browse/MEAR-207) - Remove the JavaModule/Ejb3Module which are marked deprecated
* [MEAR-208](https://issues.apache.org/jira/browse/MEAR-208) - Upgrade to Maven 3.0 compatiblity + JDK 6
* [MEAR-209](https://issues.apache.org/jira/browse/MEAR-209) - Change and use a internal unique id instead of artifactId only
* [MEAR-259](https://issues.apache.org/jira/browse/MEAR-259) - Fix formatting date issues in apt files

Dependency upgrades:

* [MEAR-224](https://issues.apache.org/jira/browse/MEAR-224) - Upgrade plexus-archiver from 2.10.3 to 3.0.1
* [MEAR-233](https://issues.apache.org/jira/browse/MEAR-233) - Upgrade plexus-archiver from 3.0.3 to 3.1.1
* [MEAR-235](https://issues.apache.org/jira/browse/MEAR-235) - Upgrade maven-archiver to 3.1.0
* [MEAR-236](https://issues.apache.org/jira/browse/MEAR-236) - Upgrade maven-filtering to 3.1.1
* [MEAR-237](https://issues.apache.org/jira/browse/MEAR-237) - Upgrade plexus-archiver to 3.3
* [MEAR-238](https://issues.apache.org/jira/browse/MEAR-238) - Upgrade of plexus-archiver to 3.4.
* [MEAR-240](https://issues.apache.org/jira/browse/MEAR-240) - Upgrade of maven-archiver to 3.1.1.
* [MEAR-245](https://issues.apache.org/jira/browse/MEAR-245) - Upgrade of plexus-interpolation to 1.24.
* [MEAR-251](https://issues.apache.org/jira/browse/MEAR-251) - Upgrade maven-archiver to 3.2.0
* [MEAR-252](https://issues.apache.org/jira/browse/MEAR-252) - Upgrade plexus-archiver to 3.5.
* [MEAR-253](https://issues.apache.org/jira/browse/MEAR-253) - Upgrade plexus-utils to version 3.1.0
* [MEAR-255](https://issues.apache.org/jira/browse/MEAR-255) - Upgrade parent to 31
* [MEAR-256](https://issues.apache.org/jira/browse/MEAR-256) - Upgrade maven-verifier component
* [MEAR-257](https://issues.apache.org/jira/browse/MEAR-257) - Upgrade JUnit to 4.12

Enjoy,

-The Apache Maven team
