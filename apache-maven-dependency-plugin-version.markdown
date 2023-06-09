---
layout: post
title: Apache Maven Dependency Plugin Version 3.1.0 Released
date: '2018-04-06T16:36:22+00:00'
permalink: apache-maven-dependency-plugin-version
---
<div class="entry-content"><p>The Apache Maven team is pleased to announce the release of the
<a href="http://maven.apache.org/plugins/maven-dependency-plugin/">Apache Maven Dependecy Plugin, version 3.1.0</a>.</p>

<p>The dependency plugin provides the capability to manipulate artifacts. It
can copy and/or unpack artifacts from local or remote repositories to a
specified location.</p>

<p><a href="https://maven.apache.org/plugins/maven-dependency-plugin/">https://maven.apache.org/plugins/maven-dependency-plugin/</a></p>

<p>You should specify the version in your project&rsquo;s plugin configuration:</p>

<figure class='code'><figcaption><span></span></figcaption><div class="highlight"><table><tr><td class="gutter"><pre class="line-numbers"><span class='line-number'>1</span>
<span class='line-number'>2</span>
<span class='line-number'>3</span>
<span class='line-number'>4</span>
<span class='line-number'>5</span>
</pre></td><td class='code'><pre><code class='xml'><span class='line'><span class="nt">&lt;plugin&gt;</span>
</span><span class='line'>    <span class="nt">&lt;groupId&gt;</span>org.apache.maven.plugins<span class="nt">&lt;/groupId&gt;</span>
</span><span class='line'>    <span class="nt">&lt;artifactId&gt;</span>maven-dependency-plugin<span class="nt">&lt;/artifactId&gt;</span>
</span><span class='line'>    <span class="nt">&lt;version&gt;</span>3.1.0<span class="nt">&lt;/version&gt;</span>
</span><span class='line'><span class="nt">&lt;/plugin&gt;</span>
</span></code></pre></td></tr></table></div></figure>


<p></p>

<p>You can download the appropriate sources etc. from the download page:</p>

<p><a href="https://maven.apache.org/plugins/maven-dependency-plugin/download.cgi">https://maven.apache.org/plugins/maven-dependency-plugin/download.cgi</a></p>

<!-- more -->


<p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317227&amp;version=12341595">Release Notes &ndash; Maven Dependency Plugin &ndash; Version 3.1.0</a></p>

<p>Bugs:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MDEP-559">MDEP-559</a> &ndash; Java 9 bytecode cannot be parsed</li>
<li><a href="https://issues.apache.org/jira/browse/MDEP-603">MDEP-603</a> &ndash; dependency:analyze fails on JDK 9 / JDK 10</li>
</ul>


<p>Improvement:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MDEP-605">MDEP-605</a> &ndash; Add documentation information for GitHub</li>
</ul>


<p>Dependency upgrades:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MDEP-584">MDEP-584</a> &ndash; Upgrade plexus-utils to version 3.1.0</li>
<li><a href="https://issues.apache.org/jira/browse/MDEP-585">MDEP-585</a> &ndash; Upgrade plexus-archiver to 3.5.</li>
<li><a href="https://issues.apache.org/jira/browse/MDEP-599">MDEP-599</a> &ndash; Upgrade parent to 31</li>
</ul>


<p>Many thanks to all reporters/contributors/testers of this release.</p>

<p>Reporters:</p>

<ul>
<li>MDEP-559: Ben Alex</li>
</ul>


<p>Testers:</p>

<ul>
<li>Mark Raynsford</li>
</ul>


<p>Enjoy,</p>

<p>-The Apache Maven team</p>
</div>
