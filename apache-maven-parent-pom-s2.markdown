---
layout: post
title: Apache Maven Parent POM's Version 36 Released
date: '2022-04-22T10:32:33+00:00'
permalink: apache-maven-parent-pom-s2
---
<div class="entry-content"><p>The Apache Maven team is pleased to announce the release of the
  <a href="https://maven.apache.org/pom/maven/">Maven Parent POMs Version 36</a></p>

  <p>Maven Parent POMs include <a href="https://maven.apache.org/pom/maven/">Maven Parent POM</a>
    itself, but also <a href="https://maven.apache.org/pom/maven/maven-plugins/">Maven Plugins Parent POM</a>,
    <a href="https://maven.apache.org/pom/maven/maven-shared-components/">Maven Shared Components Parent POM</a>,
    <a href="https://maven.apache.org/pom/maven/maven-skins/">Maven Skins Parent POM</a> and
    Maven Doxia Tools Parent POM.</p>

  <p><a href="https://maven.apache.org/pom/maven/">https://maven.apache.org/pom/maven/</a></p>

  <p>You should specify the version in your project as parent like the following:</p>

  <figure class='code'><figcaption><span></span></figcaption><div class="highlight"><table><tr><td class="gutter"><pre class="line-numbers"><span class='line-number'>1</span>
<span class='line-number'>2</span>
<span class='line-number'>3</span>
<span class='line-number'>4</span>
<span class='line-number'>5</span>
</pre></td><td class='code'><pre><code class='xml'><span class='line'><span class="nt">&lt;parent&gt;</span>
</span><span class='line'>   <span class="nt">&lt;groupId&gt;</span>org.apache.maven<span class="nt">&lt;/groupId&gt;</span>
</span><span class='line'>   <span class="nt">&lt;artifactId&gt;</span>maven-parent<span class="nt">&lt;/artifactId&gt;</span>
</span><span class='line'>   <span class="nt">&lt;version&gt;</span>36<span class="nt">&lt;/version&gt;</span>
</span><span class='line'><span class="nt">&lt;/parent&gt;</span>
</span></code></pre></td></tr></table></div></figure>


  <p>You can download the appropriate sources etc. from the download page:</p>

  <p><a href="https://maven.apache.org/pom/maven/download.html">https://maven.apache.org/pom/maven/download.html</a></p>

  <!-- more -->


  <p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?version=12351408&amp;styleName=Text&amp;projectId=12311250">Release Notes &ndash; Apache Maven Parent POM &ndash; Version 36</a></p>

  <ul>
    <li><p>Improvements:</p>

      <ul>
        <li><a href="https://issues.apache.org/jira/browse/MPOM-300">MPOM-300</a> &ndash; Replace Google Analytics with ASF Matomo</li>
        <li><a href="https://issues.apache.org/jira/browse/MPOM-313">MPOM-313</a> &ndash; Execute checkstyle in early phase of the build</li>
      </ul>
    </li>
    <li><p>Dependency upgrades:</p>

      <ul>
        <li><a href="https://issues.apache.org/jira/browse/MPOM-308">MPOM-308</a> &ndash; Upgrade Maven PMD Plugin from 3.15.0 to 3.16.0</li>
        <li><a href="https://issues.apache.org/jira/browse/MPOM-309">MPOM-309</a> &ndash; Upgrade TagList Maven Plugin from 2.4 to 3.0.0</li>
        <li><a href="https://issues.apache.org/jira/browse/MPOM-311">MPOM-311</a> &ndash; Upgrade Maven JXR Plugin from 3.1.1 to 3.2.0</li>
        <li><a href="https://issues.apache.org/jira/browse/MPOM-314">MPOM-314</a> &ndash; Upgrade modello-maven-plugin from 1.11 to 2.0.0</li>
        <li><a href="https://issues.apache.org/jira/browse/MPOM-316">MPOM-316</a> &ndash; Upgrade ASF Parent to 26</li>
      </ul>
    </li>
  </ul>


  <p>Enjoy,
    &ndash; The Apache Maven Team</p>
</div>

