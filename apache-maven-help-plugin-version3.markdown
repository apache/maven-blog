---
layout: post
title: Apache Maven Help Plugin Version 3.2.0 Released
date: '2019-04-23T17:26:21+00:00'
permalink: apache-maven-help-plugin-version3
---
<div class="entry-content"><p>The Apache Maven team is pleased to announce the release of the
<a href="https://maven.apache.org/plugins/maven-help-plugin/">Apache Maven Help Plugin, version 3.2.0</a></p>

<p>The Maven Help Plugin is used to get relative information about a project or
the system. It can be used to get a description of a particular plugin,
including the plugin&rsquo;s goals with their parameters and component requirements,
the effective POM and effective settings of the current build, and the profiles
applied to the current project being built.</p>

<p>You should specify the version in your project&rsquo;s plugin configuration:</p>

<figure class='code'><figcaption><span></span></figcaption><div class="highlight"><table><tr><td class="gutter"><pre class="line-numbers"><span class='line-number'>1</span>
<span class='line-number'>2</span>
<span class='line-number'>3</span>
<span class='line-number'>4</span>
<span class='line-number'>5</span>
</pre></td><td class='code'><pre><code class='xml'><span class='line'><span class="nt">&lt;plugin&gt;</span>
</span><span class='line'>  <span class="nt">&lt;groupId&gt;</span>org.apache.maven.plugins<span class="nt">&lt;/groupId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;artifactId&gt;</span>maven-help-plugin<span class="nt">&lt;/artifactId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;version&gt;</span>3.2.0<span class="nt">&lt;/version&gt;</span>
</span><span class='line'><span class="nt">&lt;/plugin&gt;</span>
</span></code></pre></td></tr></table></div></figure>


<p>You can download the appropriate <a href="https://maven.apache.org/plugins/maven-help-plugin/download.cgi">sources etc. from the download page</a>.</p>

<!-- more -->


<p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317522&amp;version=12345382">Release Notes &ndash; Maven Help Plugin &ndash; Version 3.2.0</a></p>

<p>New Feature:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MPH-160">MPH-160</a> &ndash; help:effective-pom -Dverbose: add source location as comments in effective pom.xml</li>
</ul>


<p>Improvement:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MPH-161">MPH-161</a> &ndash; add color to goal or plugin description</li>
</ul>


<p>Enjoy,</p>

<p>-The Apache Maven team</p>
</div>
