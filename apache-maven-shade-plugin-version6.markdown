---
layout: post
title: Apache   Maven Shade Plugin, Version 3.3.0 Released
date: '2022-03-29T21:57:12+00:00'
permalink: apache-maven-shade-plugin-version6
---
<div class="entry-content"><p>The Apache Maven team is pleased to announce the release of the <a href="https://maven.apache.org/plugins/maven-shade-plugin/">Apache
  Maven Shade Plugin, version 3.3.0</a>.</p>

  <p>This plugin provides the capability to package the artifact in an uber-jar,
    including its dependencies and to shade &ndash; i.e. rename &ndash; the packages of some of
    the dependencies.</p>

  <p>You should specify the version in your project&rsquo;s plugin configuration:</p>

  <figure class='code'><figcaption><span></span></figcaption><div class="highlight"><table><tr><td class="gutter"><pre class="line-numbers"><span class='line-number'>1</span>
<span class='line-number'>2</span>
<span class='line-number'>3</span>
<span class='line-number'>4</span>
<span class='line-number'>5</span>
</pre></td><td class='code'><pre><code class='xml'><span class='line'><span class="nt">&lt;plugin&gt;</span>
</span><span class='line'>  <span class="nt">&lt;groupId&gt;</span>org.apache.maven.plugins<span class="nt">&lt;/groupId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;artifactId&gt;</span>maven-shade-plugin<span class="nt">&lt;/artifactId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;version&gt;</span>3.3.0<span class="nt">&lt;/version&gt;</span>
</span><span class='line'><span class="nt">&lt;/plugin&gt;</span>
</span></code></pre></td></tr></table></div></figure>


  <p>You can download the <a href="https://maven.apache.org/plugins/maven-shade-plugin/download.cgi">appropriate sources etc. from the download page</a></p>

  <!-- more -->


  <p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?version=12348391&amp;styleName=Text&amp;projectId=12317921">Release Notes &ndash; Maven Shade Plugin &ndash; Version 3.3.0</a></p>

  <ul>
    <li><p>Bugs:</p>

      <ul>
        <li><a href="https://issues.apache.org/jira/browse/MSHADE-252">MSHADE-252</a> &ndash; shadeSourcesContent is broken when combined with partial relocation</li>
        <li><a href="https://issues.apache.org/jira/browse/MSHADE-396">MSHADE-396</a> &ndash; Improve SourceContent Shading</li>
      </ul>
    </li>
    <li><p>New Feature:</p>

      <ul>
        <li><a href="https://issues.apache.org/jira/browse/MSHADE-36">MSHADE-36</a> &ndash; Add option to include dependency reduced POM instead of original one</li>
      </ul>
    </li>
    <li><p>Improvements:</p>

      <ul>
        <li><a href="https://issues.apache.org/jira/browse/MSHADE-321">MSHADE-321</a> &ndash; Always respect &lsquo;createDependencyReducedPom&rsquo; flag</li>
        <li><a href="https://issues.apache.org/jira/browse/MSHADE-371">MSHADE-371</a> &ndash; Update Shade Apache[Notice/LICENSE]ResourceTransformer to use also [NOTICE/LICENSE].md</li>
        <li><a href="https://issues.apache.org/jira/browse/MSHADE-373">MSHADE-373</a> &ndash; Source transformation on source jar can break OSGi resolution due to duplicated bundle name</li>
        <li><a href="https://issues.apache.org/jira/browse/MSHADE-382">MSHADE-382</a> &ndash; Add an option to skip execution</li>
        <li><a href="https://issues.apache.org/jira/browse/MSHADE-391">MSHADE-391</a> &ndash; Do not modify class files, if nothing was relocated</li>
        <li><a href="https://issues.apache.org/jira/browse/MSHADE-405">MSHADE-405</a> &ndash; ShowOverlapping Uses http instead of https</li>
      </ul>
    </li>
    <li><p>Tasks:</p>

      <ul>
        <li><a href="https://issues.apache.org/jira/browse/MSHADE-389">MSHADE-389</a> &ndash; Get rid of old baggage</li>
        <li><a href="https://issues.apache.org/jira/browse/MSHADE-390">MSHADE-390</a> &ndash; Implement Sisu index transformer</li>
        <li><a href="https://issues.apache.org/jira/browse/MSHADE-401">MSHADE-401</a> &ndash; Improve ServiceResourceTransformer</li>
        <li><a href="https://issues.apache.org/jira/browse/MSHADE-412">MSHADE-412</a> &ndash; SimpleRelocator can fail in NPE, in particular with manifest transformer</li>
      </ul>
    </li>
    <li><p>Dependency upgrades:</p>

      <ul>
        <li><a href="https://issues.apache.org/jira/browse/MSHADE-379">MSHADE-379</a> &ndash; Support Java 16 &ndash; upgrade ASM to 9.0</li>
        <li><a href="https://issues.apache.org/jira/browse/MSHADE-386">MSHADE-386</a> &ndash; Update JDependency to 2.6.0</li>
        <li><a href="https://issues.apache.org/jira/browse/MSHADE-407">MSHADE-407</a> &ndash; Update ASM to 9.2 to support Java 17</li>
      </ul>
    </li>
  </ul>


  <p>Enjoy,</p>

  <p>-The Apache Maven team</p>
</div>
