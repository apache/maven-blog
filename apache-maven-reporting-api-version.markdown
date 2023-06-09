---
layout: post
title: Apache Maven Reporting API Version 3.1.0 Released
date: '2022-02-05T12:50:50+00:00'
permalink: apache-maven-reporting-api-version
---
<div class="entry-content"><p>The Apache Maven team is pleased to announce the release of the
<a href="https://maven.apache.org/shared/maven-reporting-api/">Apache Shared Component: Apache Maven Reporting API Version 3.1.0</a></p>

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
</span><span class='line'>  <span class="nt">&lt;version&gt;</span>3.1.0<span class="nt">&lt;/version&gt;</span>
</span><span class='line'><span class="nt">&lt;/plugin&gt;</span>
</span></code></pre></td></tr></table></div></figure>




<!-- more -->


<p><a href="https://issues.apache.org/jira/projects/MSHARED/versions/12331438">Release Notes</a></p>

<ul>
<li><p>Improvements:</p>

<ul>
<li>[MSHARED-812] &ndash; Require Java 7</li>
<li>[MSHARED-879] &ndash; make build Reproducible</li>
</ul>
</li>
<li><p>Task:</p>

<ul>
<li>[MSHARED-1024] &ndash; Replace deprecated code</li>
</ul>
</li>
<li><p>Dependency upgrade:</p>

<ul>
<li>[MSHARED-844] &ndash; Upgrade to Doxia 1.11.1</li>
</ul>
</li>
</ul>


<p>Enjoy,</p>

<p>-The Apache Maven Team</p>
