---
layout: post
title: "Apache Maven Parent POM Version 35 Released"
date: '2022-03-03T15:20:22+00:00'
permalink: apache-maven-parent-pom-35
categories:
  - Maven-Parent-POM
---
The Apache Maven team is pleased to announce the release of the
[Maven Parent POMs Version 34](https://maven.apache.org/pom/maven/)

Maven Parent POMs include [Maven Parent POM](https://maven.apache.org/pom/maven/)
itself, but also [Maven Plugins Parent POM](https://maven.apache.org/pom/maven/maven-plugins/),
[Maven Shared Components Parent POM](https://maven.apache.org/pom/maven/maven-shared-components/),
[Maven Skins Parent POM](https://maven.apache.org/pom/maven/maven-skins/) and
Maven Doxia Tools Parent POM.

https://maven.apache.org/pom/maven/

You should specify the version in your project as parent like the following:

```xml
<parent>
   <groupId>org.apache.maven</groupId>
   <artifactId>maven-parent</artifactId>
   <version>35</version>
</parent>
```

You can download the appropriate sources etc. from the download page:

https://maven.apache.org/pom/maven/download.html


<!-- more -->

[Release Notes - Apache Maven Parent POM - Version 34](https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12311250&version=12346694&stylename=Text)


* Bugs:

    * [MPOM-242](https://issues.apache.org/jira/browse/MPOM-242) - fix mono-module site easy-deployment
    * [MPOM-243](https://issues.apache.org/jira/browse/MPOM-243) - WARNING: release:perform issues [WARNING] The requested profile "pom.xml" could not be activated because it does not exist.
    * [MPOM-253](https://issues.apache.org/jira/browse/MPOM-253) - issue management URL incorrect

* New Feature:

    * [MPOM-274](https://issues.apache.org/jira/browse/MPOM-274) - use Shared GitHub Actions

* Improvements:

    * [MPOM-268](https://issues.apache.org/jira/browse/MPOM-268) - Removed unused property
    * [MPOM-276](https://issues.apache.org/jira/browse/MPOM-276) - streamLogsOnFailures for maven-invoker-plugin as default
    * [MPOM-278](https://issues.apache.org/jira/browse/MPOM-278) - add "Extensions" entry to "Maven Projects" menu
    * [MPOM-279](https://issues.apache.org/jira/browse/MPOM-279) - Get rid of findbugs-maven-plugin
    * [MPOM-280](https://issues.apache.org/jira/browse/MPOM-280) - Remove detectLinks from maven-javadoc-plugin
    * [MPOM-298](https://issues.apache.org/jira/browse/MPOM-298) - Cleanup dependencyLocationsEnabled from MPIR configuration

* Tasks:

    * [MPOM-270](https://issues.apache.org/jira/browse/MPOM-270) - Fix enforcer use
    * [MPOM-271](https://issues.apache.org/jira/browse/MPOM-271) - Create helper profile to "ban legacy"
    * [MPOM-272](https://issues.apache.org/jira/browse/MPOM-272) - Remove legacy from doxia parent depMgmg
    * [MPOM-273](https://issues.apache.org/jira/browse/MPOM-273) - Update maven-plugin-plugin to 3.6.2
    * [MPOM-281](https://issues.apache.org/jira/browse/MPOM-281) - Update maven-plugin-plugin to 3.6.4

* Dependency upgrades:

    * [MPOM-239](https://issues.apache.org/jira/browse/MPOM-239) - upgrade plexus-component-metadata to 2.1.0 for better Reproducible Build
    * [MPOM-250](https://issues.apache.org/jira/browse/MPOM-250) - remove the JavaDoc taglets from maven-parent (both to extract Mojo javadoc annotations and link in javadoc)
    * [MPOM-292](https://issues.apache.org/jira/browse/MPOM-292) - upgrade parent to ASF 25


Enjoy,
- The Apache Maven Team

