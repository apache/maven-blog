---
layout: post
title: Apache Maven PMD Plugin Version 3.10.0 Released
date: '2018-06-07T06:17:06+00:00'
permalink: apache-maven-pmd-plugin-version
---
<div class="entry-content"><p>The Maven team is pleased to announce the release of the
<a href="http://maven.apache.org/plugins/maven-pmd-plugin/">Apache Maven PMD Plugin, version 3.10.0</a></p>

<p>A Maven plugin for the PMD toolkit, that produces a report on both code rule
violations and detected copy and paste fragments, as well as being able to fail
the build based on these metrics.</p>

<p>You can download the appropriate sources etc. from the download page:</p>

<p><a href="https://maven.apache.org/plugins/maven-pmd-plugin/download.cgi">https://maven.apache.org/plugins/maven-pmd-plugin/download.cgi</a></p>

<p>You should specify the version in your project&rsquo;s plugin configuration:</p>

<figure class='code'><figcaption><span></span></figcaption><div class="highlight"><table><tr><td class="gutter"><pre class="line-numbers"><span class='line-number'>1</span>
<span class='line-number'>2</span>
<span class='line-number'>3</span>
<span class='line-number'>4</span>
<span class='line-number'>5</span>
</pre></td><td class='code'><pre><code class='xml'><span class='line'><span class="nt">&lt;plugin&gt;</span>
</span><span class='line'>  <span class="nt">&lt;groupId&gt;</span>org.apache.maven.plugins<span class="nt">&lt;/groupId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;artifactId&gt;</span>maven-pmd-plugin<span class="nt">&lt;/artifactId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;version&gt;</span>3.10.0<span class="nt">&lt;/version&gt;</span>
</span><span class='line'><span class="nt">&lt;/plugin&gt;</span>
</span></code></pre></td></tr></table></div></figure>




<!-- more -->


<p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?version=12342689&amp;styleName=Text&amp;projectId=12317621">Release Notes &ndash; Apache Maven PMD Plugin &ndash; Version 3.9</a></p>

<p>Bugs:</p>

<ul>
<li>[MPMD-253] &ndash; PMD links to java Xref fail in aggregated report</li>
<li>[MPMD-257] &ndash; Allow to disable analysisCache completely, avoid warnings</li>
<li>[MPMD-258] &ndash; PMD output multiplies with every module in multi module projects</li>
<li>[MPMD-259] &ndash; FileNotFoundException with analysisCache=true, includeTests=true and no test classes</li>
</ul>


<p>New Feature:</p>

<ul>
<li>[MPMD-256] &ndash; Add maxAllowedViolations property for PMD</li>
</ul>


<p>Improvements:</p>

<ul>
<li>[MPMD-261] &ndash; Upgrade to PMD 6.4.0</li>
<li>[MPMD-263] &ndash; Add documentation information for GitHub</li>
<li>[MPMD-264] &ndash; Add rule priority to HTML report</li>
</ul>


<p>Dependency upgrades:</p>

<ul>
<li>[MPMD-252] &ndash; Upgrade parent to 31</li>
<li>[MPMD-262] &ndash; Upgrade maven-surefire/failsafe-plugin 2.21.0</li>
</ul>


<p>Enjoy,</p>

<p>-The Maven team</p>
</div>
