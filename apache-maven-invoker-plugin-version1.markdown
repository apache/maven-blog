---
layout: post
title: Apache Maven Invoker Plugin Version 3.2.0 Released
date: '2019-01-21T20:54:48+00:00'
permalink: apache-maven-invoker-plugin-version1
---
<div class="entry-content"><p>The Apache Maven team is pleased to announce the release of the
<a href="http://maven.apache.org/plugins/maven-invoker-plugin/">Apache Maven Invoker Plugin, version 3.2.0</a>.</p>

<p>The Invoker Plugin is used to run a set of Maven projects. The plugin can
determine whether each project execution is successful, and optionally can
verify the output generated from a given project execution.</p>

<p>This plugin is in particular handy to perform integration tests for other Maven
plugins. The Invoker Plugin can be employed to run a set of test projects that
have been designed to assert certain features of the plugin under test.</p>

<p>You should specify the version in your project&rsquo;s plugin configuration:</p>

<figure class='code'><figcaption><span></span></figcaption><div class="highlight"><table><tr><td class="gutter"><pre class="line-numbers"><span class='line-number'>1</span>
<span class='line-number'>2</span>
<span class='line-number'>3</span>
<span class='line-number'>4</span>
<span class='line-number'>5</span>
</pre></td><td class='code'><pre><code class='xml'><span class='line'><span class="nt">&lt;plugin&gt;</span>
</span><span class='line'>  <span class="nt">&lt;groupId&gt;</span>org.apache.maven.plugins<span class="nt">&lt;/groupId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;artifactId&gt;</span>maven-invoker-plugin<span class="nt">&lt;/artifactId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;version&gt;</span>3.2.0<span class="nt">&lt;/version&gt;</span>
</span><span class='line'><span class="nt">&lt;/plugin&gt;</span>
</span></code></pre></td></tr></table></div></figure>


<p>You can download the appropriate sources etc. from the download page:</p>

<p><a href="https://maven.apache.org/plugins/maven-invoker-plugin/download.cgi">https://maven.apache.org/plugins/maven-invoker-plugin/download.cgi</a></p>

<!-- more -->


<p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317828&amp;version=12344638">Release Notes &ndash; Maven Invoker Plugin &ndash; Version 3.2.0</a></p>

<p>Bug:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MINVOKER-243">MINVOKER-243</a> &ndash; invoker:install doesn&rsquo;t copy transitive dependencies anymore (as of 3.1.0)</li>
</ul>


<p>Improvements:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MINVOKER-190">MINVOKER-190</a> &ndash; build.log file location causes problems</li>
<li><a href="https://issues.apache.org/jira/browse/MINVOKER-225">MINVOKER-225</a> &ndash; strange message ordering in case of post-build  script failure</li>
<li><a href="https://issues.apache.org/jira/browse/MINVOKER-245">MINVOKER-245</a> &ndash; Support toolchain selector</li>
<li><a href="https://issues.apache.org/jira/browse/MINVOKER-246">MINVOKER-246</a> &ndash; Support hierarchical invoker.properties</li>
</ul>


<p>Dependency upgrade:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MINVOKER-239">MINVOKER-239</a> &ndash; Upgrade maven-plugins parent to version 32</li>
</ul>


<p>Enjoy,</p>

<p>-The Apache Maven team</p>
</div>
