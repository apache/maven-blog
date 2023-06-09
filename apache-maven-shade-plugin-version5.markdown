---
layout: post
title: Apache Maven Shade Plugin version 3.2.4 Released
date: '2020-06-04T19:58:22+00:00'
permalink: apache-maven-shade-plugin-version5
---
<div class="entry-content"><p>The Apache Maven team is pleased to announce the release of the <a href="https://maven.apache.org/plugins/maven-shade-plugin/">Apache
Maven Shade Plugin, version 3.2.4</a>.</p>

<p>This plugin provides the capability to package the artifact in an uber-jar,
including its dependencies and to shade &ndash; i.e. rename &ndash; the packages of some of
the dependencies.</p>

<p>You should specify the version in your project&rsquo;s plugin configuration:</p>

<figure class='code'><figcaption><span></span></figcaption><div class="highlight"><table><tr><td class="gutter"><pre class="line-numbers"><span class='line-number'>1</span>
<span class='line-number'>2</span>
<span class='line-number'>3</span>
<span class='line-number'>4</span>
<span class='line-number'>5</span>
</pre></td><td class='code'><pre><code class='xml'><span class='line'><span class="nt">&lt;plugin&gt;</span>
</span><span class='line'>  <span class="nt">&lt;groupId&gt;</span>org.apache.maven.plugins<span class="nt">&lt;/groupId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;artifactId&gt;</span>maven-shade-plugin<span class="nt">&lt;/artifactId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;version&gt;</span>3.2.4<span class="nt">&lt;/version&gt;</span>
</span><span class='line'><span class="nt">&lt;/plugin&gt;</span>
</span></code></pre></td></tr></table></div></figure>


<p>You can download the <a href="https://maven.apache.org/shared/maven-archiver/download.cgi">appropriate sources etc. from the download page</a></p>

<!-- more -->


<p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317921&amp;version=12346981">Release Notes &ndash; Maven Shade Plugin &ndash; Version 3.2.4</a></p>

<ul>
<li><p>Bugs:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MSHADE-363">MSHADE-363</a> &ndash; Breaking change to ResourceTransformer&rsquo;s API</li>
<li><a href="https://issues.apache.org/jira/browse/MSHADE-360">MSHADE-360</a> &ndash; ServicesResourceTransformer.modifyOutputStream swallows IOExceptions</li>
</ul>
</li>
<li><p>Tasks:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MSHADE-365">MSHADE-365</a> &ndash; document Properties transformers available since 3.2.2 in separate table</li>
<li><a href="https://issues.apache.org/jira/browse/MSHADE-364">MSHADE-364</a> &ndash; Don&rsquo;t log as duplicate resource handled by a transformer</li>
</ul>
</li>
</ul>


<p>Enjoy,</p>

<p>-The Apache Maven team</p>
</div>
