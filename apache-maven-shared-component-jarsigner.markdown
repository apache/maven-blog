---
layout: post
title: 'Apache Maven Shared Component: Jarsigner, Version 3.0.0 Released'
date: '2018-10-31T21:05:00+00:00'
permalink: apache-maven-shared-component-jarsigner
---
<div class="entry-content"><p>The Apache Maven team is pleased to announce the release of the
<a href="https://maven.apache.org/shared/maven-jarsigner/">Apache Maven Jarsigner, version 3.0.0</a>.</p>

<p>This component provides some utilities to sign/verify jars/files in your Mojos.</p>

<p>You can download the appropriate sources etc. from the
<a href="https://maven.apache.org/shared/maven-jarsigner/download.cgi">download page</a>.</p>

<p>You should specify the component in your pom file like this:</p>

<figure class='code'><figcaption><span></span></figcaption><div class="highlight"><table><tr><td class="gutter"><pre class="line-numbers"><span class='line-number'>1</span>
<span class='line-number'>2</span>
<span class='line-number'>3</span>
<span class='line-number'>4</span>
<span class='line-number'>5</span>
</pre></td><td class='code'><pre><code class='xml'><span class='line'><span class="nt">&lt;dependency&gt;</span>
</span><span class='line'>  <span class="nt">&lt;groupId&gt;</span>org.apache.maven.shared<span class="nt">&lt;/groupId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;artifactId&gt;</span>maven-jarsigner<span class="nt">&lt;/artifactId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;version&gt;</span>3.0.0<span class="nt">&lt;/version&gt;</span>
</span><span class='line'><span class="nt">&lt;/dependency&gt;</span>
</span></code></pre></td></tr></table></div></figure>




<!-- more -->


<p><a href="http://jira.codehaus.org/secure/ReleaseNote.jspa?projectId=11990&amp;version=19865">Release Notes &ndash; Maven Shared Component &ndash; Maven Jarsigner &ndash; Version 3.0.0</a>.</p>

<p>Bug:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-654">MSHARED-654</a> &ndash; Add support of the &ldquo;certchain&rdquo; parameter in JarSigner sign operation</li>
</ul>


<p>Improvements:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-507">MSHARED-507</a> &ndash; Upgrade maven-shared-components parent to version 22</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-508">MSHARED-508</a> &ndash; Upgrade maven-shared-utils to 3.0.0</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-510">MSHARED-510</a> &ndash; Add missing apache-rat-plugin configuration for keystore</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-530">MSHARED-530</a> &ndash; Upgrade maven-shared-components parent to version 30</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-764">MSHARED-764</a> &ndash; Upgrade to JDK 1.7</li>
</ul>


<p>Tasks:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-509">MSHARED-509</a> &ndash; Upgrade Maven 3.X Only JDK 1.6</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-626">MSHARED-626</a> &ndash; Upgrade of &lsquo;maven-shared-utils&rsquo; to 3.2.0.</li>
</ul>


<p>Dependency upgrades:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-736">MSHARED-736</a> &ndash; Upgrade parent to 31</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-739">MSHARED-739</a> &ndash; Upgrade mave-surefire/failsafe-plugin 2.21.0</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-745">MSHARED-745</a> &ndash; Upgrade maven-shared-utils to 3.2.1</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-746">MSHARED-746</a> &ndash; Upgrade junit to junit 4.12</li>
</ul>


<p>Enjoy,</p>

<ul>
<li>The Apache Maven team</li>
</ul>
