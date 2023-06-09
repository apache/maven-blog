---
layout: post
title: 'Apache Maven Shared component: Maven Common Artifact Filters Version 3.3.2'
date: '2022-09-16T07:16:16+00:00'
permalink: apache-maven-shared-component-maven15
---
<div class="post_body"><p>The Apache Maven team is pleased to announce the release of the
<a href="https://maven.apache.org/shared/maven-common-artifact-filters/">Apache Maven Shared Component: Maven Common Artifact Filters Version 3.3.2</a>.</p>
<p>A collection of ready-made filters to control inclusion/exclusion of artifacts
during dependency resolution.</p>
<p>You should specify the version in your project's plugin configuration:</p>
<div class="highlight"><pre tabindex="0" class="chroma"><code class="language-xml" data-lang="xml"><span class="line"><span class="ln">1</span><span class="cl"><span class="nt">&lt;plugin&gt;</span>
</span></span><span class="line"><span class="ln">2</span><span class="cl">  <span class="nt">&lt;groupId&gt;</span>org.apache.maven.shared<span class="nt">&lt;/groupId&gt;</span>
</span></span><span class="line"><span class="ln">3</span><span class="cl">  <span class="nt">&lt;artifactId&gt;</span>maven-common-artifact-filters<span class="nt">&lt;/artifactId&gt;</span>
</span></span><span class="line"><span class="ln">4</span><span class="cl">  <span class="nt">&lt;version&gt;</span>3.3.2<span class="nt">&lt;/version&gt;</span>
</span></span><span class="line"><span class="ln">5</span><span class="cl"><span class="nt">&lt;/plugin&gt;</span>
</span></span></code></pre></div><p>You can download the appropriate sources etc. from the <a href="http://maven.apache.org/shared/maven-common-artifact-filters/download.cgi">download page</a>.</p>
<p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317922&amp;version=12352116">Release Notes Maven Common Artifact Filters 3.3.2</a></p>
<ul>
<li>
<p>Bug</p>
<ul>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-1130">MSHARED-1130</a> - PatternIncludesArtifactFilters raising NPE for patterns w/ wildcards and artifactoid w/ null on any coordinate</li>
</ul>
</li>
<li>
<p>Dependency upgrade</p>
<ul>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-1131">MSHARED-1131</a> - Upgrade Parent to 37 and cleanup</li>
</ul>
</li>
</ul>
<p>Enjoy,</p>
<p>-The Apache Maven team</p>

    </div>
