---
layout: post
title: Apache Maven Indexer Version 6.1.1 Released
date: '2022-02-17T13:34:18+00:00'
permalink: apache-maven-indexer-version-6
---
<div class="entry-content"><p>The Apache Maven team is pleased to announce the release of the
  <a href="https://maven.apache.org/maven-indexer/">Apache Maven Indexer, version 6.1.1</a>.</p>

  <p>Apache Maven Indexer (former Sonatype Nexus Indexer) is the de facto standard for producing indexes
    of Maven repositories. The Indexes are produced and consumed by all major tools in the ecosystem.</p>

  <p>Most notable changes:
    * Java 8 required
    * Lucene upgraded to latest 8.x (8.11.1)
    * Guava and TrueZip dependencies removed</p>

  <p>You can download the appropriate sources etc. from the download page:</p>

  <p><a href="https://maven.apache.org/maven-indexer/download.cgi">https://maven.apache.org/maven-indexer/download.cgi</a></p>

  <!-- more -->


  <p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?version=12351333&amp;styleName=Text&amp;projectId=12317523">Release Notes &ndash; Maven Indexer &ndash; Version 6.1.1</a></p>

  <ul>
    <li><p>Bugs:</p>

      <ul>
        <li><a href="https://issues.apache.org/jira/browse/MINDEXER-123">MINDEXER-123</a> &ndash; Fix an InputStream leak in indexer-reader Utils</li>
        <li><a href="https://issues.apache.org/jira/browse/MINDEXER-127">MINDEXER-127</a> &ndash; Maven repository indexing error: java.nio.channels.OverlappingFileLockException</li>
        <li><a href="https://issues.apache.org/jira/browse/MINDEXER-133">MINDEXER-133</a> &ndash; Reset the correct stream in IndexDataReader</li>
        <li><a href="https://issues.apache.org/jira/browse/MINDEXER-135">MINDEXER-135</a> &ndash; Fix CLI shading</li>
        <li><a href="https://issues.apache.org/jira/browse/MINDEXER-138">MINDEXER-138</a> &ndash; Indexer Core Jetty test dependency is not in test scope</li>
      </ul>
    </li>
    <li><p>Improvements:</p>

      <ul>
        <li><a href="https://issues.apache.org/jira/browse/MINDEXER-104">MINDEXER-104</a> &ndash; Migrate the indexer to Lucene 8.x</li>
        <li><a href="https://issues.apache.org/jira/browse/MINDEXER-110">MINDEXER-110</a> &ndash; Upgrade parent to 31</li>
        <li><a href="https://issues.apache.org/jira/browse/MINDEXER-114">MINDEXER-114</a> &ndash; Extend JarFileContentsIndexCreator to support zip files</li>
        <li><a href="https://issues.apache.org/jira/browse/MINDEXER-115">MINDEXER-115</a> &ndash; Remove deprecated usages of BooleanQuery constructor &ndash; use Builder instead</li>
        <li><a href="https://issues.apache.org/jira/browse/MINDEXER-116">MINDEXER-116</a> &ndash; Move to Java 8 as minimum Java version</li>
        <li><a href="https://issues.apache.org/jira/browse/MINDEXER-117">MINDEXER-117</a> &ndash; Add ability to set the temporary index directory for index update</li>
        <li><a href="https://issues.apache.org/jira/browse/MINDEXER-118">MINDEXER-118</a> &ndash; Remove usages of pre-Lucene 4.0 deprecated code</li>
        <li><a href="https://issues.apache.org/jira/browse/MINDEXER-120">MINDEXER-120</a> &ndash; Remove TrueZip dependency</li>
        <li><a href="https://issues.apache.org/jira/browse/MINDEXER-122">MINDEXER-122</a> &ndash; Add getName() to Record.EntryKey</li>
        <li><a href="https://issues.apache.org/jira/browse/MINDEXER-129">MINDEXER-129</a> &ndash; Shared GitHub Actions</li>
        <li><a href="https://issues.apache.org/jira/browse/MINDEXER-132">MINDEXER-132</a> &ndash; use Files.createTempDirectory(&hellip;) instead of custom code around File.createTempFile(&hellip;)</li>
      </ul>
    </li>
    <li><p>Tasks:</p>

      <ul>
        <li><a href="https://issues.apache.org/jira/browse/MINDEXER-109">MINDEXER-109</a> &ndash; switch from Git-WIP to Gitbox</li>
        <li><a href="https://issues.apache.org/jira/browse/MINDEXER-113">MINDEXER-113</a> &ndash; Excluding additional dependencies from shaded jar</li>
        <li><a href="https://issues.apache.org/jira/browse/MINDEXER-134">MINDEXER-134</a> &ndash; Update dependencies (except Lucene)</li>
        <li><a href="https://issues.apache.org/jira/browse/MINDEXER-137">MINDEXER-137</a> &ndash; Align example packages with indexer packages</li>
        <li><a href="https://issues.apache.org/jira/browse/MINDEXER-139">MINDEXER-139</a> &ndash; Decouple from Plexus APIs</li>
        <li><a href="https://issues.apache.org/jira/browse/MINDEXER-140">MINDEXER-140</a> &ndash; DefaultIndexingContext double invocation of setIndexDirectoryFile method</li>
      </ul>
    </li>
    <li><p>Dependency upgrades:</p>

      <ul>
        <li><a href="https://issues.apache.org/jira/browse/MINDEXER-111">MINDEXER-111</a> &ndash; Upgrade mave-surefire/failsafe-plugin 2.21.0</li>
        <li><a href="https://issues.apache.org/jira/browse/MINDEXER-112">MINDEXER-112</a> &ndash; Upgrade maven-parent to version 34</li>
        <li><a href="https://issues.apache.org/jira/browse/MINDEXER-126">MINDEXER-126</a> &ndash; Remove guava dependency from indexer-core</li>
      </ul>
    </li>
  </ul>


  <p>Enjoy,</p>

  <p>-The Apache Maven team</p>
</div>

