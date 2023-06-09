---
layout: post
title: 'Apache Maven Shared Component: Maven Dependency Analyzer Version 1.9 Released'
date: '2018-03-29T15:21:28+00:00'
permalink: apache-maven-shared-component-maven1
---
<div class="entry-content"><p>The Apache Maven team is pleased to announce the release of the
<a href="http://maven.apache.org/shared/maven-dependency-analyzer/">Apache Maven Shared Component: Maven Dependency Analyzer Version 1.9</a></p>

<p>Analyzes the dependencies of a project for undeclared or unused artifacts.</p>

<p>You should specify the version in your project&rsquo;s dependency list:</p>

<figure class='code'><figcaption><span></span></figcaption><div class="highlight"><table><tr><td class="gutter"><pre class="line-numbers"><span class='line-number'>1</span>
<span class='line-number'>2</span>
<span class='line-number'>3</span>
<span class='line-number'>4</span>
<span class='line-number'>5</span>
</pre></td><td class='code'><pre><code class='xml'><span class='line'><span class="nt">&lt;dependency&gt;</span>
</span><span class='line'>  <span class="nt">&lt;groupId&gt;</span>org.apache.maven.shared<span class="nt">&lt;/groupId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;artifactId&gt;</span>maven-dependency-analyzer<span class="nt">&lt;/artifactId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;version&gt;</span>1.9<span class="nt">&lt;/version&gt;</span>
</span><span class='line'><span class="nt">&lt;/dependency&gt;</span>
</span></code></pre></td></tr></table></div></figure>




<!-- more -->


<p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317922&amp;version=12342557">Release Notes &ndash; Maven Dependency Analzyer Version 1.9</a></p>

<p>Bug:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-710">MSHARED-710</a> &ndash; JDK 9 / 10 Issue &ndash; Unknown constant pool type</li>
</ul>


<p>Dependency upgrades:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-707">MSHARED-707</a> &ndash; Upgrade parent to 31</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-708">MSHARED-708</a> &ndash; Upgrade org.ow2.asm:asm:6.0 to 6.1 JDK 10 issues</li>
</ul>


<p>Enjoy,</p>

<p>-The Apache Maven team</p>
</div>
