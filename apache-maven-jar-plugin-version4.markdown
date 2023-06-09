---
layout: post
title: Apache Maven Jar Plugin, version 3.3.0
date: '2022-09-16T07:13:13+00:00'
permalink: apache-maven-jar-plugin-version4
---
 <div class="post_body"><p>The Apache Maven team is pleased to announce the release of the
<a href="https://maven.apache.org/plugins/maven-jar-plugin/">Apache Maven Jar Plugin, version 3.3.0</a>.</p>
<p>This plugin provides the capability to build jars.</p>
<div class="highlight"><pre tabindex="0" class="chroma"><code class="language-xml" data-lang="xml"><span class="line"><span class="ln">1</span><span class="cl"><span class="nt">&lt;plugin&gt;</span>
</span></span><span class="line"><span class="ln">2</span><span class="cl">  <span class="nt">&lt;groupId&gt;</span>org.apache.maven.plugins<span class="nt">&lt;/groupId&gt;</span>
</span></span><span class="line"><span class="ln">3</span><span class="cl">  <span class="nt">&lt;artifactId&gt;</span>maven-jar-plugin<span class="nt">&lt;/artifactId&gt;</span>
</span></span><span class="line"><span class="ln">4</span><span class="cl">  <span class="nt">&lt;version&gt;</span>3.3.0<span class="nt">&lt;/version&gt;</span>
</span></span><span class="line"><span class="ln">5</span><span class="cl"><span class="nt">&lt;/plugin&gt;</span>
</span></span></code></pre></div><!-- more -->
<p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317526&amp;version=12351126">Release Notes - Maven JAR Plugin - Version 3.3.0</a></p>
<ul>
<li>
<p>Bug:</p>
<ul>
<li><a href="https://issues.apache.org/jira/browse/MJAR-275">MJAR-275</a> - outputTimestamp not applied to module-info; breaks reproducible builds</li>
</ul>
</li>
<li>
<p>Tasks:</p>
<ul>
<li><a href="https://issues.apache.org/jira/browse/MJAR-278">MJAR-278</a> - Update plugin (requires Maven 3.2.5+)</li>
<li><a href="https://issues.apache.org/jira/browse/MJAR-280">MJAR-280</a> - Java 8 as minimum</li>
</ul>
</li>
<li>
<p>Dependency upgrades:</p>
<ul>
<li><a href="https://issues.apache.org/jira/browse/MJAR-288">MJAR-288</a> - Upgrade Parent to 36</li>
<li><a href="https://issues.apache.org/jira/browse/MJAR-290">MJAR-290</a> - Update Plexus Utils to 3.4.2</li>
<li><a href="https://issues.apache.org/jira/browse/MJAR-291">MJAR-291</a> - Upgrade Parent to 37</li>
</ul>
</li>
</ul>
<p>Enjoy,</p>
<ul>
<li>The Apache Maven team</li>
</ul>

    </div>
