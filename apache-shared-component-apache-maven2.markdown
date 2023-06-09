---
layout: post
title: 'Apache Shared Component: Apache Maven Reporting Impl. Version 3.2.0'
date: '2022-08-09T21:01:01+00:00'
permalink: apache-shared-component-apache-maven2
---
<div class="post_body"><p>The Apache Maven team is pleased to announce the release of the
<a href="https://maven.apache.org/shared/maven-reporting-impl/">Apache Shared Component: Apache Maven Reporting Impl. Version 3.2.0</a></p>
<p>Abstract classes to manage report generation, which can be run both:</p>
<ul>
<li>as part of a site generation, as a <a href="https://maven.apache.org/shared/maven-reporting-api/">maven-reporting-api</a>'s <a href="https://maven.apache.org/shared/maven-reporting-api/apidocs/org/apache/maven/reporting/MavenReport.html">MavenReport</a>,</li>
<li>or as a direct standalone goal invocation, as a <a href="https://maven.apache.org/ref/current/maven-plugin-api/">maven-plugin-api</a>'s <a href="https://maven.apache.org/ref/current/maven-plugin-api/apidocs/org/apache/maven/plugin/Mojo.html">Mojo</a>.</li>
</ul>
<div class="highlight"><pre tabindex="0" class="chroma"><code class="language-xml" data-lang="xml"><span class="line"><span class="ln">1</span><span class="cl"><span class="nt">&lt;plugin&gt;</span>
</span></span><span class="line"><span class="ln">2</span><span class="cl">  <span class="nt">&lt;groupId&gt;</span>org.apache.maven.reporting<span class="nt">&lt;/groupId&gt;</span>
</span></span><span class="line"><span class="ln">3</span><span class="cl">  <span class="nt">&lt;artifactId&gt;</span>maven-reporting-impl<span class="nt">&lt;/artifactId&gt;</span>
</span></span><span class="line"><span class="ln">4</span><span class="cl">  <span class="nt">&lt;version&gt;</span>3.2.0<span class="nt">&lt;/version&gt;</span>
</span></span><span class="line"><span class="ln">5</span><span class="cl"><span class="nt">&lt;/plugin&gt;</span>
</span></span></code></pre></div><p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317922&amp;version=12352179">Release Notes Maven Reporting Impl. Version 3.2.0 Released</a></p>
<ul>
<li>
<p>Improvement:</p>
<ul>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-1099">MSHARED-1099</a> - Render with a skin when report is run in standalone mode</li>
</ul>
</li>
<li>
<p>Dependency upgrades:</p>
<ul>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-1120">MSHARED-1120</a> - Upgrade Maven Reporting API to 3.1.1</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-1121">MSHARED-1121</a> - Upgrade plugins and components in project and ITs</li>
</ul>
</li>
</ul>
<p>Enjoy,</p>
<ul>
<li>The Apache Maven Team</li>
</ul>

    </div>
