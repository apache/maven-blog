---
layout: post
title: "Apache Maven Deploy Plugin Version 3.0.0-M1 Released"
date: '2018-10-01T19:30:55+00:00'
permalink: apache-maven-deploy-plugin-3-0-0-M1
categories:
- Maven
- Maven-Plugin-Releases
---
The Apache Maven team is pleased to announce the release of the
[Apache Maven Deploy Plugin, version 3.0.0-M1](https://maven.apache.org/plugins/maven-deploy-plugin/).

The Maven Deploy Plugin is primarily used during the deploy-phase, to add your
artifact(s) to a remote repository for sharing with other developers and
projects. This is usually done in an integration or release environment. It can
also be used to deploy a particular artifact (e.g. a third party jar like Sun's
non-redistributable reference implementations).

Important Note since 3.0.0-M1:

* Maven 3.X only
* Minimum JDK 7+
* The maven-deploy-plugin will generate the needed checksums
  during the transfer to your remote repository.

Usage Note:

* Use the maven-deploy-plugin version 3.0.0-M1 only in combintation
  with the maven-install-plugin version 3.0.0-M1.

```xml
<plugin>
  <groupId>org.apache.maven.plugins</groupId>
  <artifactId>maven-deploy-plugin</artifactId>
  <version>3.0.0-M1</version>
</plugin>
```

You can download the appropriate sources etc. from the [download page](https://maven.apache.org/plugins/maven-deploy-plugin/download.cgi).

<!-- more -->



[Release Notes - Maven Deploy Plugin Version 3.0.0-M1](https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317228&version=12330476).


Bugs:

* [MDEPLOY-194](https://issues.apache.org/jira/browse/MDEPLOY-194) - Deploy SSH external: copy and paste failure in POM snippet comment
* [MDEPLOY-211](https://issues.apache.org/jira/browse/MDEPLOY-211) - uniqueVersion broken (if not supported, should be removed from doc, and warning printed)
* [MDEPLOY-212](https://issues.apache.org/jira/browse/MDEPLOY-212) - deploy-file incorrectly deploys attached artifacts
* [MDEPLOY-213](https://issues.apache.org/jira/browse/MDEPLOY-213) - deploy-file replaces main artifact of a project
* [MDEPLOY-215](https://issues.apache.org/jira/browse/MDEPLOY-215) - Remove link to non-existing Codehaus wiki

New Feature:

* [MDEPLOY-178](https://issues.apache.org/jira/browse/MDEPLOY-178) - Use information provided in pom.xml of JAR

Improvements:

* [MDEPLOY-171](https://issues.apache.org/jira/browse/MDEPLOY-171) - Remove deprecated readonly parameters
* [MDEPLOY-187](https://issues.apache.org/jira/browse/MDEPLOY-187) - Upgrade to Maven 3.0 compatiblity
* [MDEPLOY-205](https://issues.apache.org/jira/browse/MDEPLOY-205) - MavenProject with only attachments must have packaging "pom"
* [MDEPLOY-207](https://issues.apache.org/jira/browse/MDEPLOY-207) - Remove @Deprecated marked code
* [MDEPLOY-222](https://issues.apache.org/jira/browse/MDEPLOY-222) - Issue Tracking in pom.xml points to outdated Codehaus site
* [MDEPLOY-231](https://issues.apache.org/jira/browse/MDEPLOY-231) - Move checksum generation from install to deploy plugin
* [MDEPLOY-232](https://issues.apache.org/jira/browse/MDEPLOY-232) - Using maven-fluido-skin 1.7
* [MDEPLOY-233](https://issues.apache.org/jira/browse/MDEPLOY-233) - Remove unused code
* [MDEPLOY-240](https://issues.apache.org/jira/browse/MDEPLOY-240) - Remove updateReleaseInfo parameter

Tasks:

* [MDEPLOY-203](https://issues.apache.org/jira/browse/MDEPLOY-203) - Rename package to org.apache.maven.plugins
* [MDEPLOY-239](https://issues.apache.org/jira/browse/MDEPLOY-239) - Add GitHub documentation
* [MDEPLOY-242](https://issues.apache.org/jira/browse/MDEPLOY-242) - Lift JDK minimum to JDK 7

Sub-task:

* [MDEPLOY-202](https://issues.apache.org/jira/browse/MDEPLOY-202) - deploy-file goal insists on deploying source file for previous deploy-file execution

Dependency upgrades:

* [MDEPLOY-188](https://issues.apache.org/jira/browse/MDEPLOY-188) - Upgrade plexus-utils to 3.0.18
* [MDEPLOY-191](https://issues.apache.org/jira/browse/MDEPLOY-191) - Upgrade to maven-plugins parent version 27
* [MDEPLOY-192](https://issues.apache.org/jira/browse/MDEPLOY-192) - Upgrade maven-plugin-testing-harness to 1.3
* [MDEPLOY-208](https://issues.apache.org/jira/browse/MDEPLOY-208) - Upgrade plexus-utils to 3.0.24
* [MDEPLOY-209](https://issues.apache.org/jira/browse/MDEPLOY-209) - Upgrade maven-shared-components parent to version 30
* [MDEPLOY-210](https://issues.apache.org/jira/browse/MDEPLOY-210) - Upgrade of commons-io to 2.5.
* [MDEPLOY-219](https://issues.apache.org/jira/browse/MDEPLOY-219) - Upgrade maven-artifact-transfer to version 0.9.1
* [MDEPLOY-228](https://issues.apache.org/jira/browse/MDEPLOY-228) - Upgrade plexus-utils 3.1.0
* [MDEPLOY-230](https://issues.apache.org/jira/browse/MDEPLOY-230) - Upgrade parent to 31
* [MDEPLOY-235](https://issues.apache.org/jira/browse/MDEPLOY-235) - Upgrade mave-surefire/failsafe-plugin 2.21.0
* [MDEPLOY-237](https://issues.apache.org/jira/browse/MDEPLOY-237) - Upgrade maven-plugins parent to version 32
* [MDEPLOY-238](https://issues.apache.org/jira/browse/MDEPLOY-238) - Upgrade JUnit 4.11 to 4.12

Enjoy,

-The Apache Maven team

Karl-Heinz Marbaise
