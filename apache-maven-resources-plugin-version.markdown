---
layout: post
title: Apache Maven Resources Plugin Version 3.1.0 Released
date: '2018-05-01T10:14:35+00:00'
permalink: apache-maven-resources-plugin-version
---
<div class="entry-content"><p>The Apache Maven team is pleased to announce the release of the
<a href="http://maven.apache.org/plugins/maven-resources-plugin">Apache Maven Resources Plugin, Version 3.1.0</a>.</p>

<p>The Resources Plugin handles the copying of project resources to the output
directory. There are two different kinds of resources: main resources and test
resources. The difference is that the main resources are the resources
associated to the main source code while the test resources are associated to
the test source code.</p>

<p>Thus, this allows the separation of resources for the main source code and its
unit tests.</p>

<p>Important Note:</p>

<ul>
<li>Maven 3.X only</li>
<li>JDK 7 minimum requirement</li>
</ul>


<p>Reporters for this release:</p>

<ul>
<li>Michel Barret <a href="https://issues.apache.org/jira/browse/MRESOURCES-247">MRESOURCES-247</a></li>
</ul>


<p>You should specify the version in your project&rsquo;s plugin configuration:</p>

<figure class='code'><figcaption><span></span></figcaption><div class="highlight"><table><tr><td class="gutter"><pre class="line-numbers"><span class='line-number'>1</span>
<span class='line-number'>2</span>
<span class='line-number'>3</span>
<span class='line-number'>4</span>
<span class='line-number'>5</span>
</pre></td><td class='code'><pre><code class='xml'><span class='line'><span class="nt">&lt;plugin&gt;</span>
</span><span class='line'>  <span class="nt">&lt;groupId&gt;</span>org.apache.maven.plugins<span class="nt">&lt;/groupId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;artifactId&gt;</span>maven-resources-plugin<span class="nt">&lt;/artifactId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;version&gt;</span>3.1.0<span class="nt">&lt;/version&gt;</span>
</span><span class='line'><span class="nt">&lt;/plugin&gt;</span>
</span></code></pre></td></tr></table></div></figure>


<p>You can download the appropriate sources etc. from the download page:</p>

<p><a href="https://maven.apache.org/plugins/maven-resources-plugin/download.cgi">https://maven.apache.org/plugins/maven-resources-plugin/download.cgi</a></p>

<!-- more -->


<p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317827&amp;version=12336059">Release Notes &ndash; Apache Maven Resources Version 3.1.0</a></p>

<p>Bug:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MRESOURCES-242">MRESOURCES-242</a> &ndash; Fix integration test include-git-ignore</li>
</ul>


<p>Improvement:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MRESOURCES-247">MRESOURCES-247</a> &ndash; Improve WARNING message about encoding.</li>
</ul>


<p>Tasks:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MRESOURCES-243">MRESOURCES-243</a> &ndash; Upgrade mave-surefire/failsafe-plugin 2.20.1</li>
<li><a href="https://issues.apache.org/jira/browse/MRESOURCES-245">MRESOURCES-245</a> &ndash; Upgrade to JDK 7 minimum.</li>
</ul>


<p>Dependency upgrades:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MRESOURCES-241">MRESOURCES-241</a> &ndash; Upgrade parent to 31</li>
<li><a href="https://issues.apache.org/jira/browse/MRESOURCES-244">MRESOURCES-244</a> &ndash; Upgrade plexus-utils 3.1.0</li>
<li><a href="https://issues.apache.org/jira/browse/MRESOURCES-248">MRESOURCES-248</a> &ndash; Add documentation information for GitHub</li>
</ul>


<p>Enjoy,</p>

<p>-The Apache Maven team</p>
</div>
