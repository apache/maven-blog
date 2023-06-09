---
layout: post
title: Apache Maven Site Plugin Version 3.12.1 Released
date: '2022-08-04T12:01:01+00:00'
permalink: apache-maven-site-plugin-version6
---
<div class="post_body"><p>The Apache Maven team is pleased to announce the release of the
<a href="https://maven.apache.org/plugins/maven-site-plugin/">Apache Maven Site Plugin, version 3.12.1</a>.</p>
<p>The Site Plugin is used to generate a site for the project. The generated site
also includes the project's reports that were configured in the POM.</p>
<p>You can download the appropriate sources etc. from the download page:</p>
<p><a href="https://maven.apache.org/plugins/maven-site-plugin/download.cgi">https://maven.apache.org/plugins/maven-site-plugin/download.cgi</a></p>
<div class="highlight"><pre tabindex="0" class="chroma"><code class="language-xml" data-lang="xml"><span class="line"><span class="ln">1</span><span class="cl"><span class="nt">&lt;plugin&gt;</span>
</span></span><span class="line"><span class="ln">2</span><span class="cl">  <span class="nt">&lt;groupId&gt;</span>org.apache.maven.plugins<span class="nt">&lt;/groupId&gt;</span>
</span></span><span class="line"><span class="ln">3</span><span class="cl">  <span class="nt">&lt;artifactId&gt;</span>maven-site-plugin<span class="nt">&lt;/artifactId&gt;</span>
</span></span><span class="line"><span class="ln">4</span><span class="cl">  <span class="nt">&lt;version&gt;</span>3.12.1<span class="nt">&lt;/version&gt;</span>
</span></span><span class="line"><span class="ln">5</span><span class="cl"><span class="nt">&lt;/plugin&gt;</span>   
</span></span></code></pre></div><p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?version=12351337&amp;styleName=Text&amp;projectId=12317923">Release Notes - Maven Site Plugin - Version 3.12.1</a></p>
<ul>
<li>
<p>Bug:</p>
<ul>
<li><a href="https://issues.apache.org/jira/browse/MSITE-901">MSITE-901</a> - If preceding standalone report has been run, site:jar does not reinvoke site:site</li>
</ul>
</li>
<li>
<p>Dependency upgrades:</p>
<ul>
<li><a href="https://issues.apache.org/jira/browse/MSITE-897">MSITE-897</a> - Upgrade Plexus Archiver to 4.2.7</li>
<li><a href="https://issues.apache.org/jira/browse/MSITE-898">MSITE-898</a> - Upgrade Parent to 36</li>
<li><a href="https://issues.apache.org/jira/browse/MSITE-902">MSITE-902</a> - Upgrade Plexus Utils to 3.4.2</li>
<li><a href="https://issues.apache.org/jira/browse/MSITE-908">MSITE-908</a> - Upgrade Maven Reporting API to 3.1.1</li>
</ul>
</li>
</ul>
<p>Enjoy,</p>
<p>-The Apache Maven team</p>

    </div>
