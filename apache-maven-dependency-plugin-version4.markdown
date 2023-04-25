---
layout: post
title: Apache Maven Dependency Plugin Version 3.5.0 Released
date: '2023-01-11T21:58:58+00:00'
permalink: apache-maven-dependency-plugin-version4
---
 <div class="post_body"><p>The Apache Maven team is pleased to announce the release of the
<a href="https://maven.apache.org/plugins/maven-dependency-plugin/">Apache Maven Dependecy Plugin, version 3.5.0</a>.</p>
<p>The dependency plugin provides the capability to manipulate artifacts. It
can copy and/or unpack artifacts from local or remote repositories to a
specified location.</p>
<p><a href="https://maven.apache.org/plugins/maven-dependency-plugin/">https://maven.apache.org/plugins/maven-dependency-plugin/</a></p>
<p>You should specify the version in your project's plugin configuration:</p>
<div class="highlight"><pre tabindex="0" class="chroma"><code class="language-xml" data-lang="xml"><span class="line"><span class="ln">1</span><span class="cl"><span class="nt">&lt;plugin&gt;</span>
</span></span><span class="line"><span class="ln">2</span><span class="cl">    <span class="nt">&lt;groupId&gt;</span>org.apache.maven.plugins<span class="nt">&lt;/groupId&gt;</span>
</span></span><span class="line"><span class="ln">3</span><span class="cl">    <span class="nt">&lt;artifactId&gt;</span>maven-dependency-plugin<span class="nt">&lt;/artifactId&gt;</span>
</span></span><span class="line"><span class="ln">4</span><span class="cl">    <span class="nt">&lt;version&gt;</span>3.5.0<span class="nt">&lt;/version&gt;</span>
</span></span><span class="line"><span class="ln">5</span><span class="cl"><span class="nt">&lt;/plugin&gt;</span>
</span></span></code></pre></div><p>You can download the appropriate sources etc. from the download page:</p>
<p><a href="https://maven.apache.org/plugins/maven-dependency-plugin/download.cgi">https://maven.apache.org/plugins/maven-dependency-plugin/download.cgi</a></p>
<p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?version=12340588&amp;styleName=Text&amp;projectId=12317227">Release Notes - Maven Dependency Plugin - Version 3.5.0</a></p>
<ul>
<li>
<p>Improvement</p>
<ul>
<li><a href="https://issues.apache.org/jira/browse/MDEP-831">MDEP-831</a> - Remove not used dependencies / Replace parts</li>
</ul>
</li>
<li>
<p>Task</p>
<ul>
<li><a href="https://issues.apache.org/jira/browse/MDEP-841">MDEP-841</a> - Explicitly start and end tables with Doxia Sinks in report renderers</li>
</ul>
</li>
<li>
<p>Dependency upgrade</p>
<ul>
<li><a href="https://issues.apache.org/jira/browse/MDEP-837">MDEP-837</a> - Upgrade Parent to 38</li>
</ul>
</li>
</ul>
<p>Enjoy,</p>
<p>-The Apache Maven team</p>

    </div>
