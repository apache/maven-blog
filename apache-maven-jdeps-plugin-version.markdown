---
layout: post
title: Apache Maven JDeps Plugin, version 3.1.1
date: '2018-03-01T17:09:08+00:00'
permalink: apache-maven-jdeps-plugin-version
---
<div class="entry-content"><p>The Apache Maven team is pleased to announce the release of the
<a href="http://maven.apache.org/plugins/maven-jdeps-plugin/">Apache Maven JDeps Plugin, version 3.1.1</a>.</p>

<p>The JDeps Plugin uses the jdeps tool to analyze classes for internal API calls.
For more information about the standard jdeps tool, please refer to
<a href="https://wiki.openjdk.java.net/display/JDK8/Java+Dependency+Analysis+Tool">https://wiki.openjdk.java.net/display/JDK8/Java+Dependency+Analysis+Tool</a></p>

<p>You should specify the version in your project&rsquo;s plugin configuration:</p>

<figure class='code'><figcaption><span></span></figcaption><div class="highlight"><table><tr><td class="gutter"><pre class="line-numbers"><span class='line-number'>1</span>
<span class='line-number'>2</span>
<span class='line-number'>3</span>
<span class='line-number'>4</span>
<span class='line-number'>5</span>
</pre></td><td class='code'><pre><code class='xml'><span class='line'><span class="nt">&lt;plugin&gt;</span>
</span><span class='line'>  <span class="nt">&lt;groupId&gt;</span>org.apache.maven.plugins<span class="nt">&lt;/groupId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;artifactId&gt;</span>maven-jdeps-plugin<span class="nt">&lt;/artifactId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;version&gt;</span>3.1.1<span class="nt">&lt;/version&gt;</span>
</span><span class='line'><span class="nt">&lt;/plugin&gt;</span>
</span></code></pre></td></tr></table></div></figure>


<p><a href="http://maven.apache.org/plugins/maven-jdeps-plugin/download.cgi">You can download the appropriate sources etc. from the download page.</a>.</p>

<!-- more -->


<p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12319223&amp;version=12341552&amp;styleName=Text">Release Notes Maven JDeps Plugin Release Notes Version 3.1.1</a></p>

<p>Bugs:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MJDEPS-10">MJDEPS-10</a> &ndash; Error: unknown option: -M while using module option of maven-jdeps-plugin</li>
</ul>


<p>New Features:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MJDEPS-9">MJDEPS-9</a> &ndash; Introduce failOnWarning as a named property</li>
<li><a href="https://issues.apache.org/jira/browse/MJDEPS-11">MJDEPS-11</a> &ndash; Introduce &mdash;multi-release option</li>
</ul>


<p>Improvement:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MJDEPS-12">MJDEPS-12</a> &ndash; Add support for the &lsquo;-package&rsquo; options</li>
</ul>


<p>Dependency upgrade:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MJDEPS-8">MJDEPS-8</a> &ndash; Upgrade plexus-utils to version 3.1.0</li>
<li><a href="https://issues.apache.org/jira/browse/MJDEPS-13">MJDEPS-13</a> &ndash; Upgrade parent to 31</li>
</ul>


<p>Enjoy,</p>

<p>-The Apache Maven team</p>
</div>
