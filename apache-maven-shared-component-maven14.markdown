---
layout: post
title: 'Apache Maven Shared Component: Maven Reporting Exec Version 2.0.0-M1 Released'
date: '2022-04-28T01:02:16+00:00'
permalink: apache-maven-shared-component-maven14
---
<div class="entry-content"><p>The Apache Maven team is pleased to announce the release of the
  <a href="https://maven.apache.org/shared/maven-reporting-exec/">Apache Maven Shared Component: Maven Reporting Exec Version 2.0.0-M1</a>.</p>

  <p>Classes to prepare report plugins execution with Maven 3, through
    <a href="https://maven.apache.org/shared/maven-reporting-exec/apidocs/org/apache/maven/reporting/exec/MavenReportExecutor.html">MavenReportExecutor</a> (<a href="https://maven.apache.org/shared/maven-reporting-exec/apidocs/org/apache/maven/reporting/exec/DefaultMavenReportExecutor.html">implementation</a>).</p>

  <p>You should specify the version in your project&rsquo;s plugin configuration:</p>

  <figure class='code'><figcaption><span></span></figcaption><div class="highlight"><table><tr><td class="gutter"><pre class="line-numbers"><span class='line-number'>1</span>
<span class='line-number'>2</span>
<span class='line-number'>3</span>
<span class='line-number'>4</span>
<span class='line-number'>5</span>
</pre></td><td class='code'><pre><code class='xml'><span class='line'><span class="nt">&lt;dependency&gt;</span>
</span><span class='line'>  <span class="nt">&lt;groupId&gt;</span>org.apache.maven.reporting<span class="nt">&lt;/groupId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;artifactId&gt;</span>maven-reporting-exec<span class="nt">&lt;/artifactId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;version&gt;</span>2.0.0-M1<span class="nt">&lt;/version&gt;</span>
</span><span class='line'><span class="nt">&lt;/plugin&gt;</span>
</span></code></pre></td></tr></table></div></figure>


  <p>You can download the appropriate sources etc. from the <a href="https://maven.apache.org/shared/maven-reporting-exec/download.cgi">download page</a>.</p>

  <!-- more -->


  <p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317922&amp;version=12348384">Release Notes Apache Maven Shared Component: Maven Reporting Exec Version 2.0.0-M1</a></p>

  <ul>
    <li><p>Tasks:</p>

      <ul>
        <li><a href="https://issues.apache.org/jira/browse/MSHARED-1060">MSHARED-1060</a> &ndash; Upgrade to Java 8</li>
        <li><a href="https://issues.apache.org/jira/browse/MSHARED-1061">MSHARED-1061</a> &ndash; Replace Plexus Logger with SLF4J</li>
        <li><a href="https://issues.apache.org/jira/browse/MSHARED-1064">MSHARED-1064</a> &ndash; Reintroduce org.codehaus.doxia.sink.Sink</li>
      </ul>
    </li>
    <li><p>Dependency upgrades:</p>

      <ul>
        <li><a href="https://issues.apache.org/jira/browse/MSHARED-1062">MSHARED-1062</a> &ndash; Upgrade Maven Reporting API to 4.0.0-M1</li>
        <li><a href="https://issues.apache.org/jira/browse/MSHARED-1063">MSHARED-1063</a> &ndash; Upgrade to Doxia Sitetools to 2.0.0-M2</li>
        <li><a href="https://issues.apache.org/jira/browse/MSHARED-1065">MSHARED-1065</a> &ndash; Upgrade plugins and components in UTs and ITs</li>
      </ul>
    </li>
  </ul>


  <p>Enjoy,</p>

  <p>-The Apache Maven team</p>
</div>
