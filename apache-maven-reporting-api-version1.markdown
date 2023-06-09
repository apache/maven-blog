---
layout: post
title: Apache Maven Reporting API Version 4.0.0-M1
date: '2022-04-20T19:25:00+00:00'
permalink: apache-maven-reporting-api-version1
---
<div class="entry-content"><p>The Apache Maven team is pleased to announce the release of the
  <a href="https://maven.apache.org/shared/maven-reporting-api/">Apache Shared Component: Apache Maven Reporting API Version 4.0.0-M1</a></p>

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
</span><span class='line'>  <span class="nt">&lt;artifactId&gt;</span>maven-reporting-api<span class="nt">&lt;/artifactId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;version&gt;</span>4.0.0-M1<span class="nt">&lt;/version&gt;</span>
</span><span class='line'><span class="nt">&lt;/plugin&gt;</span>
</span></code></pre></td></tr></table></div></figure>




  <!-- more -->


  <p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?version=12351595&amp;styleName=Text&amp;projectId=12317922">Release Notes Maven Reporting API Version 4.0.0-M1</a></p>

  <ul>
    <li><p>Dependency upgrade:</p>

      <ul>
        <li><a href="https://issues.apache.org/jira/browse/MSHARED-1052">MSHARED-1052</a> &ndash; Upgrade to Java 8</li>
        <li><a href="https://issues.apache.org/jira/browse/MSHARED-1053">MSHARED-1053</a> &ndash; Upgrade Doxia to 2.0.0-M2</li>
        <li><a href="https://issues.apache.org/jira/browse/MSHARED-1054">MSHARED-1054</a> &ndash; Upgrade plugins</li>
      </ul>
    </li>
  </ul>


  <p>Enjoy,</p>

  <p>-The Apache Maven Team</p>
</div>
