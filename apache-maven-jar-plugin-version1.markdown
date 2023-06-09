---
layout: post
title: Apache Maven Jar Plugin Version 3.1.1
date: '2018-12-12T19:22:00+00:00'
permalink: apache-maven-jar-plugin-version1
---
<div class="entry-content"><p>The Apache Maven team is pleased to announce the release of the
<a href="https://maven.apache.org/plugins/maven-jar-plugin/">Apache Maven Jar Plugin, version 3.1.1</a>.</p>

<p>This plugin provides the capability to build jars.</p>

<p>Important Note:</p>

<ul>
<li>Maven 3.X only</li>
<li>JDK 7 minimum requirement</li>
</ul>


<figure class='code'><figcaption><span></span></figcaption><div class="highlight"><table><tr><td class="gutter"><pre class="line-numbers"><span class='line-number'>1</span>
<span class='line-number'>2</span>
<span class='line-number'>3</span>
<span class='line-number'>4</span>
<span class='line-number'>5</span>
</pre></td><td class='code'><pre><code class='xml'><span class='line'><span class="nt">&lt;plugin&gt;</span>
</span><span class='line'>  <span class="nt">&lt;groupId&gt;</span>org.apache.maven.plugins<span class="nt">&lt;/groupId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;artifactId&gt;</span>maven-jar-plugin<span class="nt">&lt;/artifactId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;version&gt;</span>3.1.1<span class="nt">&lt;/version&gt;</span>
</span><span class='line'><span class="nt">&lt;/plugin&gt;</span>
</span></code></pre></td></tr></table></div></figure>




<!-- more -->


<p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317526&amp;version=12343046">Release Notes &ndash; Maven JAR Plugin &ndash; Version 3.1.1</a></p>

<p>Bug:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MJAR-241">MJAR-241</a> &ndash; Jar package does not have a size in ZipEntry</li>
</ul>


<p>Improvement:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MJAR-260">MJAR-260</a> &ndash; Upgrade to Archiver 3.3.0 and add ITs</li>
</ul>


<p>Task:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MJAR-251">MJAR-251</a> &ndash; Add documentation information for GitHub</li>
</ul>


<p>Dependency upgrades:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MJAR-252">MJAR-252</a> &ndash; Upgrade plexus-archiver to 3.6.0</li>
<li><a href="https://issues.apache.org/jira/browse/MJAR-255">MJAR-255</a> &ndash; Upgrade maven-plugins parent to version 32</li>
<li><a href="https://issues.apache.org/jira/browse/MJAR-256">MJAR-256</a> &ndash; Upgrade JUnit to 4.12</li>
<li><a href="https://issues.apache.org/jira/browse/MJAR-261">MJAR-261</a> &ndash; Upgrade plexus-archiver 3.7.0</li>
</ul>


<p>Enjoy,</p>

<ul>
<li>The Apache Maven team</li>
</ul>

</div>
