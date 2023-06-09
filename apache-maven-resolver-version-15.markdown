---
layout: post
title: Apache Maven Resolver, Version 1.8.0 released
date: '2022-04-20T17:37:56+00:00'
permalink: apache-maven-resolver-version-15
---
<div class="entry-content"><p>The Apache Maven team is pleased to announce the release of the
  <a href="https://maven.apache.org/resolver/index.html">Apache Maven Resolver, version 1.8.0</a></p>

  <p>Apache Maven Artifact Resolver is a library for working with artifact
    repositories and dependency resolution.</p>

  <p>Maven Artifact Resolver deals with the specification of local repository,
    remote repository, developer workspaces, artifact transports and artifact
    resolution.</p>

  <p>It is expected to be extended by concrete repository implementation, like Maven
    Artifact Resolver Provider for Maven repositories or any other provider for
    other repository formats.</p>

  <p>You can download the appropriate sources etc. from the <a href="https://maven.apache.org/resolver/download.cgi">download page</a>.</p>

  <!-- more -->


  <p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?version=12351121&amp;styleName=Text&amp;projectId=12320628">Release Notes &ndash; Maven Resolver &ndash; Version Maven Artifact Resolver 1.8.0</a></p>

  <ul>
    <li><p>Bugs:</p>

      <ul>
        <li><a href="https://issues.apache.org/jira/browse/MRESOLVER-241">MRESOLVER-241</a> &ndash; Resolver checksum calculation should be driven by layout</li>
        <li><a href="https://issues.apache.org/jira/browse/MRESOLVER-242">MRESOLVER-242</a> &ndash; When no remote checksums provided by layout, transfer inevitably fails/warns</li>
        <li><a href="https://issues.apache.org/jira/browse/MRESOLVER-250">MRESOLVER-250</a> &ndash; Usage of descriptors map in DataPool prevents gargabe collection</li>
      </ul>
    </li>
    <li><p>New Feature:</p>

      <ul>
        <li><a href="https://issues.apache.org/jira/browse/MRESOLVER-236">MRESOLVER-236</a> &ndash; Make it possible to resolve .asc on a &lsquo;fail&rsquo; <checksumPolicy/> respository.</li>
      </ul>
    </li>
    <li><p>Improvements:</p>

      <ul>
        <li><a href="https://issues.apache.org/jira/browse/MRESOLVER-240">MRESOLVER-240</a> &ndash; Using breadth-first approach to resolve Maven dependencies</li>
        <li><a href="https://issues.apache.org/jira/browse/MRESOLVER-247">MRESOLVER-247</a> &ndash; Avoid unnecessary dependency resolution by a Skip solution based on BFS</li>
        <li><a href="https://issues.apache.org/jira/browse/MRESOLVER-248">MRESOLVER-248</a> &ndash; Make DF and BF collector implementations coexist</li>
      </ul>
    </li>
    <li><p>Tasks:</p>

      <ul>
        <li><a href="https://issues.apache.org/jira/browse/MRESOLVER-230">MRESOLVER-230</a> &ndash; Make supported checksum algorithms extensible</li>
        <li><a href="https://issues.apache.org/jira/browse/MRESOLVER-231">MRESOLVER-231</a> &ndash; Extend &ldquo;smart checksum&rdquo; feature</li>
        <li><a href="https://issues.apache.org/jira/browse/MRESOLVER-234">MRESOLVER-234</a> &ndash; Introduce &ldquo;provided&rdquo; checksums feature</li>
        <li><a href="https://issues.apache.org/jira/browse/MRESOLVER-237">MRESOLVER-237</a> &ndash; Make all checksum mismatches handled same</li>
        <li><a href="https://issues.apache.org/jira/browse/MRESOLVER-239">MRESOLVER-239</a> &ndash; Update and sanitize dependencies</li>
        <li><a href="https://issues.apache.org/jira/browse/MRESOLVER-244">MRESOLVER-244</a> &ndash; Deprecate FileTransformer API</li>
        <li><a href="https://issues.apache.org/jira/browse/MRESOLVER-245">MRESOLVER-245</a> &ndash; Isolate Hazelcast tests</li>
      </ul>
    </li>
    <li><p>Dependency upgrade:</p>

      <ul>
        <li><a href="https://issues.apache.org/jira/browse/MRESOLVER-249">MRESOLVER-249</a> &ndash; Update Hazelcast to 5.1.1 in named-locks-hazelcast module</li>
      </ul>
    </li>
  </ul>


  <p>Enjoy,</p>

  <ul>
    <li>The Apache Maven team</li>
  </ul>

</div>
