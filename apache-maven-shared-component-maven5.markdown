---
layout: post
title: 'Apache Maven Shared Component: Maven Verifier Version 1.7.0 Released'
date: '2020-03-31T16:48:45+00:00'
permalink: apache-maven-shared-component-maven5
---
<div class="entry-content"><p>The Apache Maven team is pleased to announce the release of the
<a href="https://maven.apache.org/shared/maven-verifier/">Maven Verifier, version 1.7.0</a>.</p>

<p>This library provides a test harness for Maven integration tests.</p>

<p>You should specify the version in your project&rsquo;s dependency configuration:</p>

<figure class='code'><figcaption><span></span></figcaption><div class="highlight"><table><tr><td class="gutter"><pre class="line-numbers"><span class='line-number'>1</span>
<span class='line-number'>2</span>
<span class='line-number'>3</span>
<span class='line-number'>4</span>
<span class='line-number'>5</span>
</pre></td><td class='code'><pre><code class='xml'><span class='line'><span class="nt">&lt;dependency&gt;</span>
</span><span class='line'>    <span class="nt">&lt;groupId&gt;</span>org.apache.maven.shared<span class="nt">&lt;/groupId&gt;</span>
</span><span class='line'>    <span class="nt">&lt;artifactId&gt;</span>maven-verifier<span class="nt">&lt;/artifactId&gt;</span>
</span><span class='line'>    <span class="nt">&lt;version&gt;</span>1.7.0<span class="nt">&lt;/version&gt;</span>
</span><span class='line'><span class="nt">&lt;/dependency&gt;</span>
</span></code></pre></td></tr></table></div></figure>


<p>You can download the appropriate sources etc. from the <a href="https://maven.apache.org/shared/maven-verifier/download.html">download page</a>.</p>

<!-- more -->


<p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317922&amp;version=12332949">Release Notes &ndash; Maven Verifier &ndash; Version 1.7.0</a></p>

<ul>
<li><p>Bugs:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-723">MSHARED-723</a> &ndash; Upgrade mave-surefire/failsafe-plugin 2.21.0</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-769">MSHARED-769</a> &ndash; FileNotFoundException not thrown for unknown property file</li>
</ul>
</li>
<li><p>New Feature:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-855">MSHARED-855</a> &ndash; Support calling maven wrapper</li>
</ul>
</li>
<li><p>Improvements:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-547">MSHARED-547</a> &ndash; Support colorized output checks (ignore ANSI escape codes)</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-768">MSHARED-768</a> &ndash; Require Java 7</li>
</ul>
</li>
<li><p>Dependency upgrades:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-689">MSHARED-689</a> &ndash; Upgrade parent to 31</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-694">MSHARED-694</a> &ndash; Upgrade JUnit 3.8.2 to 4.12</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-734">MSHARED-734</a> &ndash; Upgrade maven-shared-utils to 3.2.1</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-751">MSHARED-751</a> &ndash; Upgrade maven-shared-components parent to version 32</li>
</ul>
</li>
</ul>


<p>Enjoy,</p>

<p>-The Apache Maven team</p>
</div>
