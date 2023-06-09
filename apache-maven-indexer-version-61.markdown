---
layout: post
title: Apache Maven Indexer Version 6.2.0 Released
date: '2022-05-05T19:37:04+00:00'
permalink: apache-maven-indexer-version-61
---
<div class="entry-content"><p>The Apache Maven team is pleased to announce the release of the
  <a href="https://maven.apache.org/maven-indexer/">Apache Maven Indexer, version 6.2.0</a>.</p>

  <p>Apache Maven Indexer (former Sonatype Nexus Indexer) is the de facto standard for producing indexes
    of Maven repositories. The Indexes are produced and consumed by all major tools in the ecosystem.</p>

  <p>Most notable changes:</p>

  <ul>
    <li>IndexReader provides OOTB resource handlers</li>
    <li>Search API w/ 2 backends</li>
    <li>Bugs squashed</li>
  </ul>


  <p>IMPORTANT: Next release planned will use the Lucene version to 9.x, and
    that will imply Java 11. Hence, this is the LAST planned Java 8 release of
    Maven Indexer.</p>

  <p>You can download the appropriate sources etc. from the download page:</p>

  <p><a href="https://maven.apache.org/maven-indexer/download.cgi">https://maven.apache.org/maven-indexer/download.cgi</a></p>

  <!-- more -->


  <p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317523&version=12351653">Release Notes &ndash; Maven Indexer &ndash; Version 6.2.0</a></p>

  <ul>
    <li><p>Bugs:</p>

      <ul>
        <li><a href="https://issues.apache.org/jira/browse/MINDEXER-121">MINDEXER-121</a> &ndash; ChunkReaderIterator leaks InputStreams</li>
        <li><a href="https://issues.apache.org/jira/browse/MINDEXER-144">MINDEXER-144</a> &ndash; IndexOutOfBoundsException during indexing</li>
        <li><a href="https://issues.apache.org/jira/browse/MINDEXER-146">MINDEXER-146</a> &ndash; Fix issues reported by Lucene 9</li>
      </ul>
    </li>
    <li><p>New Feature</p>

      <ul>
        <li><a href="https://issues.apache.org/jira/browse/MINDEXER-124">MINDEXER-124</a> &ndash; IndexReader modules should provide resource handler implementations</li>
        <li><a href="https://issues.apache.org/jira/browse/MINDEXER-143">MINDEXER-143</a> &ndash; Introduce Search API and provide backends</li>
      </ul>
    </li>
    <li><p>Tasks:</p>

      <ul>
        <li><a href="https://issues.apache.org/jira/browse/MINDEXER-145">MINDEXER-145</a> &ndash; Update parent POM and dependencies</li>
        <li><a href="https://issues.apache.org/jira/browse/MINDEXER-147">MINDEXER-147</a> &ndash; Move rootGroups and allGroups fields out of index</li>
        <li><a href="https://issues.apache.org/jira/browse/MINDEXER-149">MINDEXER-149</a> &ndash; Deprecate Maven1 support</li>
      </ul>
    </li>
  </ul>


  <p>Enjoy,</p>

  <p>-The Apache Maven team</p>
</div>

