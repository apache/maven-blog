---
layout: post
title: "Apache Maven 3.6.3 Released"
date: '2019-11-26T21:23:36+00:00'
permalink: apache-maven-3-6-3
categories:
  - Maven-Core-Releases
---
The Apache Maven team is pleased to announce the release of the Apache
Maven 3.6.3.

Apache Maven is a software project management and comprehension tool. Based
on the concept of a project object model (POM), Maven can manage a
project's build, reporting and documentation from a central piece of
information.

You can find out more about Apache Maven at https://maven.apache.org

You can download the appropriate sources etc. from
the [download page](https://maven.apache.org/download.cgi)

<!-- more -->

## Overview about the changes

- This is a regression release to fix some critical issues shipped with 3.6.2.
- Some license issues on binary distribution have been fixed.
- This Maven distribution is now Reproducible: if you build from source archive, with JDK 8,
  on Windows, with `mvn -DbuildNumber=cecedd343002696d0abb50b32b541b8a6ba2883f package` you’ll
  get bit-by-bit identical output that you can check with sha512 fingerprints.
  If you’re building on any Unix system, you’ll need to add `-Dline.separator=$'\r\n'`.
  See the https://maven.apache.org/guides/mini/guide-reproducible-builds.html for more details.

For more information read https://maven.apache.org/docs/3.6.3/release-notes.html


## Complete Release Notes

* Sub-tasks:

    * [MNG-6779](https://issues.apache.org/jira/browse/MNG-6779) - fix jcl-over-slf4j license: Apache 2.0 instead of MIT

* Bugs

    * [MNG-6584](https://issues.apache.org/jira/browse/MNG-6584) - Maven version 3.6.0 does not show ReasonPhrase anymore
    * [MNG-6759](https://issues.apache.org/jira/browse/MNG-6759) - [REGRESSION] Maven fails to use `<repositories>` section from dependency when resolving transitive dependencies in some cases
    * [MNG-6760](https://issues.apache.org/jira/browse/MNG-6760) - [REGRESSION] ExclusionArtifactFilter result invalid when wildcard exclusion is followed by other exclusions
    * [MNG-6765](https://issues.apache.org/jira/browse/MNG-6765) - [Regression] tycho pom-less builds fails with 3.6.2
    * [MNG-6771](https://issues.apache.org/jira/browse/MNG-6771) - Fix license issues on binary distribution

* Improvements:

    * [MNG-6778](https://issues.apache.org/jira/browse/MNG-6778) - Use https for schemaLocations
    * [MNG-6799](https://issues.apache.org/jira/browse/MNG-6799) - avoid model interpolation instability risk: ensure StringVisitorModelInterpolator replaces StringSearchModelInterpolator

* Tasks:

    * [MNG-6777](https://issues.apache.org/jira/browse/MNG-6777) - Remove duplicate resolveFile methods
    * [MNG-6789](https://issues.apache.org/jira/browse/MNG-6789) - Make Maven distribution build Reproducible


See [complete release notes for all versions][5]

- The Apache Maven Team.


[0]: ../../download.html
[1]: ../../plugins/index.html
[2]: https://maven.apache.org/
[4]: https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12316922&version=12346152
[5]: ../../docs/history.html
