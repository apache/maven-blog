---
layout: post
title: 'Apache Maven Shared Component: Maven Archiver Version 3.3.0 Released'
date: '2018-11-24T07:40:35+00:00'
permalink: apache-maven-shared-component-maven2
---
<div class="entry-content"><p>The Apache Maven team is pleased to announce the release of the
<a href="http://maven.apache.org/shared/maven-archiver/">Maven Archiver, version 3.3.0</a>.</p>

<p>The Maven Archiver is mainly used by plugins to handle packaging. The version
numbers referenced in the Since column on this page are the version of the
Maven Archiver component &ndash; not for any specific plugin. To see which version of
Maven Archiver a plugin uses, go to the site for that plugin.</p>

<p>You should specify the version in your project&rsquo;s dependency configuration:</p>

<figure class='code'><figcaption><span></span></figcaption><div class="highlight"><table><tr><td class="gutter"><pre class="line-numbers"><span class='line-number'>1</span>
<span class='line-number'>2</span>
<span class='line-number'>3</span>
<span class='line-number'>4</span>
<span class='line-number'>5</span>
</pre></td><td class='code'><pre><code class='xml'><span class='line'><span class="nt">&lt;dependency&gt;</span>
</span><span class='line'>  <span class="nt">&lt;groupId&gt;</span>org.apache.maven.shared<span class="nt">&lt;/groupId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;artifactId&gt;</span>maven-archiver<span class="nt">&lt;/artifactId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;version&gt;</span>3.3.0<span class="nt">&lt;/version&gt;</span>
</span><span class='line'><span class="nt">&lt;/plugin&gt;</span>
</span></code></pre></td></tr></table></div></figure>


<p>You can download the appropriate sources etc. from the <a href="https://maven.apache.org/shared/maven-archiver/download.cgi">download page</a>.</p>

<p>Important Notes since Version 3.3.0:</p>

<ul>
<li>Maven 3.X only</li>
<li>JDK 7 minimum requirement</li>
</ul>


<!-- more -->


<p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317922&amp;version=12341347">Release Notes &ndash; Maven Archiver &ndash; Version 3.3.0</a></p>

<p>Improvement:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-773">MSHARED-773</a> &ndash; Fail on invalid &lsquo;Automatic-Module-Name&rsquo; in MANIFEST</li>
</ul>


<p>Dependency upgrades:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-668">MSHARED-668</a> &ndash; plexus-utils 3.0.24 to 3.1.0</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-669">MSHARED-669</a> &ndash; Upgrade plexus-interpolation to 1.24</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-686">MSHARED-686</a> &ndash; Upgrade parent to 31</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-721">MSHARED-721</a> &ndash; Upgrade maven-shared-utils to 3.2.1</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-726">MSHARED-726</a> &ndash; Upgrade plexus-archiver to 3.6.0</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-727">MSHARED-727</a> &ndash; Upgrade mave-surefire/failsafe-plugin 2.21.0</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-747">MSHARED-747</a> &ndash; Upgrade maven-plugins parent to version 32</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-774">MSHARED-774</a> &ndash; Upgrade maven-plugins parent to version 33</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-775">MSHARED-775</a> &ndash; Upgrade plexus-interpolation to 1.25</li>
</ul>


<p>Enjoy,</p>

<p>-The Apache Maven team</p>
</div>
