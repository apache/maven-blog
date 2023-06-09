---
layout: post
title: Apache Maven Reporting Impl. Version 3.1.0 Released
date: '2022-02-09T21:37:37+00:00'
permalink: apache-maven-reporting-impl-version
---
<div class="entry-content"><p>The Apache Maven team is pleased to announce the release of the
  <a href="https://maven.apache.org/shared/maven-reporting-impl/">Apache Shared Component: Apache Maven Reporting Impl. Version 3.1.0</a></p>

  <p>Abstract classes to manage report generation, which can be run both:</p>

  <ul>
    <li>as part of a site generation, as a <a href="https://maven.apache.org/shared/maven-reporting-api/">maven-reporting-api</a>&rsquo;s <a href="https://maven.apache.org/shared/maven-reporting-api/apidocs/org/apache/maven/reporting/MavenReport.html">MavenReport</a>,</li>
    <li>or as a direct standalone goal invocation, as a <a href="https://maven.apache.org/ref/current/maven-plugin-api/">maven-plugin-api</a>&rsquo;s <a href="https://maven.apache.org/ref/current/maven-plugin-api/apidocs/org/apache/maven/plugin/Mojo.html">Mojo</a>.</li>
  </ul>


  <figure class='code'><figcaption><span></span></figcaption><div class="highlight"><table><tr><td class="gutter"><pre class="line-numbers"><span class='line-number'>1</span>
<span class='line-number'>2</span>
<span class='line-number'>3</span>
<span class='line-number'>4</span>
<span class='line-number'>5</span>
</pre></td><td class='code'><pre><code class='xml'><span class='line'><span class="nt">&lt;plugin&gt;</span>
</span><span class='line'>  <span class="nt">&lt;groupId&gt;</span>org.apache.maven.reporting<span class="nt">&lt;/groupId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;artifactId&gt;</span>maven-reporting-impl<span class="nt">&lt;/artifactId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;version&gt;</span>3.1.0<span class="nt">&lt;/version&gt;</span>
</span><span class='line'><span class="nt">&lt;/plugin&gt;</span>
</span></code></pre></td></tr></table></div></figure>




  <!-- more -->


  <p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317922&amp;version=12341015">Release Notes</a></p>

  <ul>
    <li><p>Improvements:</p>

      <ul>
        <li><a href="https://issues.apache.org/jira/browse/MSHARED-813">MSHARED-813</a> &ndash; Require Java 7</li>
        <li><a href="https://issues.apache.org/jira/browse/MSHARED-879">MSHARED-879</a> &ndash; make build Reproducible</li>
      </ul>
    </li>
    <li><p>Dependency upgrades:</p>

      <ul>
        <li><a href="https://issues.apache.org/jira/browse/MSHARED-956">MSHARED-956</a> &ndash; Set minimum supported Maven version to 3.1.0</li>
        <li><a href="https://issues.apache.org/jira/browse/MSHARED-1027">MSHARED-1027</a> &ndash; Update Doxia to 1.11.1 and Doxia Sitetools to 1.11.1</li>
        <li><a href="https://issues.apache.org/jira/browse/MSHARED-1028">MSHARED-1028</a> &ndash; Upgrade Maven Reporting API to 3.1.0</li>
      </ul>
    </li>
  </ul>


  <p>Tasks:</p>

  <ul>
    <li><a href="https://issues.apache.org/jira/browse/MSHARED-606">MSHARED-606</a> &ndash; &ndash; Upgrade to Commons Validator 1.5.1</li>
    <li><a href="https://issues.apache.org/jira/browse/MSHARED-609">MSHARED-609</a> &ndash; &ndash; Partially revert MSHARED-429</li>
    <li><a href="https://issues.apache.org/jira/browse/MSHARED-611">MSHARED-611</a> &ndash; &ndash; Drop any href validation and pass as-is</li>
    <li><a href="https://issues.apache.org/jira/browse/MSHARED-612">MSHARED-612</a> &ndash; &ndash; Upgrade to Doxia 1.7</li>
    <li><a href="https://issues.apache.org/jira/browse/MSHARED-613">MSHARED-613</a> &ndash; &ndash; Upgrade to Doxia Sitetools 1.7.4</li>
    <li><a href="https://issues.apache.org/jira/browse/MSHARED-614">MSHARED-614</a> &ndash; &ndash; Upgrade to Maven Shared Utils 3.1.0</li>
  </ul>


  <p>Wish:</p>

  <ul>
    <li><a href="https://issues.apache.org/jira/browse/MSHARED-488">MSHARED-488</a> &ndash; &ndash; Make input source file encoding default to platform encoding</li>
  </ul>


  <p>Enjoy,</p>

  <p>-The Apache Maven Team</p>
