---
layout: post
title: "Apache Maven Indexer Version 6.2.0 Released"
date: '2022-05-05T19:37:04+00:00'
permalink: apache-maven-indexer-version-6-2-0
categories:
  - Maven-Indexer
---
The Apache Maven team is pleased to announce the release of the
[Apache Maven Indexer, version 6.2.0](https://maven.apache.org/maven-indexer/).

Apache Maven Indexer (former Sonatype Nexus Indexer) is the de facto standard for producing indexes
of Maven repositories. The Indexes are produced and consumed by all major tools in the ecosystem.

Most notable changes:

* IndexReader provides OOTB resource handlers
* Search API w/ 2 backends
* Bugs squashed

IMPORTANT: Next release planned will use the Lucene version to 9.x, and
that will imply Java 11. Hence, this is the LAST planned Java 8 release of
Maven Indexer.


You can download the appropriate sources etc. from the download page:

https://maven.apache.org/maven-indexer/download.cgi


<!-- more -->

[Release Notes - Maven Indexer - Version 6.2.0](https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317523&version=12351653)

* Bugs:

    * [MINDEXER-121](https://issues.apache.org/jira/browse/MINDEXER-121) - ChunkReaderIterator leaks InputStreams
    * [MINDEXER-144](https://issues.apache.org/jira/browse/MINDEXER-144) - IndexOutOfBoundsException during indexing
    * [MINDEXER-146](https://issues.apache.org/jira/browse/MINDEXER-146) - Fix issues reported by Lucene 9

* New Feature

    * [MINDEXER-124](https://issues.apache.org/jira/browse/MINDEXER-124) - IndexReader modules should provide resource handler implementations
    * [MINDEXER-143](https://issues.apache.org/jira/browse/MINDEXER-143) - Introduce Search API and provide backends

* Tasks:

    * [MINDEXER-145](https://issues.apache.org/jira/browse/MINDEXER-145) - Update parent POM and dependencies
    * [MINDEXER-147](https://issues.apache.org/jira/browse/MINDEXER-147) - Move rootGroups and allGroups fields out of index
    * [MINDEXER-149](https://issues.apache.org/jira/browse/MINDEXER-149) - Deprecate Maven1 support


Enjoy,

-The Apache Maven team
