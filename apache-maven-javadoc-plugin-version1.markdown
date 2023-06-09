---
layout: post
title: Apache Maven JavaDoc Plugin Version 3.2.0 Released
date: '2020-03-17T19:00:04+00:00'
permalink: apache-maven-javadoc-plugin-version1
---
<div class="entry-content"><p>The Apache Maven team is pleased to announce the release of the
<a href="https://maven.apache.org/plugins/maven-javadoc-plugin">Apache Maven JavaDoc Plugin, version 3.2.0</a>.</p>

<p>The Javadoc Plugin uses the Javadoc tool to generate javadocs for the
specified project.</p>

<figure class='code'><figcaption><span></span></figcaption><div class="highlight"><table><tr><td class="gutter"><pre class="line-numbers"><span class='line-number'>1</span>
<span class='line-number'>2</span>
<span class='line-number'>3</span>
<span class='line-number'>4</span>
<span class='line-number'>5</span>
</pre></td><td class='code'><pre><code class='xml'><span class='line'><span class="nt">&lt;plugin&gt;</span>
</span><span class='line'>  <span class="nt">&lt;groupId&gt;</span>org.apache.maven.plugins<span class="nt">&lt;/groupId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;artifactId&gt;</span>maven-javadoc-plugin<span class="nt">&lt;/artifactId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;version&gt;</span>3.2.0<span class="nt">&lt;/version&gt;</span>
</span><span class='line'><span class="nt">&lt;/plugin&gt;</span>
</span></code></pre></td></tr></table></div></figure>


<p>You can download the appropriate sources etc. from the download page:</p>

<p><a href="https://maven.apache.org/plugins/maven-javadoc-plugin/download.cgi">https://maven.apache.org/plugins/maven-javadoc-plugin/download.cgi</a></p>

<!-- more -->


<p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317529&amp;version=12345698">Release Notes &ndash; Apache Maven JavaDoc Plugin &ndash; Version 3.2.0</a></p>

<ul>
<li><p>Bugs:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MJAVADOC-607">MJAVADOC-607</a> &ndash; followLinks fix to get redirect target breaks for certain sites</li>
<li><a href="https://issues.apache.org/jira/browse/MJAVADOC-609">MJAVADOC-609</a> &ndash; Include jars for which module name cannot be determined on the classpath</li>
<li><a href="https://issues.apache.org/jira/browse/MJAVADOC-612">MJAVADOC-612</a> &ndash; UnsupportedOperationException for javadoc:aggregate with multi modules with jpms</li>
<li><a href="https://issues.apache.org/jira/browse/MJAVADOC-616">MJAVADOC-616</a> &ndash; JavadocReportTest.testOptionsUmlautEncoding fails on Windows with default ecnoding that does not support umlauts</li>
<li><a href="https://issues.apache.org/jira/browse/MJAVADOC-620">MJAVADOC-620</a> &ndash; Maven Javadoc Plugin fails to resolve the dependencies when used with Java 11</li>
<li><a href="https://issues.apache.org/jira/browse/MJAVADOC-639">MJAVADOC-639</a> &ndash; aggregate should use all requires static from maven modules</li>
</ul>
</li>
<li><p>New Feature:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MJAVADOC-627">MJAVADOC-627</a> &ndash; Reproducible Builds: make entries in output jar files reproducible (order + timestamp)</li>
</ul>
</li>
<li><p>Improvements:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MJAVADOC-613">MJAVADOC-613</a> &ndash; Exclude some modules with aggregate goals</li>
<li><a href="https://issues.apache.org/jira/browse/MJAVADOC-626">MJAVADOC-626</a> &ndash; Detect stale files and skip generation if not needed</li>
<li><a href="https://issues.apache.org/jira/browse/MJAVADOC-632">MJAVADOC-632</a> &ndash; agggregate using jpms and non jar module is failing</li>
<li><a href="https://issues.apache.org/jira/browse/MJAVADOC-636">MJAVADOC-636</a> &ndash; Exclude some modules when building aggregate</li>
<li><a href="https://issues.apache.org/jira/browse/MJAVADOC-637">MJAVADOC-637</a> &ndash; make build Reproducible</li>
<li><a href="https://issues.apache.org/jira/browse/MJAVADOC-640">MJAVADOC-640</a> &ndash; Ability to exclude maven modules from javadoc aggregate goals</li>
</ul>
</li>
<li><p>Dependency upgrades:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MJAVADOC-635">MJAVADOC-635</a> &ndash; upgrade plexus-java 1.0.4</li>
<li><a href="https://issues.apache.org/jira/browse/MJAVADOC-638">MJAVADOC-638</a> &ndash; upgrade Doxia Sitetools to 1.9.2 to remove dependency on Struts</li>
</ul>
</li>
</ul>


<p>Enjoy,</p>

<p>-The Apache Maven team</p>
</div>
