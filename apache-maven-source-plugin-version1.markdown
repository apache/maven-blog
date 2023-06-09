---
layout: post
title: Apache Maven Source Plugin Version 3.2.0 Released
date: '2019-11-04T10:53:47+00:00'
permalink: apache-maven-source-plugin-version1
---
<div class="entry-content"><p>The Apache Maven team is pleased to announce the release of the
  <a href="https://maven.apache.org/plugins/maven-source-plugin/">Apache Maven Source Plugin, Version 3.2.0</a>.</p>

  <p>This plugin creates a jar archive of the source files of the current project.</p>

  <figure class='code'><figcaption><span></span></figcaption><div class="highlight"><table><tr><td class="gutter"><pre class="line-numbers"><span class='line-number'>1</span>
<span class='line-number'>2</span>
<span class='line-number'>3</span>
<span class='line-number'>4</span>
<span class='line-number'>5</span>
</pre></td><td class='code'><pre><code class='xml'><span class='line'><span class="nt">&lt;plugin&gt;</span>
</span><span class='line'>  <span class="nt">&lt;groupId&gt;</span>org.apache.maven.plugins<span class="nt">&lt;/groupId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;artifactId&gt;</span>maven-source-plugin<span class="nt">&lt;/artifactId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;version&gt;</span>3.2.0<span class="nt">&lt;/version&gt;</span>
</span><span class='line'><span class="nt">&lt;/plugin&gt;</span>
</span></code></pre></td></tr></table></div></figure>


  <p>You can download the appropriate sources etc. from the <a href="https://maven.apache.org/plugins/maven-source-plugin/download.html">download page</a>.</p>

  <!-- more -->


  <p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317924&amp;version=12345522">Release Notes &ndash; Apache Maven Source Version 3.2.0</a></p>

  <p>Bug:</p>

  <ul>
    <li><a href="https://issues.apache.org/jira/browse/MSOURCES-95">MSOURCES-95</a> &ndash; Source JAR is re-created even if sources are not changed</li>
  </ul>


  <p>New Feature:</p>

  <ul>
    <li><a href="https://issues.apache.org/jira/browse/MSOURCES-120">MSOURCES-120</a> &ndash; Reproducible Builds: make entries in output jar files reproducible (order + timestamp)</li>
  </ul>


  <p>Read <a href="https://maven.apache.org/guides/mini/guide-reproducible-builds.html">https://maven.apache.org/guides/mini/guide-reproducible-builds.html</a> for more information on Reproducible Builds with Maven.</p>

  <p>Enjoy,</p>

  <p>-The Apache Maven team</p>
</div>

