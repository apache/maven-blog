---
layout: post
title: Apache Maven Shade Plugin, version 3.4.0
date: '2022-09-14T21:15:15+00:00'
permalink: apache-maven-shade-plugin-version7
---
<div class="post_body"><p>The Apache Maven team is pleased to announce the release of the <a href="https://maven.apache.org/plugins/maven-shade-plugin/">Apache
Maven Shade Plugin, version 3.4.0</a>.</p>
<p>This plugin provides the capability to package the artifact in an uber-jar,
including its dependencies and to shade - i.e. rename - the packages of some dependencies.</p>
<p>Notes:</p>
<ul>
<li>Starting from this release you need JDK8 as minimum.</li>
<li>Minimum Maven Version 3.1.1.</li>
</ul>
<p>You should specify the version in your project's plugin configuration:</p>
<div class="highlight"><pre tabindex="0" class="chroma"><code class="language-xml" data-lang="xml"><span class="line"><span class="ln">1</span><span class="cl"><span class="nt">&lt;plugin&gt;</span>
</span></span><span class="line"><span class="ln">2</span><span class="cl">  <span class="nt">&lt;groupId&gt;</span>org.apache.maven.plugins<span class="nt">&lt;/groupId&gt;</span>
</span></span><span class="line"><span class="ln">3</span><span class="cl">  <span class="nt">&lt;artifactId&gt;</span>maven-shade-plugin<span class="nt">&lt;/artifactId&gt;</span>
</span></span><span class="line"><span class="ln">4</span><span class="cl">  <span class="nt">&lt;version&gt;</span>3.4.0<span class="nt">&lt;/version&gt;</span>
</span></span><span class="line"><span class="ln">5</span><span class="cl"><span class="nt">&lt;/plugin&gt;</span>
</span></span></code></pre></div><p>You can download the <a href="https://maven.apache.org/plugins/maven-shade-plugin/download.cgi">appropriate sources etc. from the download page</a></p>
<!-- more -->
<p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317921&amp;version=12351491">Release Notes - Maven Shade Plugin - Version 3.4.0</a></p>
<ul>
<li>
<p>Bug:</p>
<ul>
<li><a href="https://issues.apache.org/jira/browse/MSHADE-425">MSHADE-425</a> - Maven shade plugin build fails without 'clean' goal</li>
</ul>
</li>
<li>
<p>Tasks:</p>
<ul>
<li><a href="https://issues.apache.org/jira/browse/MSHADE-393">MSHADE-393</a> - Upgrade project from Java 7 to 8</li>
<li><a href="https://issues.apache.org/jira/browse/MSHADE-416">MSHADE-416</a> - Jenkins URL is wrong.</li>
<li><a href="https://issues.apache.org/jira/browse/MSHADE-423">MSHADE-423</a> - Get rid of commons-lang3</li>
</ul>
</li>
<li>
<p>Dependency upgrades:</p>
<ul>
<li><a href="https://issues.apache.org/jira/browse/MSHADE-415">MSHADE-415</a> - Upgrade maven-plugin parent to 37</li>
<li><a href="https://issues.apache.org/jira/browse/MSHADE-424">MSHADE-424</a> - Upgrade jdependency 2.8.0</li>
</ul>
</li>
</ul>
<p>Enjoy,</p>
<p>-The Apache Maven team</p>

    </div>
