---
layout: post
title: 'Apache Maven Shared Component: Maven Reporting Exec Version 1.5.1 Released'
date: '2020-06-20T13:16:32+00:00'
permalink: apache-maven-shared-component-maven7
---
<div class="entry-content"><p>The Apache Maven team is pleased to announce the release of the
<a href="https://maven.apache.org/shared/maven-reporting-exec/">Apache Maven Shared Component: Maven Reporting Exec Version 1.5.1</a>.</p>

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
</span><span class='line'>  <span class="nt">&lt;version&gt;</span>1.5.1<span class="nt">&lt;/version&gt;</span>
</span><span class='line'><span class="nt">&lt;/plugin&gt;</span>
</span></code></pre></td></tr></table></div></figure>


<p>You can download the appropriate sources etc. from the <a href="https://maven.apache.org/shared/maven-reporting-exec/download.cgi">download page</a>.</p>

<!-- more -->


<p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317922&amp;version=12348384">Release Notes Apache Maven Shared Component: Maven Reporting Exec Version 1.5.1</a></p>

<ul>
<li><p>Bugs:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-923">MSHARED-923</a> &ndash; upgrade maven-shade-plugin to 3.2.4 to get Reproducible Build</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-924">MSHARED-924</a> &ndash; fix Xpp3DomUtils shading relocation</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-921">MSHARED-921</a> &ndash; NoSuchMethodError: &lsquo;Xpp3Dom.getInputLocation()&rsquo; with Maven versions &lt; 3.6.1</li>
</ul>
</li>
<li><p>Improvements:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-814">MSHARED-814</a> &ndash; Require Java 7</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-879">MSHARED-879</a> &ndash; make build Reproducible</li>
</ul>
</li>
<li><p>Task:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-663">MSHARED-663</a> &ndash; mark ReportPlugin and ReportSet package private</li>
</ul>
</li>
</ul>


<p>Enjoy,</p>

<p>-The Apache Maven team</p>
</div>
