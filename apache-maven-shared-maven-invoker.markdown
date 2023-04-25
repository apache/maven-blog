---
layout: post
title: Apache Maven Shared Maven Invoker Version 3.1.0 Released
date: '2018-06-01T19:03:03+00:00'
permalink: apache-maven-shared-maven-invoker
---
<div class="entry-content"><p>The Apache Maven team is pleased to announce the release of the
<a href="http://maven.apache.org/shared/maven-invoker/">Apache Maven Shared Maven Invoker, version 3.1.0</a></p>

<p>This API is concerned with firing a Maven build in a new JVM. It accomplishes
its task by building up a conventional Maven command line from options given in
the current request, along with those global options specified in the invoker
itself. Once it has the command line, the invoker will execute it, and capture
the resulting exit code or any exception thrown to signal a failure to execute.
Input/output control can be specified using an InputStream and up to two
InvocationOutputHandlers.</p>

<p>You can download the appropriate sources etc. from the
<a href="http://maven.apache.org/shared/maven-invoker/download.cgi">download page</a>.</p>

<figure class='code'><figcaption><span></span></figcaption><div class="highlight"><table><tr><td class="gutter"><pre class="line-numbers"><span class='line-number'>1</span>
<span class='line-number'>2</span>
<span class='line-number'>3</span>
<span class='line-number'>4</span>
<span class='line-number'>5</span>
<span class='line-number'>6</span>
<span class='line-number'>7</span>
</pre></td><td class='code'><pre><code class='xml'><span class='line'><span class="nt">&lt;dependencies&gt;</span>
</span><span class='line'>  <span class="nt">&lt;dependency&gt;</span>
</span><span class='line'>    <span class="nt">&lt;groupId&gt;</span>org.apache.maven.shared<span class="nt">&lt;/groupId&gt;</span>
</span><span class='line'>    <span class="nt">&lt;artifactId&gt;</span>maven-invoker<span class="nt">&lt;/artifactId&gt;</span>
</span><span class='line'>    <span class="nt">&lt;version&gt;</span>3.1.0<span class="nt">&lt;/version&gt;</span>
</span><span class='line'>  <span class="nt">&lt;/dependency&gt;</span>
</span><span class='line'><span class="nt">&lt;/dependencies&gt;</span>
</span></code></pre></td></tr></table></div></figure>




<!-- more -->


<p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?version=12339250&amp;styleName=Text&amp;projectId=12317922">Release Notes &ndash; Maven Shared Components &ndash; Version maven-invoker-3.1.0</a></p>

<p>Improvement:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-702">MSHARED-702</a> &ndash; Remove hard coded versions for plexus-component-annotations/plexus-component-metadata</li>
</ul>


<p>Tasks:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-625">MSHARED-625</a> &ndash; Refactored to use &lsquo;maven-shared-utils&rsquo; instead of &lsquo;plexus-utils&rsquo;.</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-729">MSHARED-729</a> &ndash; Upgrade to JDK 7 minimum.</li>
</ul>


<p>Dependency upgrades:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-700">MSHARED-700</a> &ndash; Upgrade parent to 31</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-728">MSHARED-728</a> &ndash; Upgrade maven-shared-utils to 3.2.1</li>
</ul>


<p>Enjoy,</p>

<p>-The Apache Maven team</p>
</div>
