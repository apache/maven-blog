---
layout: post
title: Apache Maven Help Plugin Version 3.1.1 Released
date: '2018-12-12T19:08:23+00:00'
permalink: apache-maven-help-plugin-version2
---
<div class="entry-content"><p>The Apache Maven team is pleased to announce the release of the
<a href="http://maven.apache.org/plugins/maven-help-plugin/">Apache Maven Help Plugin, version 3.1.1</a></p>

<p>The Maven Help Plugin is used to get relative information about a project or
the system. It can be used to get a description of a particular plugin,
including the plugin&rsquo;s goals with their parameters and component requirements,
the effective POM and effective settings of the current build, and the profiles
applied to the current project being built.</p>

<p>Important Notes since Version 3.0.0</p>

<ul>
<li>Maven 3+ only</li>
<li>JDK 7 minimum requirement</li>
</ul>


<p>You should specify the version in your project&rsquo;s plugin configuration:</p>

<figure class='code'><figcaption><span></span></figcaption><div class="highlight"><table><tr><td class="gutter"><pre class="line-numbers"><span class='line-number'>1</span>
<span class='line-number'>2</span>
<span class='line-number'>3</span>
<span class='line-number'>4</span>
<span class='line-number'>5</span>
</pre></td><td class='code'><pre><code class='xml'><span class='line'><span class="nt">&lt;plugin&gt;</span>
</span><span class='line'>  <span class="nt">&lt;groupId&gt;</span>org.apache.maven.plugins<span class="nt">&lt;/groupId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;artifactId&gt;</span>maven-help-plugin<span class="nt">&lt;/artifactId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;version&gt;</span>3.1.1<span class="nt">&lt;/version&gt;</span>
</span><span class='line'><span class="nt">&lt;/plugin&gt;</span>
</span></code></pre></td></tr></table></div></figure>


<p>You can download the appropriate <a href="https://maven.apache.org/plugins/maven-help-plugin/download.cgi">sources etc. from the download page</a>.</p>

<!-- more -->


<p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317522&amp;version=12343422">Release Notes &ndash; Maven Help Plugin &ndash; Version 3.1.1</a></p>

<p>Improvement:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MPH-154">MPH-154</a> &ndash; The output of the plugin should be flushed when using forceStdout</li>
</ul>


<p>Dependency upgrades:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MPH-153">MPH-153</a> &ndash; Upgrade maven-plugins parent to version 32</li>
<li><a href="https://issues.apache.org/jira/browse/MPH-156">MPH-156</a> &ndash; Upgrade maven-artifact-transfer to 0.10.0</li>
<li><a href="https://issues.apache.org/jira/browse/MPH-157">MPH-157</a> &ndash; Upgrade plexus-interactivity-api 1.0-alpha-6</li>
<li><a href="https://issues.apache.org/jira/browse/MPH-158">MPH-158</a> &ndash; Upgrade xstream 1.4.11.1</li>
<li><a href="https://issues.apache.org/jira/browse/MPH-159">MPH-159</a> &ndash; Upgrade JUnit 4.12</li>
</ul>


<p>Enjoy,</p>

<p>-The Apache Maven team</p>
</div>
