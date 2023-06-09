---
layout: post
title: Apache Maven Reporting Impl Version 4.0.0-M1
date: '2022-04-23T23:47:57+00:00'
permalink: apache-maven-reporting-impl-version1
---
<div class="entry-content"><p>The Apache Maven team is pleased to announce the release of the
  <a href="https://maven.apache.org/shared/maven-reporting-impl/">Apache Shared Component: Apache Maven Reporting Impl. Version 4.0.0-M1</a></p>

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
</span><span class='line'>  <span class="nt">&lt;version&gt;</span>4.0.0-M1<span class="nt">&lt;/version&gt;</span>
</span><span class='line'><span class="nt">&lt;/plugin&gt;</span>
</span></code></pre></td></tr></table></div></figure>




  <!-- more -->


  <p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317922&amp;version=12351596">Release Notes</a></p>

  <ul>
    <li><p>Task:</p>

      <ul>
        <li><a href="https://issues.apache.org/jira/browse/MSHARED-1055">MSHARED-1055</a> &ndash; Upgrade to Java 8</li>
      </ul>
    </li>
    <li><p>Dependency upgrades:</p>

      <ul>
        <li><a href="https://issues.apache.org/jira/browse/MSHARED-1056">MSHARED-1056</a> &ndash; Upgrade to Maven 3.2.5</li>
        <li><a href="https://issues.apache.org/jira/browse/MSHARED-1057">MSHARED-1057</a> &ndash; Upgrade to Doxia/Doxia Sitetools to 2.0.0-M2</li>
        <li><a href="https://issues.apache.org/jira/browse/MSHARED-1058">MSHARED-1058</a> &ndash; Upgrade components</li>
        <li><a href="https://issues.apache.org/jira/browse/MSHARED-1059">MSHARED-1059</a> &ndash; Upgrade Maven Reporting API to 4.0.0-M1</li>
      </ul>
    </li>
  </ul>


  <p>Enjoy,</p>
  <p>-The Apache Maven Team</p>
</div>
