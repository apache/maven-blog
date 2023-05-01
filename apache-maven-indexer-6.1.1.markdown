---
layout: post
title: "Apache Maven Indexer Version 6.1.1 Released"
date: '2022-02-17T13:34:18+00:00'
permalink: apache-maven-indexer-6-1-1
categories:
  - Maven-Indexer
---
The Apache Maven team is pleased to announce the release of the
[Apache Maven Indexer, version 6.1.1](https://maven.apache.org/maven-indexer/).

Apache Maven Indexer (former Sonatype Nexus Indexer) is the de facto standard for producing indexes
of Maven repositories. The Indexes are produced and consumed by all major tools in the ecosystem.

Most notable changes:

* Java 8 required
* Lucene upgraded to latest 8.x (8.11.1)
* Guava and TrueZip dependencies removed

You can download the appropriate sources etc. from the download page:

https://maven.apache.org/maven-indexer/download.cgi


<!-- more -->

[Release Notes - Maven Indexer - Version 6.1.1](https://issues.apache.org/jira/secure/ReleaseNote.jspa?version=12351333&styleName=Text&projectId=12317523)

* Bugs:

    * [MINDEXER-123](https://issues.apache.org/jira/browse/MINDEXER-123) - Fix an InputStream leak in indexer-reader Utils
    * [MINDEXER-127](https://issues.apache.org/jira/browse/MINDEXER-127) - Maven repository indexing error: java.nio.channels.OverlappingFileLockException
    * [MINDEXER-133](https://issues.apache.org/jira/browse/MINDEXER-133) - Reset the correct stream in IndexDataReader
    * [MINDEXER-135](https://issues.apache.org/jira/browse/MINDEXER-135) - Fix CLI shading
    * [MINDEXER-138](https://issues.apache.org/jira/browse/MINDEXER-138) - Indexer Core Jetty test dependency is not in test scope

* Improvements:

    * [MINDEXER-104](https://issues.apache.org/jira/browse/MINDEXER-104) - Migrate the indexer to Lucene 8.x
    * [MINDEXER-110](https://issues.apache.org/jira/browse/MINDEXER-110) - Upgrade parent to 31
    * [MINDEXER-114](https://issues.apache.org/jira/browse/MINDEXER-114) - Extend JarFileContentsIndexCreator to support zip files
    * [MINDEXER-115](https://issues.apache.org/jira/browse/MINDEXER-115) - Remove deprecated usages of BooleanQuery constructor - use Builder instead
    * [MINDEXER-116](https://issues.apache.org/jira/browse/MINDEXER-116) - Move to Java 8 as minimum Java version
    * [MINDEXER-117](https://issues.apache.org/jira/browse/MINDEXER-117) - Add ability to set the temporary index directory for index update
    * [MINDEXER-118](https://issues.apache.org/jira/browse/MINDEXER-118) - Remove usages of pre-Lucene 4.0 deprecated code
    * [MINDEXER-120](https://issues.apache.org/jira/browse/MINDEXER-120) - Remove TrueZip dependency
    * [MINDEXER-122](https://issues.apache.org/jira/browse/MINDEXER-122) - Add getName() to Record.EntryKey
    * [MINDEXER-129](https://issues.apache.org/jira/browse/MINDEXER-129) - Shared GitHub Actions
    * [MINDEXER-132](https://issues.apache.org/jira/browse/MINDEXER-132) - use Files.createTempDirectory(...) instead of custom code around File.createTempFile(...)

* Tasks:

    * [MINDEXER-109](https://issues.apache.org/jira/browse/MINDEXER-109) - switch from Git-WIP to Gitbox
    * [MINDEXER-113](https://issues.apache.org/jira/browse/MINDEXER-113) - Excluding additional dependencies from shaded jar
    * [MINDEXER-134](https://issues.apache.org/jira/browse/MINDEXER-134) - Update dependencies (except Lucene)
    * [MINDEXER-137](https://issues.apache.org/jira/browse/MINDEXER-137) - Align example packages with indexer packages
    * [MINDEXER-139](https://issues.apache.org/jira/browse/MINDEXER-139) - Decouple from Plexus APIs
    * [MINDEXER-140](https://issues.apache.org/jira/browse/MINDEXER-140) - DefaultIndexingContext double invocation of setIndexDirectoryFile method

* Dependency upgrades:

    * [MINDEXER-111](https://issues.apache.org/jira/browse/MINDEXER-111) - Upgrade mave-surefire/failsafe-plugin 2.21.0
    * [MINDEXER-112](https://issues.apache.org/jira/browse/MINDEXER-112) - Upgrade maven-parent to version 34
    * [MINDEXER-126](https://issues.apache.org/jira/browse/MINDEXER-126) - Remove guava dependency from indexer-core

Enjoy,

-The Apache Maven team
