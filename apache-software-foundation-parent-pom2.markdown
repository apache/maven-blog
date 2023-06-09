---
layout: post
title: Apache Software Foundation Parent POM Version 26 released
date: '2022-04-14T01:48:45+00:00'
permalink: apache-software-foundation-parent-pom2
---
<div class="entry-content"><p>The Apache Maven team is pleased to announce the release of the
  <a href="https://maven.apache.org/pom/asf/">Apache Software Foundation Parent POM Version 26</a>.</p>

  <p>You should specify the version in your project as parent like the following:</p>

  <figure class='code'><figcaption><span></span></figcaption><div class="highlight"><table><tr><td class="gutter"><pre class="line-numbers"><span class='line-number'>1</span>
<span class='line-number'>2</span>
<span class='line-number'>3</span>
<span class='line-number'>4</span>
<span class='line-number'>5</span>
</pre></td><td class='code'><pre><code class='xml'><span class='line'><span class="nt">&lt;parent&gt;</span>
</span><span class='line'>   <span class="nt">&lt;groupId&gt;</span>org.apache<span class="nt">&lt;/groupId&gt;</span>
</span><span class='line'>   <span class="nt">&lt;artifactId&gt;</span>apache<span class="nt">&lt;/artifactId&gt;</span>
</span><span class='line'>   <span class="nt">&lt;version&gt;</span>26<span class="nt">&lt;/version&gt;</span>
</span><span class='line'><span class="nt">&lt;/parent&gt;</span>
</span></code></pre></td></tr></table></div></figure>


  <p>You can download the appropriate sources etc. from the download page:</p>

  <p><a href="https://maven.apache.org/pom/asf/download.html">https://maven.apache.org/pom/asf/download.html</a></p>

  <!-- more -->


  <p>Release Notes &ndash; Maven POMs &ndash; Version ASF-26</p>

  <ul>
    <li><p>Improvement:</p>

      <ul>
        <li><a href="https://issues.apache.org/jira/browse/MPOM-310">MPOM-310</a> &ndash; Replace Google Analytics with ASF Matomo in documentation</li>
      </ul>
    </li>
    <li><p>Task:</p>

      <ul>
        <li><a href="https://issues.apache.org/jira/browse/MPOM-305">MPOM-305</a> &ndash; Set minimum enforced Maven version to 3.2.5</li>
      </ul>
    </li>
    <li><p>Dependency upgrades:</p>

      <ul>
        <li><a href="https://issues.apache.org/jira/browse/MPOM-304">MPOM-304</a> &ndash; Upgrade Maven Project Info Reports Plugin from 3.1.2 to 3.2.2</li>
        <li><a href="https://issues.apache.org/jira/browse/MPOM-306">MPOM-306</a> &ndash; Upgrade Maven Compiler Plugin from 3.10.0 to 3.10.1</li>
        <li><a href="https://issues.apache.org/jira/browse/MPOM-307">MPOM-307</a> &ndash; Upgrade Maven Dependency Plugin from 3.2.0 to 3.3.0</li>
        <li><a href="https://issues.apache.org/jira/browse/MPOM-312">MPOM-312</a> &ndash; Upgrade Maven Shade Plugin from 3.2.4 to 3.3.0</li>
        <li><a href="https://issues.apache.org/jira/browse/MPOM-315">MPOM-315</a> &ndash; Upgrade Maven Clean Plugin from 3.1.0 to 3.2.0</li>
      </ul>
    </li>
  </ul>


  <p>Enjoy,</p>

  <p>-The Apache Maven team</p>
</div>
