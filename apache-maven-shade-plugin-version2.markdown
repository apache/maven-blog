---
layout: post
title: Apache Maven Shade Plugin Version 3.2.1
date: '2018-11-12T12:20:49+00:00'
permalink: apache-maven-shade-plugin-version2
---
<div class="entry-content"><p>The Apache Maven team is pleased to announce the release of the <a href="http://maven.apache.org/plugins/maven-shade-plugin/">Apache
Maven Shade Plugin, version 3.2.1</a>.</p>

<p>This plugin provides the capability to package the artifact in an uber-jar,
including its dependencies and to shade &ndash; i.e. rename &ndash; the packages of some of
the dependencies.</p>

<p>You should specify the version in your project&rsquo;s plugin configuration:</p>

<figure class='code'><figcaption><span></span></figcaption><div class="highlight"><table><tr><td class="gutter"><pre class="line-numbers"><span class='line-number'>1</span>
<span class='line-number'>2</span>
<span class='line-number'>3</span>
<span class='line-number'>4</span>
<span class='line-number'>5</span>
</pre></td><td class='code'><pre><code class='xml'><span class='line'><span class="nt">&lt;plugin&gt;</span>
</span><span class='line'>  <span class="nt">&lt;groupId&gt;</span>org.apache.maven.plugins<span class="nt">&lt;/groupId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;artifactId&gt;</span>maven-shade-plugin<span class="nt">&lt;/artifactId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;version&gt;</span>3.2.1<span class="nt">&lt;/version&gt;</span>
</span><span class='line'><span class="nt">&lt;/plugin&gt;</span>
</span></code></pre></td></tr></table></div></figure>


<p>You can download the appropriate sources etc. from the <a href="https://maven.apache.org/plugins/maven-shade-plugin/download.cgi">download page</a>.</p>

<!-- more -->

<p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317921&amp;version=12344059">Release Notes &ndash; Maven Shade Plugin &ndash; Version 3.2.1</a></p>

<p>Bug:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MSHADE-302">MSHADE-302</a> &ndash; maven-shade-plugin fails to minimize JAR with Java 11</li>
</ul>


<p>Improvement:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MSHADE-303">MSHADE-303</a> &ndash; Suppress module-info.class warning if the file if filtered</li>
</ul>


<p>Task:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MSHADE-301">MSHADE-301</a> &ndash; java11 support</li>
</ul>


<p>Dependency upgrade:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MSHADE-299">MSHADE-299</a> &ndash; Upgrade maven-dependency-tree to 3.0.1</li>
</ul>


<p>Enjoy,</p>

<p>-The Apache Maven team</p>
</div>
