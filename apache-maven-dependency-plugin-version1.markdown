---
layout: post
title: Apache Maven Dependency Plugin Version 3.1.1 Released
date: '2018-05-24T13:43:56+00:00'
permalink: apache-maven-dependency-plugin-version1
---
<div class="entry-content"><p>The Apache Maven team is pleased to announce the release of the
<a href="http://maven.apache.org/plugins/maven-dependency-plugin/">Apache Maven Dependecy Plugin, version 3.1.1</a>.</p>

<p>The dependency plugin provides the capability to manipulate artifacts. It
can copy and/or unpack artifacts from local or remote repositories to a
specified location.</p>

<p><a href="https://maven.apache.org/plugins/maven-dependency-plugin/">https://maven.apache.org/plugins/maven-dependency-plugin/</a></p>

<p>You should specify the version in your project&rsquo;s plugin configuration:</p>

<figure class='code'><figcaption><span></span></figcaption><div class="highlight"><table><tr><td class="gutter"><pre class="line-numbers"><span class='line-number'>1</span>
<span class='line-number'>2</span>
<span class='line-number'>3</span>
<span class='line-number'>4</span>
<span class='line-number'>5</span>
</pre></td><td class='code'><pre><code class='xml'><span class='line'><span class="nt">&lt;plugin&gt;</span>
</span><span class='line'>    <span class="nt">&lt;groupId&gt;</span>org.apache.maven.plugins<span class="nt">&lt;/groupId&gt;</span>
</span><span class='line'>    <span class="nt">&lt;artifactId&gt;</span>maven-dependency-plugin<span class="nt">&lt;/artifactId&gt;</span>
</span><span class='line'>    <span class="nt">&lt;version&gt;</span>3.1.1<span class="nt">&lt;/version&gt;</span>
</span><span class='line'><span class="nt">&lt;/plugin&gt;</span>
</span></code></pre></td></tr></table></div></figure>


<p></p>

<p>You can download the appropriate sources etc. from the download page:</p>

<p><a href="https://maven.apache.org/plugins/maven-dependency-plugin/download.cgi">https://maven.apache.org/plugins/maven-dependency-plugin/download.cgi</a></p>

<!-- more -->


<p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317227&amp;version=12343248">Release Notes &ndash; Maven Dependency Plugin &ndash; Version 3.1.1</a></p>

<p>Bug:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MDEP-607">MDEP-607</a> &ndash; maven-dependency-plugin:3.1.0:analyze failed.: NullPointerException</li>
</ul>


<p>Dependency upgrades:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MDEP-611">MDEP-611</a> &ndash; Upgrade plexus-archiver to 3.6.0</li>
<li><a href="https://issues.apache.org/jira/browse/MDEP-612">MDEP-612</a> &ndash; Upgrade maven-dependency-analyzer to 1.10</li>
<li><a href="https://issues.apache.org/jira/browse/MDEP-614">MDEP-614</a> &ndash; Upgrade file-management to 3.0.0</li>
</ul>


<p>Many thanks to all reporters/contributors/testers of this release.</p>

<p>Reporters:</p>

<ul>
<li>MDEP-607: Filipe Sousa</li>
</ul>


<p>Enjoy,</p>

<p>-The Apache Maven team</p>
</div>
