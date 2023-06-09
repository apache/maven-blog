---
layout: post
title: Apache Maven Site Plugin Version 3.7.1 Released
date: '2018-04-29T08:46:54+00:00'
permalink: apache-maven-site-plugin-version
---
<div class="entry-content"><p>The Apache Maven team is pleased to announce the release of the
<a href="https://maven.apache.org/plugins/maven-site-plugin/">Apache Maven Site Plugin, version 3.7.1</a>.</p>

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
</span><span class='line'>  <span class="nt">&lt;version&gt;</span>3.7.1<span class="nt">&lt;/version&gt;</span>
</span><span class='line'><span class="nt">&lt;/plugin&gt;</span>
</span></code></pre></td></tr></table></div></figure>



<p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317923&amp;version=12342371&amp;styleName=Text">Release Notes &ndash; Maven Site Plugin &ndash; Version 3.7.1</a></p>

<p>Bugs:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MSITE-806">MSITE-806</a> &ndash; Site generation does not work when no report configured nor Doxia document provided</li>
<li><a href="https://issues.apache.org/jira/browse/MSITE-809">MSITE-809</a> &ndash; Documentation: examples/configuring-reports.html includes invalid XML</li>
<li><a href="https://issues.apache.org/jira/browse/MSITE-812">MSITE-812</a> &ndash; Missing &lsquo;/&rsquo; in log when deploying documentation by site:stage</li>
<li><a href="https://issues.apache.org/jira/browse/MSITE-817">MSITE-817</a> &ndash; inherit edit value in site.xml</li>
<li><a href="https://issues.apache.org/jira/browse/MSITE-818">MSITE-818</a> &ndash; site:run fails to find locale when zh_CN is used</li>
</ul>


<p>Improvements:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MSITE-811">MSITE-811</a> &ndash; Upgrade parent to 31</li>
<li><a href="https://issues.apache.org/jira/browse/MSITE-819">MSITE-819</a> &ndash; improve display of site rendering with locale info</li>
</ul>


<p>Wish:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MSITE-815">MSITE-815</a> &ndash; highlight skin used to render site and documents statistics</li>
</ul>


<p>Tasks:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MSITE-767">MSITE-767</a> &ndash; Revert r1729902 caused by DOXIASITETOOLS-155 and fix ITs as soon as parent POMs and site.xml descriptors have been upgraded</li>
<li><a href="https://issues.apache.org/jira/browse/MSITE-821">MSITE-821</a> &ndash; add documentation on site plugin dependencies</li>
</ul>


<p>Enjoy,</p>

<p>-The Apache Maven team</p>
</div>
