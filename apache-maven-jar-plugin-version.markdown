---
layout: post
title: Apache Maven Jar Plugin Version 3.1.0
date: '2018-04-10T15:47:06+00:00'
permalink: apache-maven-jar-plugin-version
---
<div class="entry-content"><p>The Apache Maven team is pleased to announce the release of the
<a href="http://maven.apache.org/plugins/maven-jar-plugin/">Apache Maven Jar Plugin, version 3.1.0</a>.</p>

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
</span><span class='line'>  <span class="nt">&lt;version&gt;</span>3.1.0<span class="nt">&lt;/version&gt;</span>
</span><span class='line'><span class="nt">&lt;/plugin&gt;</span>
</span></code></pre></td></tr></table></div></figure>




<!-- more -->


<p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317526&amp;version=12342349">Release Notes &ndash; Maven JAR Plugin &ndash; Version 3.1.0</a></p>

<p>Bugs:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MJAR-221">MJAR-221</a> &ndash; Link to wiki page should be removed now that Codehaus is shut down</li>
<li><a href="https://issues.apache.org/jira/browse/MJAR-237">MJAR-237</a> &ndash; Navigation link &ldquo;Creating an Executable JAR File&rdquo; is wrong.</li>
<li><a href="https://issues.apache.org/jira/browse/MJAR-240">MJAR-240</a> &ndash; maven-jar-plugin index.html &ndash; bad links in left column Examples section</li>
<li><a href="https://issues.apache.org/jira/browse/MJAR-245">MJAR-245</a> &ndash; Additional attached jar: role of classifier</li>
<li><a href="https://issues.apache.org/jira/browse/MJAR-249">MJAR-249</a> &ndash; Get Build working on JDK 10</li>
</ul>


<p>Improvements:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MJAR-235">MJAR-235</a> &ndash; Update life cycle bound plugin versions</li>
<li><a href="https://issues.apache.org/jira/browse/MJAR-236">MJAR-236</a> &ndash; Keep maven-compiler-plugin to 3.5.1 based on JDK9 issues</li>
</ul>


<p>Dependency upgrades:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MJAR-243">MJAR-243</a> &ndash; maven-archiver 3.1.1 to 3.2.0</li>
<li><a href="https://issues.apache.org/jira/browse/MJAR-246">MJAR-246</a> &ndash; Upgrade parent to 31</li>
</ul>


<p>Enjoy,</p>

<ul>
<li>The Apache Maven team</li>
</ul>
