---
layout: post
title: Apache Maven Plugin Tools Version 3.5.2 Released
date: '2018-05-26T16:45:19+00:00'
permalink: apache-maven-plugin-tools-version
---
<div class="entry-content"><p>The Apache Maven team is pleased to announce the release of the
<a href="http://maven.apache.org/plugin-tools/">Apache Maven Plugin Tools, version 3.5.2</a>.</p>

<p>The Maven Plugin Tools contains the necessary tools to generate<br/>
rebarbative content like descriptor, help and documentation. In addition,<br/>
it provides tools to write Maven Plugins in scripting languages like Ant<br/>
or Beanshell.</p>

<p>The Maven Plugin Plugin is used to create a Maven plugin descriptor for<br/>
any Mojo&rsquo;s found in the source tree, to include in the JAR. It is also<br/>
used to generate report files for the Mojos as well as for updating the<br/>
plugin registry, the artifact metadata and generating a generic help goal.</p>

<ul>
<li><a href="https://maven.apache.org/plugin-tools/">https://maven.apache.org/plugin-tools/</a></li>
<li><a href="https://maven.apache.org/plugin-tools/maven-plugin-plugin/">https://maven.apache.org/plugin-tools/maven-plugin-plugin/</a></li>
</ul>


<p>You should specify the version in your project&rsquo;s plugin configuration:</p>

<figure class='code'><figcaption><span></span></figcaption><div class="highlight"><table><tr><td class="gutter"><pre class="line-numbers"><span class='line-number'>1</span>
<span class='line-number'>2</span>
<span class='line-number'>3</span>
<span class='line-number'>4</span>
<span class='line-number'>5</span>
</pre></td><td class='code'><pre><code class='xml'><span class='line'><span class="nt">&lt;plugin&gt;</span>
</span><span class='line'>  <span class="nt">&lt;groupId&gt;</span>org.apache.maven.plugins<span class="nt">&lt;/groupId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;artifactId&gt;</span>maven-plugin-plugin<span class="nt">&lt;/artifactId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;version&gt;</span>3.5.2<span class="nt">&lt;/version&gt;</span>
</span><span class='line'><span class="nt">&lt;/plugin&gt;</span>
</span></code></pre></td></tr></table></div></figure>


<p>You can download the appropriate sources etc. from the <a href="https://maven.apache.org/plugins-tools/download.cgi">download page</a>.</p>

<!-- more -->


<p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317820&amp;version=12342545&amp;styleName=Text">Release Notes &ndash; Maven Plugin Tools &ndash; Version 3.5.2</a></p>

<p>Dependency upgrades:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MPLUGIN-333">MPLUGIN-333</a> &ndash; Upgrade parent to 31</li>
<li><a href="https://issues.apache.org/jira/browse/MPLUGIN-334">MPLUGIN-334</a> &ndash; Upgrade mave-surefire/failsafe-plugin 2.21.0</li>
<li><a href="https://issues.apache.org/jira/browse/MPLUGIN-335">MPLUGIN-335</a> &ndash; Support JDK 10 for plugin generation: upgrade asm</li>
<li><a href="https://issues.apache.org/jira/browse/MPLUGIN-338">MPLUGIN-338</a> &ndash; Upgrade plexus-archiver to 3.6.0</li>
</ul>


<p>Enjoy,</p>

<p>-The Apache Maven team</p>
</div>
