---
layout: post
title: Apache Maven PMD Plugin Version 3.12.0 Released
date: '2019-04-23T17:27:44+00:00'
permalink: apache-maven-pmd-plugin-version1
---
<div class="entry-content"><p>The Maven team is pleased to announce the release of the
<a href="http://maven.apache.org/plugins/maven-pmd-plugin/">Apache Maven PMD Plugin, version 3.12.0</a></p>

<p>A Maven plugin for the PMD toolkit, that produces a report on both code rule
violations and detected copy and paste fragments, as well as being able to fail
the build based on these metrics.</p>

<p>You can download the appropriate sources etc. from the
<a href="https://maven.apache.org/plugins/maven-pmd-plugin/download.cgi">download page</a>.</p>

<p>You should specify the version in your project&rsquo;s plugin configuration:</p>

<figure class='code'><figcaption><span></span></figcaption><div class="highlight"><table><tr><td class="gutter"><pre class="line-numbers"><span class='line-number'>1</span>
<span class='line-number'>2</span>
<span class='line-number'>3</span>
<span class='line-number'>4</span>
<span class='line-number'>5</span>
</pre></td><td class='code'><pre><code class='xml'><span class='line'><span class="nt">&lt;plugin&gt;</span>
</span><span class='line'>  <span class="nt">&lt;groupId&gt;</span>org.apache.maven.plugins<span class="nt">&lt;/groupId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;artifactId&gt;</span>maven-pmd-plugin<span class="nt">&lt;/artifactId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;version&gt;</span>3.12.0<span class="nt">&lt;/version&gt;</span>
</span><span class='line'><span class="nt">&lt;/plugin&gt;</span>
</span></code></pre></td></tr></table></div></figure>




<!-- more -->


<p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317621&amp;version=12344380">Release Notes &ndash; Apache Maven PMD Plugin &ndash; Version 3.12.0</a></p>

<p>Bugs:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MPMD-277">MPMD-277</a> &ndash; Plugin tries to download local submodules from repo</li>
</ul>


<p>New Features:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MPMD-280">MPMD-280</a> &ndash; Support targetJdk 12</li>
<li><a href="https://issues.apache.org/jira/browse/MPMD-281">MPMD-281</a> &ndash; Display found violations grouped by priority</li>
</ul>


<p>Improvements:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MPMD-279">MPMD-279</a> &ndash; Improve documentation of maxAllowedViolations</li>
<li><a href="https://issues.apache.org/jira/browse/MPMD-282">MPMD-282</a> &ndash; Add rule name to HTML report</li>
</ul>


<p>Dependency upgrades:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MPMD-275">MPMD-275</a> &ndash; Upgrade to PMD 6.13.0</li>
<li><a href="https://issues.apache.org/jira/browse/MPMD-284">MPMD-284</a> &ndash; Upgrade parent to 33</li>
</ul>


<p>Enjoy,</p>

<p>-The Maven team</p>
</div>
