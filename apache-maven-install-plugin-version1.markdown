---
layout: post
title: Apache Maven Install Plugin, version 3.0.1 released
date: '2022-07-23T19:12:12+00:00'
permalink: apache-maven-install-plugin-version1
---
 <div class="post_body"><p>The Apache Maven team is pleased to announce the release of the
<a href="https://maven.apache.org/plugins/maven-install-plugin/">Apache Maven Install Plugin, version 3.0.1</a>.</p>
<p>The Install Plugin is used during the install phase to add artifact(s) to the
local repository. The Install Plugin uses the information in the POM (groupId,
artifactId, version) to determine the proper location for the artifact within
the local repository.</p>
<p>NOTE:</p>
<ul>
<li>Plugin is Java7 level and compatible with Maven 3.2.5+</li>
</ul>
<div class="highlight"><pre tabindex="0" class="chroma"><code class="language-xml" data-lang="xml"><span class="line"><span class="ln">1</span><span class="cl"><span class="nt">&lt;plugin&gt;</span>
</span></span><span class="line"><span class="ln">2</span><span class="cl">  <span class="nt">&lt;groupId&gt;</span>org.apache.maven.plugins<span class="nt">&lt;/groupId&gt;</span>
</span></span><span class="line"><span class="ln">3</span><span class="cl">  <span class="nt">&lt;artifactId&gt;</span>maven-install-plugin<span class="nt">&lt;/artifactId&gt;</span>
</span></span><span class="line"><span class="ln">4</span><span class="cl">  <span class="nt">&lt;version&gt;</span>3.0.1<span class="nt">&lt;/version&gt;</span>
</span></span><span class="line"><span class="ln">5</span><span class="cl"><span class="nt">&lt;/plugin&gt;</span>
</span></span></code></pre></div><p>You can download the appropriate sources etc. from the <a href="https://maven.apache.org/plugins/maven-install-plugin/download.cgi">download page</a>.</p>
<p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317524&amp;version=12352096">Release Notes - Maven Install Plugin Version 3.0.1</a></p>
<ul>
<li>
<p>Bug:</p>
<ul>
<li><a href="https://issues.apache.org/jira/browse/MINSTALL-160">MINSTALL-160</a> - generatePom=true with 3.0.0-M1 does not generate minimal POM but copies existing one</li>
</ul>
</li>
</ul>
<p>Enjoy,</p>
<p>-The Apache Maven team</p>
    </div>
