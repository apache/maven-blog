---
layout: post
title: Apache Maven Shade Plugin version 3.2.3 Released
date: '2020-04-15T23:56:13+00:00'
permalink: apache-maven-shade-plugin-version4
---
<div class="entry-content"><p>The Apache Maven team is pleased to announce the release of the <a href="http://maven.apache.org/plugins/maven-shade-plugin/">Apache
Maven Shade Plugin, version 3.2.3</a>.</p>

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
</span><span class='line'>  <span class="nt">&lt;version&gt;</span>3.2.3<span class="nt">&lt;/version&gt;</span>
</span><span class='line'><span class="nt">&lt;/plugin&gt;</span>
</span></code></pre></td></tr></table></div></figure>


<p>You can download the <a href="https://maven.apache.org/shared/maven-archiver/download.cgi">appropriate sources etc. from the download page</a></p>

<!-- more -->


<p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317921&amp;version=12346981">Release Notes &ndash; Maven Shade Plugin &ndash; Version 3.2.3</a></p>

<ul>
<li><p>Bug:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MSHADE-352">MSHADE-352</a> &ndash; shaded jars are not reproducible when using transformer</li>
</ul>
</li>
<li><p>Dependency upgrades:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MSHADE-355">MSHADE-355</a> &ndash; Java 15 Compatibility &ndash; JDependecny/ASM Upgrade</li>
<li><a href="https://issues.apache.org/jira/browse/MSHADE-357">MSHADE-357</a> &ndash; Upgrade asm to 8.0</li>
</ul>
</li>
</ul>


<p>Enjoy,</p>

<p>-The Apache Maven team</p>
</div>
