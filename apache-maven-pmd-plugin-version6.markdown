---
layout: post
title: Apache Maven PMD Plugin, version 3.20.0 Released
date: '2023-01-11T20:35:35+00:00'
permalink: apache-maven-pmd-plugin-version6
---
   <div class="post_body"><p>The Maven team is pleased to announce the release of the
<a href="https://maven.apache.org/plugins/maven-pmd-plugin/">Apache Maven PMD Plugin, version 3.20.0</a></p>
<p>A Maven plugin for the PMD toolkit, that produces a report on both code rule
violations and detected copy and paste fragments, as well as being able to fail
the build based on these metrics.</p>
<p>You can download the appropriate sources etc. from the
<a href="https://maven.apache.org/plugins/maven-pmd-plugin/download.cgi">download page</a>.</p>
<p>You should specify the version in your project's plugin configuration:</p>
<div class="highlight"><pre tabindex="0" class="chroma"><code class="language-xml" data-lang="xml"><span class="line"><span class="ln">1</span><span class="cl"><span class="nt">&lt;plugin&gt;</span>
</span></span><span class="line"><span class="ln">2</span><span class="cl">  <span class="nt">&lt;groupId&gt;</span>org.apache.maven.plugins<span class="nt">&lt;/groupId&gt;</span>
</span></span><span class="line"><span class="ln">3</span><span class="cl">  <span class="nt">&lt;artifactId&gt;</span>maven-pmd-plugin<span class="nt">&lt;/artifactId&gt;</span>
</span></span><span class="line"><span class="ln">4</span><span class="cl">  <span class="nt">&lt;version&gt;</span>3.20.0<span class="nt">&lt;/version&gt;</span>
</span></span><span class="line"><span class="ln">5</span><span class="cl"><span class="nt">&lt;/plugin&gt;</span>
</span></span></code></pre></div><p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317621&amp;version=12352270">Release Notes - Apache Maven PMD Plugin - Version 3.20.0</a></p>
<ul>
<li>
<p>Bug</p>
<ul>
<li><a href="https://issues.apache.org/jira/browse/MPMD-335">MPMD-335</a> - Aggregate mode doesn't use additional repositories</li>
</ul>
</li>
<li>
<p>Task</p>
<ul>
<li><a href="https://issues.apache.org/jira/browse/MPMD-361">MPMD-361</a> - Explicitly start and end tables with Doxia Sinks in report renderers</li>
</ul>
</li>
<li>
<p>Dependency upgrades</p>
<ul>
<li><a href="https://issues.apache.org/jira/browse/MPMD-356">MPMD-356</a> - Upgrade to PMD 6.50.0</li>
<li><a href="https://issues.apache.org/jira/browse/MPMD-357">MPMD-357</a> - Upgrade to PMD 6.51.0</li>
<li><a href="https://issues.apache.org/jira/browse/MPMD-358">MPMD-358</a> - Upgrade to PMD 6.52.0</li>
<li><a href="https://issues.apache.org/jira/browse/MPMD-360">MPMD-360</a> - Upgrade to PMD 6.53.0</li>
</ul>
</li>
</ul>
<p>Enjoy,</p>
<ul>
<li>The Maven team</li>
</ul>

    </div>
