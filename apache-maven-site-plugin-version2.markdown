---
layout: post
title: Apache Maven Site Plugin, version 3.9.0 Released
date: '2020-03-10T22:13:14+00:00'
permalink: apache-maven-site-plugin-version2
---
<div class="entry-content"><p>The Apache Maven team is pleased to announce the release of the
<a href="https://maven.apache.org/plugins/maven-site-plugin/">Apache Maven Site Plugin, version 3.9.0</a>.</p>

<p>The Site Plugin is used to generate a site for the project. The generated site
also includes the project&rsquo;s reports that were configured in the POM.</p>

<p>You can download the appropriate sources etc. from the download page:</p>

<p><a href="https://maven.apache.org/plugins/maven-site-plugin/download.cgi">https://maven.apache.org/plugins/maven-site-plugin/download.cgi</a></p>

<figure class='code'><figcaption><span></span></figcaption><div class="highlight"><table><tr><td class="gutter"><pre class="line-numbers"><span class='line-number'>1</span>
<span class='line-number'>2</span>
<span class='line-number'>3</span>
<span class='line-number'>4</span>
<span class='line-number'>5</span>
</pre></td><td class='code'><pre><code class='xml'><span class='line'><span class="nt">&lt;plugin&gt;</span>
</span><span class='line'>  <span class="nt">&lt;groupId&gt;</span>org.apache.maven.plugins<span class="nt">&lt;/groupId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;artifactId&gt;</span>maven-site-plugin<span class="nt">&lt;/artifactId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;version&gt;</span>3.9.0<span class="nt">&lt;/version&gt;</span>
</span><span class='line'><span class="nt">&lt;/plugin&gt;</span>
</span></code></pre></td></tr></table></div></figure>


<!-- more -->


<p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317923&amp;version=12345725">Release Notes &ndash; Maven Site Plugin &ndash; Version 3.9.0</a></p>

<ul>
<li><p>Bugs:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MSITE-847">MSITE-847</a> &ndash; &ldquo;$prerequisiteMavenVersion&rdquo; text in plugin&rsquo;s documentation</li>
<li><a href="https://issues.apache.org/jira/browse/MSITE-853">MSITE-853</a> &ndash; Upgrade Doxia to 1.9.1 to have Markdown <code>code</code> and &#8220;` support</li>
</ul>
</li>
<li><p>New Feature:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MSITE-851">MSITE-851</a> &ndash; Reproducible Builds: make entries in output jar files reproducible (order + timestamp)</li>
</ul>
</li>
<li><p>Improvements:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MSITE-852">MSITE-852</a> &ndash; Upgrade Doxia Site Renderer to 1.9.2 to remove Struts dependencies</li>
<li><a href="https://issues.apache.org/jira/browse/MSITE-855">MSITE-855</a> &ndash; make build Reproducible</li>
</ul>
</li>
</ul>


<p>Enjoy,</p>

<p>-The Apache Maven team</p>
</div>
