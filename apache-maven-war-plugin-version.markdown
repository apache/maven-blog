---
layout: post
title: Apache Maven WAR Plugin Version 3.2.1 Released
date: '2018-05-13T10:14:44+00:00'
permalink: apache-maven-war-plugin-version
---
<div class="entry-content"><p>The Apache Maven team is pleased to announce the release of the
<a href="http://maven.apache.org/plugins/maven-war-plugin/">Apache Maven WAR Plugin, version 3.2.1</a>.</p>

<p>The WAR Plugin is responsible for collecting all artifact dependencies, classes
and resources of the web application and packaging them into a web application
archive.</p>

<p>You should specify the version in your project&rsquo;s plugin configuration:</p>

<figure class='code'><figcaption><span></span></figcaption><div class="highlight"><table><tr><td class="gutter"><pre class="line-numbers"><span class='line-number'>1</span>
<span class='line-number'>2</span>
<span class='line-number'>3</span>
<span class='line-number'>4</span>
<span class='line-number'>5</span>
</pre></td><td class='code'><pre><code class='xml'><span class='line'><span class="nt">&lt;plugin&gt;</span>
</span><span class='line'>  <span class="nt">&lt;groupId&gt;</span>org.apache.maven.plugins<span class="nt">&lt;/groupId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;artifactId&gt;</span>maven-war-plugin<span class="nt">&lt;/artifactId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;version&gt;</span>3.2.1<span class="nt">&lt;/version&gt;</span>
</span><span class='line'><span class="nt">&lt;/plugin&gt;</span>
</span></code></pre></td></tr></table></div></figure>


<p>You can download the appropriate sources etc. from the <a href="https://maven.apache.org/plugins/maven-war-plugin/download.cgi">download page</a>.</p>

<p>Important Note:</p>

<ul>
<li>Maven 3.X only</li>
<li>JDK 7 minimum requirement</li>
</ul>


<!-- more -->


<p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12318121&amp;version=12341729">Release Notes &ndash; Maven WAR Plugin &ndash; Version 3.1.0</a></p>

<p>Improvement:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MWAR-412">MWAR-412</a> &ndash; Upgrade parent to 31</li>
</ul>


<p>Task:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MWAR-401">MWAR-401</a> &ndash; Upgrade the WAR lifecycle to use the maven-compiler-plugin 3.7.0</li>
</ul>


<p>Dependency upgrades:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MWAR-413">MWAR-413</a> &ndash; Upgrade xstream to 1.4.10</li>
<li><a href="https://issues.apache.org/jira/browse/MWAR-414">MWAR-414</a> &ndash; Upgrade mave-surefire/failsafe-plugin 2.21.0</li>
<li><a href="https://issues.apache.org/jira/browse/MWAR-416">MWAR-416</a> &ndash; Upgrade plexus-archiver to 3.6.0</li>
</ul>


<p>Enjoy,</p>

<p>-The Apache Maven team</p>
</div>
