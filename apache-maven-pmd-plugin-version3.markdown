---
layout: post
title: Apache Maven PMD Plugin Version 3.16.0 Released
date: '2022-02-15T20:34:34+00:00'
permalink: apache-maven-pmd-plugin-version3
---
<div class="entry-content"><p>The Maven team is pleased to announce the release of the
  <a href="https://maven.apache.org/plugins/maven-pmd-plugin/">Apache Maven PMD Plugin, version 3.16.0</a></p>

  <p>A Maven plugin for the PMD toolkit, that produces a report on both code rule
    violations and detected copy and paste fragments, as well as being able to fail
    the build based on these metrics.</p>

  <p>You can download the appropriate sources etc. from the
    <a href="https://maven.apache.org/plugins/maven-pmd-plugin/download.cgi">download page</a>.</p>

  <p>You should specify the version in your project&rsquo;s plugin configuration:</p>

  <figure class='code'><figcaption><span></span></figcaption><div class="highlight"><table><tr><td class="gutter"><pre class="line-numbers"><span class='line-number'>1</span>
<span class='line-number'>2</span>
<span class='line-number'>3</span>
<span class='line-number'>4</span>
<span class='line-number'>5</span>
</pre></td><td class='code'><pre><code class='xml'><span class='line'><span class="nt">&lt;plugin&gt;</span>
</span><span class='line'>  <span class="nt">&lt;groupId&gt;</span>org.apache.maven.plugins<span class="nt">&lt;/groupId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;artifactId&gt;</span>maven-pmd-plugin<span class="nt">&lt;/artifactId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;version&gt;</span>3.16.0<span class="nt">&lt;/version&gt;</span>
</span><span class='line'><span class="nt">&lt;/plugin&gt;</span>
</span></code></pre></td></tr></table></div></figure>




  <!-- more -->


  <p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?version=12350599&amp;styleName=Text&amp;projectId=12317621">Release Notes &ndash; Apache Maven PMD Plugin &ndash; Version 3.16.0</a></p>

  <ul>
    <li><p>Bugs:</p>

      <ul>
        <li><a href="https://issues.apache.org/jira/browse/MPMD-325">MPMD-325</a> &ndash; Could not find class due to IncompatibleClassChangeError warning</li>
        <li><a href="https://issues.apache.org/jira/browse/MPMD-324">MPMD-324</a> &ndash; Ruleset URLs have hyphen replaced with forwardslash</li>
        <li><a href="https://issues.apache.org/jira/browse/MPMD-323">MPMD-323</a> &ndash; ResourceManager should use project base dir instead of pom location</li>
      </ul>
    </li>
    <li><p>Improvement:</p>

      <ul>
        <li><a href="https://issues.apache.org/jira/browse/MPMD-328">MPMD-328</a> &ndash; Shared GitHub Actions</li>
      </ul>
    </li>
    <li><p>Tasks:</p>

      <ul>
        <li><a href="https://issues.apache.org/jira/browse/MPMD-327">MPMD-327</a> &ndash; Upgrade to PMD 6.42.0</li>
        <li><a href="https://issues.apache.org/jira/browse/MPMD-326">MPMD-326</a> &ndash; Set Maven 3.1.1 as minimum version</li>
      </ul>
    </li>
  </ul>


  <p>Enjoy,</p>

  <p>-The Maven team</p>
</div>
