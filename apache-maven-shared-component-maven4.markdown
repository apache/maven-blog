---
layout: post
title: 'Apache Maven Shared Component: Maven Archiver Version 3.4.0 Released'
date: '2019-02-25T10:25:31+00:00'
permalink: apache-maven-shared-component-maven4
---
<div class="entry-content"><p>The Apache Maven team is pleased to announce the release of the
<a href="http://maven.apache.org/shared/maven-archiver/">Maven Archiver, version 3.4.0</a>.</p>

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
</span><span class='line'>  <span class="nt">&lt;version&gt;</span>3.4.0<span class="nt">&lt;/version&gt;</span>
</span><span class='line'><span class="nt">&lt;/plugin&gt;</span>
</span></code></pre></td></tr></table></div></figure>


<p>You can download the appropriate sources etc. from the <a href="https://maven.apache.org/shared/maven-archiver/download.cgi">download page</a>.</p>

<!-- more -->


<p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317922&amp;version=12344607">Release Notes &ndash; Maven Archiver &ndash; Version 3.4.0</a></p>

<p>Bugs:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-588">MSHARED-588</a> &ndash; User supplied Class-Path entry does not go first</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-782">MSHARED-782</a> &ndash; Deprecated option classpathMavenRepositoryLayout not marked as deprecated in the documentation</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-783">MSHARED-783</a> &ndash; Archiver documentation issue tracker 404</li>
</ul>


<p>New Features:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-787">MSHARED-787</a> &ndash; Add optional buildEnvironment information to the manifest</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-798">MSHARED-798</a> &ndash; Add addDefaultEntries option (true by default)</li>
</ul>


<p>Improvements:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-362">MSHARED-362</a> &ndash; Support removing default manifest entries with Maven Archiver</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-777">MSHARED-777</a> &ndash; Remove deprecated main attributes from generated manifest</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-799">MSHARED-799</a> &ndash; Change &ldquo;Created-By&rdquo; manifest entry value to be reproducible</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-800">MSHARED-800</a> &ndash; Remove Maven version from pom.properties</li>
</ul>


<p>Wishes:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-661">MSHARED-661</a> &ndash; Remove manifest entry &ldquo;Built-By: <username>&rdquo; for reproducible builds</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-796">MSHARED-796</a> &ndash; use java.specification.version instead of java.version in Build-Jdk manifest entry</li>
</ul>


<p>Task:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-797">MSHARED-797</a> &ndash; Move current Build-Jdk manifest entry to Build-Jdk-Spec</li>
</ul>


<p>Dependency upgrade:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-781">MSHARED-781</a> &ndash; Upgrade to Plexus Archiver 4.1.0</li>
</ul>


<p>Enjoy,</p>

<p>-The Apache Maven team</p>
</div>
