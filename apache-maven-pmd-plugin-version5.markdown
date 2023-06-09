---
layout: post
title: Apache Maven PMD Plugin, version 3.19.0
date: '2022-09-05T07:13:13+00:00'
permalink: apache-maven-pmd-plugin-version5
---
<div class="post_body"><p>The Maven team is pleased to announce the release of the
<a href="https://maven.apache.org/plugins/maven-pmd-plugin/">Apache Maven PMD Plugin, version 3.19.0</a></p>
<p>A Maven plugin for the PMD toolkit, that produces a report on both code rule
violations and detected copy and paste fragments, as well as being able to fail
the build based on these metrics.</p>
<p>You can download the appropriate sources etc. from the
<a href="https://maven.apache.org/plugins/maven-pmd-plugin/download.cgi">download page</a>.</p>
<p>You should specify the version in your project's plugin configuration:</p>
<div class="highlight"><pre tabindex="0" class="chroma"><code class="language-xml" data-lang="xml"><span class="line"><span class="ln">1</span><span class="cl"><span class="nt">&lt;plugin&gt;</span>
</span></span><span class="line"><span class="ln">2</span><span class="cl">  <span class="nt">&lt;groupId&gt;</span>org.apache.maven.plugins<span class="nt">&lt;/groupId&gt;</span>
</span></span><span class="line"><span class="ln">3</span><span class="cl">  <span class="nt">&lt;artifactId&gt;</span>maven-pmd-plugin<span class="nt">&lt;/artifactId&gt;</span>
</span></span><span class="line"><span class="ln">4</span><span class="cl">  <span class="nt">&lt;version&gt;</span>3.19.0<span class="nt">&lt;/version&gt;</span>
</span></span><span class="line"><span class="ln">5</span><span class="cl"><span class="nt">&lt;/plugin&gt;</span>
</span></span></code></pre></div><p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317621&amp;version=12352255">Release Notes - Apache Maven PMD Plugin - Version 3.19.0</a></p>
<ul>
<li>
<p>Bug:</p>
<ul>
<li><a href="https://issues.apache.org/jira/browse/MPMD-353">MPMD-353</a> - API incompatibility with jansi after upgrading m-shared-utils</li>
</ul>
</li>
<li>
<p>Task:</p>
<ul>
<li><a href="https://issues.apache.org/jira/browse/MPMD-354">MPMD-354</a> - Upgrade to PMD 6.49.0</li>
</ul>
</li>
</ul>
<p>Enjoy,</p>
<p>-The Maven team</p>
    </div>
