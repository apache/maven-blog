---
layout: post
title: Apache Maven EAR Plugin 3.0.1 Released
date: '2018-05-13T10:11:38+00:00'
permalink: apache-maven-ear-plugin-31
---
<div class="entry-content"><p>The Apache Maven team is pleased to announce the release of the
<a href="http://maven.apache.org/plugins/maven-ear-plugin/">Apache Maven EAR Plugin, version 3.0.1</a></p>

<p>This plugin generates Java EE Enterprise Archive (EAR) file. It can also
generate the deployment descriptor file (e.g. application.xml).</p>

<p>You should specify the version in your project&rsquo;s plugin configuration:</p>

<figure class='code'><figcaption><span></span></figcaption><div class="highlight"><table><tr><td class="gutter"><pre class="line-numbers"><span class='line-number'>1</span>
<span class='line-number'>2</span>
<span class='line-number'>3</span>
<span class='line-number'>4</span>
<span class='line-number'>5</span>
</pre></td><td class='code'><pre><code class='xml'><span class='line'><span class="nt">&lt;plugin&gt;</span>
</span><span class='line'>  <span class="nt">&lt;groupId&gt;</span>org.apache.maven.plugins<span class="nt">&lt;/groupId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;artifactId&gt;</span>maven-ear-plugin<span class="nt">&lt;/artifactId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;version&gt;</span>3.0.1<span class="nt">&lt;/version&gt;</span>
</span><span class='line'><span class="nt">&lt;/plugin&gt;</span>
</span></code></pre></td></tr></table></div></figure>


<p>You can download the appropriate <a href="https://maven.apache.org/plugins/maven-ear-plugin/download.cgi">sources etc. from the download page</a>.</p>

<!-- more -->


<p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317422&amp;version=12342882">Release Notes &ndash; Maven EAR Plugin &ndash; Version 3.0.1</a></p>

<p>Improvements:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MEAR-265">MEAR-265</a> &ndash; Add documentation information for GitHub</li>
<li><a href="https://issues.apache.org/jira/browse/MEAR-266">MEAR-266</a> &ndash; Upgrade mave-surefire/failsafe-plugin 2.21.0</li>
</ul>


<p>Dependency upgrade:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MEAR-268">MEAR-268</a> &ndash; Upgrade plexus-archiver to 3.6.0</li>
</ul>


<p>Enjoy,</p>

<p>-The Apache Maven team</p>
</div>
