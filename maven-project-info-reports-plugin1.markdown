---
layout: post
title: Maven Project Info Reports Plugin Version 3.2.1 Released
date: '2022-02-05T12:51:51+00:00'
permalink: maven-project-info-reports-plugin1
---
<div class="entry-content"><p>The Apache Maven team is pleased to announce the release of the
  <a href="https://maven.apache.org/plugins/maven-project-info-reports-plugin/">Maven Project Info Reports Plugin version 3.2.1</a></p>

  <p>You should specify the version in your project&rsquo;s plugin configuration:</p>

  <figure class='code'><figcaption><span></span></figcaption><div class="highlight"><table><tr><td class="gutter"><pre class="line-numbers"><span class='line-number'>1</span>
<span class='line-number'>2</span>
<span class='line-number'>3</span>
<span class='line-number'>4</span>
<span class='line-number'>5</span>
</pre></td><td class='code'><pre><code class='xml'><span class='line'><span class="nt">&lt;plugin&gt;</span>
</span><span class='line'>  <span class="nt">&lt;groupId&gt;</span>org.apache.maven.plugins<span class="nt">&lt;/groupId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;artifactId&gt;</span>maven-project-info-reports-plugin<span class="nt">&lt;/artifactId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;version&gt;</span>3.2.1<span class="nt">&lt;/version&gt;</span>
</span><span class='line'><span class="nt">&lt;/plugin&gt;</span>
</span></code></pre></td></tr></table></div></figure>


  <p>You can download the appropriate sources etc. from the
    <a href="https://maven.apache.org/plugins/maven-project-info-reports-plugin/download.cgi">download page</a>.</p>

  <!-- more -->


  <p></p>

  <p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317821&amp;version=12351375">Release Notes &ndash; Maven Project Info Reports Plugin &ndash; Version 3.2.1</a></p>

  <ul>
    <li><p>Bugs:</p>

      <ul>
        <li><a href="https://issues.apache.org/jira/browse/MPIR-403">MPIR-403</a> &ndash; Travis link should point to travis-ci.com instead of travis-ci.org</li>
        <li><a href="https://issues.apache.org/jira/browse/MPIR-404">MPIR-404</a> &ndash; Warn and accept invalid mailing list links</li>
        <li><a href="https://issues.apache.org/jira/browse/MPIR-405">MPIR-405</a> &ndash; Regression in Maven site rendering due to Doxia change to HTML5</li>
        <li><a href="https://issues.apache.org/jira/browse/MPIR-412">MPIR-412</a> &ndash; Dependency report generates non-well-formed output if the POM of a depdendency cannot be parsed</li>
      </ul>
    </li>
    <li><p>Improvement:</p>

      <ul>
        <li><a href="https://issues.apache.org/jira/browse/MPIR-408">MPIR-408</a> &ndash; Add some i18n properties for zh_CH</li>
      </ul>
    </li>
    <li><p>Dependency upgrades:</p>

      <ul>
        <li><a href="https://issues.apache.org/jira/browse/MPIR-409">MPIR-409</a> &ndash; Upgrade Maven Site Plugin to 3.10.0</li>
        <li><a href="https://issues.apache.org/jira/browse/MPIR-410">MPIR-410</a> &ndash; Upgrade Maven SCM to 1.12.2</li>
        <li><a href="https://issues.apache.org/jira/browse/MPIR-411">MPIR-411</a> &ndash; Upgrade Doxia to 1.11.1 and Doxia Sitetools to 1.11.1</li>
      </ul>
    </li>
  </ul>


  <p>Enjoy,</p>

  <p>-The Apache Maven team</p>
</div>
