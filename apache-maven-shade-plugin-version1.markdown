---
layout: post
title: Apache Maven Shade Plugin Version 3.2.0
date: '2018-09-12T20:46:31+00:00'
permalink: apache-maven-shade-plugin-version1
---
<div class="entry-content"><p>The Apache Maven team is pleased to announce the release of the <a href="http://maven.apache.org/plugins/maven-shade-plugin/">Apache
Maven Shade Plugin, version 3.2.0</a>.</p>

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
</span><span class='line'>  <span class="nt">&lt;version&gt;</span>3.2.0<span class="nt">&lt;/version&gt;</span>
</span><span class='line'><span class="nt">&lt;/plugin&gt;</span>
</span></code></pre></td></tr></table></div></figure>


<p>You can download the appropriate sources etc. from the <a href="https://maven.apache.org/plugins/maven-shade-plugin/download.cgi">download page</a>.</p>

<!-- more -->


<p>You can download the <a href="http://maven.apache.org/plugins/maven-shade-plugin/download.cgi">appropriate sources etc. from the download page</a>.</p>

<p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317921&amp;version=12343491">Release Notes &ndash; Maven Shade Plugin &ndash; Version 3.2.0</a></p>

<p>Bug:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MSHADE-289">MSHADE-289</a> &ndash; Maven Shade Plugin does not work under Java 10</li>
</ul>


<p>Improvement:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MSHADE-293">MSHADE-293</a> &ndash; Require Java 7</li>
</ul>


<p>Dependency upgrades:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MSHADE-294">MSHADE-294</a> &ndash; Upgrade maven-plugins parent to version 32</li>
<li><a href="https://issues.apache.org/jira/browse/MSHADE-296">MSHADE-296</a> &ndash; Upgrade maven-artifact-transfer 0.10.0</li>
</ul>


<p>Enjoy,</p>

<p>-The Apache Maven team</p>
</div>
