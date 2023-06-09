---
layout: post
title: Apache Maven Reporting API 3.1.1 released
date: '2022-07-31T19:17:17+00:00'
permalink: apache-maven-reporting-api-3
---
<div class="post_body"><p>The Apache Maven team is pleased to announce the release of the
<a href="https://maven.apache.org/shared/maven-reporting-api/">Apache Shared Component: Apache Maven Reporting API Version 3.1.1</a></p>
<p>Abstract classes to manage report generation, which can be run both:</p>
<ul>
<li>as part of a site generation, as a <a href="https://maven.apache.org/shared/maven-reporting-api/">maven-reporting-api</a>'s <a href="https://maven.apache.org/shared/maven-reporting-api/apidocs/org/apache/maven/reporting/MavenReport.html">MavenReport</a>,</li>
<li>or as a direct standalone goal invocation, as a <a href="https://maven.apache.org/ref/current/maven-plugin-api/">maven-plugin-api</a>'s <a href="https://maven.apache.org/ref/current/maven-plugin-api/apidocs/org/apache/maven/plugin/Mojo.html">Mojo</a>.</li>
</ul>
<div class="highlight"><pre tabindex="0" class="chroma"><code class="language-xml" data-lang="xml"><span class="line"><span class="ln">1</span><span class="cl"><span class="nt">&lt;plugin&gt;</span>
</span></span><span class="line"><span class="ln">2</span><span class="cl">  <span class="nt">&lt;groupId&gt;</span>org.apache.maven.reporting<span class="nt">&lt;/groupId&gt;</span>
</span></span><span class="line"><span class="ln">3</span><span class="cl">  <span class="nt">&lt;artifactId&gt;</span>maven-reporting-api<span class="nt">&lt;/artifactId&gt;</span>
</span></span><span class="line"><span class="ln">4</span><span class="cl">  <span class="nt">&lt;version&gt;</span>3.1.1<span class="nt">&lt;/version&gt;</span>
</span></span><span class="line"><span class="ln">5</span><span class="cl"><span class="nt">&lt;/plugin&gt;</span>
</span></span></code></pre></div><p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317922&amp;version=12352152">Release Notes Maven Reporting API Version 3.1.1</a></p>
<ul>
<li>
<p>Task:</p>
<ul>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-1118">MSHARED-1118</a> - Restore binary compat for MavenReport (partially revert MSHARED-1024)</li>
</ul>
</li>
</ul>
<p>Enjoy,</p>
<p>-The Apache Maven Team</p>

    </div>
