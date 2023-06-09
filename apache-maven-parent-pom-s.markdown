---
layout: post
title: Apache Maven Parent POM's Version 33 Released
date: '2018-09-22T10:54:27+00:00'
permalink: apache-maven-parent-pom-s
---
<div class="entry-content"><p>The Apache Maven team is pleased to announce the release of the
<a href="https://maven.apache.org/pom/maven/">Maven Parent POMs Version 33</a></p>

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
</span><span class='line'>   <span class="nt">&lt;version&gt;</span>33<span class="nt">&lt;/version&gt;</span>
</span><span class='line'><span class="nt">&lt;/parent&gt;</span>
</span></code></pre></td></tr></table></div></figure>


<p>You can download the appropriate sources etc. from the download page:</p>

<p><a href="https://maven.apache.org/pom/maven/download.html">https://maven.apache.org/pom/maven/download.html</a></p>

<!-- more -->


<p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12311250&amp;version=12343766">Release Notes &ndash; Apache Maven Parent POM &ndash; Version 33</a></p>

<p>Bug:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MPOM-202">MPOM-202</a> &ndash; Links to nabble archive only work with http</li>
</ul>


<p>Improvement:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MPOM-203">MPOM-203</a> &ndash; Links to mailing list will not open mail</li>
</ul>


<p>Wish:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MPOM-197">MPOM-197</a> &ndash; Remove deprecated plexus-maven-plugin from pluginManagement</li>
</ul>


<p>Tasks:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MPOM-199">MPOM-199</a> &ndash; remove Archetypes parent POM from menu</li>
<li><a href="https://issues.apache.org/jira/browse/MPOM-201">MPOM-201</a> &ndash; configure m2e lifecyle-mapping to ignore rat:check</li>
<li><a href="https://issues.apache.org/jira/browse/MPOM-206">MPOM-206</a> &ndash; use sha512 instead of sha1 for source release distribution</li>
</ul>


<p>Dependency upgrade:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MPOM-198">MPOM-198</a> &ndash; Update plexus-utils to 3.1.0 for Doxia Tools</li>
</ul>


<p>Enjoy,
&ndash; The Apache Maven Team</p>
</div>
