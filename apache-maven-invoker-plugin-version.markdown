---
layout: post
title: Apache Maven Invoker Plugin Version 3.1.0 Released
date: '2018-06-01T19:04:39+00:00'
permalink: apache-maven-invoker-plugin-version
---
<div class="entry-content"><p>The Apache Maven team is pleased to announce the release of the
<a href="http://maven.apache.org/plugins/maven-invoker-plugin/">Apache Maven Invoker Plugin, version 3.1.0</a>.</p>

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
</span><span class='line'>  <span class="nt">&lt;version&gt;</span>3.1.0<span class="nt">&lt;/version&gt;</span>
</span><span class='line'><span class="nt">&lt;/plugin&gt;</span>
</span></code></pre></td></tr></table></div></figure>


<p>You can download the appropriate sources etc. from the download page:</p>

<p><a href="https://maven.apache.org/plugins/maven-invoker-plugin/download.cgi">https://maven.apache.org/plugins/maven-invoker-plugin/download.cgi</a></p>

<!-- more -->


<p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?version=12341131&amp;styleName=Text&amp;projectId=12317525">Release Notes &ndash; Maven Invoker Plugin &ndash; Version 3.1.0</a></p>

<p>Bugs:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MINVOKER-191">MINVOKER-191</a> &ndash; “Artifact is not fully assembled” error with maven-invoker-plugin in parallel/multi thread build</li>
<li><a href="https://issues.apache.org/jira/browse/MINVOKER-224">MINVOKER-224</a> &ndash; Unable to set cloneProjectsTo to null</li>
</ul>


<p>New Feature:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MINVOKER-233">MINVOKER-233</a> &ndash; Call an invoker with a given timeout</li>
</ul>


<p>Improvement:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MINVOKER-236">MINVOKER-236</a> &ndash; improve display of setup jobs</li>
</ul>


<p>Tasks:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MINVOKER-228">MINVOKER-228</a> &ndash; Improve documentation: &ldquo;Using with other integration test frameworks&rdquo; page</li>
<li><a href="https://issues.apache.org/jira/browse/MINVOKER-237">MINVOKER-237</a> &ndash; Upgrade to JDK 7 minimum.</li>
</ul>


<p>Dependency upgrades:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MINVOKER-232">MINVOKER-232</a> &ndash; Upgrade parent to 31</li>
<li><a href="https://issues.apache.org/jira/browse/MINVOKER-234">MINVOKER-234</a> &ndash; Upgrade maven-shared-utils to 3.2.1</li>
<li><a href="https://issues.apache.org/jira/browse/MINVOKER-235">MINVOKER-235</a> &ndash; Upgrade plexus-utils 3.1.0</li>
<li><a href="https://issues.apache.org/jira/browse/MINVOKER-238">MINVOKER-238</a> &ndash; Upgrade maven-invoker to 3.0.1</li>
</ul>


<p>Enjoy,</p>

<p>-The Apache Maven team</p>
</div>

