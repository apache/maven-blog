---
layout: post
title: Apache Parent POM's Version 34 Released
date: '2020-02-03T20:04:11+00:00'
permalink: apache-parent-pom-s-version
---
<div class="entry-content"><p>The Apache Maven team is pleased to announce the release of the
<a href="https://maven.apache.org/pom/maven/">Maven Parent POMs Version 34</a></p>

<p>Maven Parent POMs include <a href="https://maven.apache.org/pom/maven/">Maven Parent POM</a>
 itself, but also <a href="https://maven.apache.org/pom/maven/maven-plugins/">Maven Plugins Parent POM</a>,
<a href="https://maven.apache.org/pom/maven/maven-shared-components/">Maven Shared Components Parent POM</a>,
<a href="https://maven.apache.org/pom/maven/maven-skins/">Maven Skins Parent POM</a> and
Maven Doxia Tools Parent POM.</p>

<p><a href="https://maven.apache.org/pom/maven/">https://maven.apache.org/pom/maven/</a></p>

<p>You should specify the version in your project as parent like the following:</p>

<figure class='code'><figcaption><span></span></figcaption><div class="highlight"><table><tr><td class="gutter"><pre class="line-numbers"><span class='line-number'>1</span>
<span class='line-number'>2</span>
<span class='line-number'>3</span>
<span class='line-number'>4</span>
<span class='line-number'>5</span>
</pre></td><td class='code'><pre><code class='xml'><span class='line'><span class="nt">&lt;parent&gt;</span>
</span><span class='line'>   <span class="nt">&lt;groupId&gt;</span>org.apache.maven<span class="nt">&lt;/groupId&gt;</span>
</span><span class='line'>   <span class="nt">&lt;artifactId&gt;</span>maven-parent<span class="nt">&lt;/artifactId&gt;</span>
</span><span class='line'>   <span class="nt">&lt;version&gt;</span>34<span class="nt">&lt;/version&gt;</span>
</span><span class='line'><span class="nt">&lt;/parent&gt;</span>
</span></code></pre></td></tr></table></div></figure>


<p>You can download the appropriate sources etc. from the download page:</p>

<p><a href="https://maven.apache.org/pom/maven/download.html">https://maven.apache.org/pom/maven/download.html</a></p>

<!-- more -->


<p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12311250&amp;version=12343766">Release Notes &ndash; Apache Maven Parent POM &ndash; Version 34</a></p>

<ul>
<li><p>Bugs:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MPOM-221">MPOM-221</a> &ndash; All Links for Diff produce Forbidden</li>
<li><a href="https://issues.apache.org/jira/browse/MPOM-235">MPOM-235</a> &ndash; Google Custom Search broken</li>
</ul>
</li>
<li><p>New Feature:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MPOM-223">MPOM-223</a> &ndash; Introduce parent for extensions</li>
</ul>
</li>
<li><p>Improvements:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MPOM-216">MPOM-216</a> &ndash; Update java minimum version to 7</li>
<li><a href="https://issues.apache.org/jira/browse/MPOM-226">MPOM-226</a> &ndash; Ignore .asf.yaml for license check in apache-rat-plugin</li>
<li><a href="https://issues.apache.org/jira/browse/MPOM-230">MPOM-230</a> &ndash; Remove maven-report</li>
</ul>
</li>
<li><p>Task:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MPOM-217">MPOM-217</a> &ndash; remove plexus javadoc taglet configuration</li>
</ul>
</li>
<li><p>Dependency upgrades:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MPOM-212">MPOM-212</a> &ndash; upgrade plexus-component-metadata to 2.0.0 to get reproducible plexus/components.xml</li>
<li><a href="https://issues.apache.org/jira/browse/MPOM-234">MPOM-234</a> &ndash; Upgrade apache-rat-plugin to 0.13</li>
</ul>
</li>
</ul>


<p>Enjoy,
&ndash; The Apache Maven Team</p>
</div>
