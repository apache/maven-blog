---
layout: post
title: Apache Maven Resources Plugin Version 3.3.0 Released
date: '2022-07-25T22:52:52+00:00'
permalink: apache-maven-resources-plugin-version1
---
 <div class="post_body"><p>The Apache Maven team is pleased to announce the release of the
<a href="https://maven.apache.org/plugins/maven-resources-plugin">Apache Maven Resources Plugin, Version 3.3.0</a>.</p>
<p>The Resources Plugin handles the copying of project resources to the output
directory. There are two different kinds of resources: main resources and test
resources. The difference is that the main resources are the resources
associated to the main source code while the test resources are associated to
the test source code.</p>
<p>Thus, this allows the separation of resources for the main source code and its
unit tests.</p>
<p>You should specify the version in your project's plugin configuration:</p>
<div class="highlight"><pre tabindex="0" class="chroma"><code class="language-xml" data-lang="xml"><span class="line"><span class="ln">1</span><span class="cl"><span class="nt">&lt;plugin&gt;</span>
</span></span><span class="line"><span class="ln">2</span><span class="cl">  <span class="nt">&lt;groupId&gt;</span>org.apache.maven.plugins<span class="nt">&lt;/groupId&gt;</span>
</span></span><span class="line"><span class="ln">3</span><span class="cl">  <span class="nt">&lt;artifactId&gt;</span>maven-resources-plugin<span class="nt">&lt;/artifactId&gt;</span>
</span></span><span class="line"><span class="ln">4</span><span class="cl">  <span class="nt">&lt;version&gt;</span>3.3.0<span class="nt">&lt;/version&gt;</span>
</span></span><span class="line"><span class="ln">5</span><span class="cl"><span class="nt">&lt;/plugin&gt;</span>
</span></span></code></pre></div><p>You can download the appropriate sources etc. from the download page:</p>
<p><a href="https://maven.apache.org/plugins/maven-resources-plugin/download.cgi">https://maven.apache.org/plugins/maven-resources-plugin/download.cgi</a></p>
<p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317827&amp;version=12348676">Release Notes - Apache Maven Resources Version 3.3.0</a></p>
<ul>
<li>
<p>Bugs:</p>
<ul>
<li><a href="https://issues.apache.org/jira/browse/MRESOURCES-237">MRESOURCES-237</a> - Resource plugin's handling of symbolic links changed in 3.0.x, broke existing behavior</li>
<li><a href="https://issues.apache.org/jira/browse/MRESOURCES-265">MRESOURCES-265</a> - Resource copying not using specified encoding</li>
<li><a href="https://issues.apache.org/jira/browse/MRESOURCES-268">MRESOURCES-268</a> - java.nio.charset.MalformedInputException: Input length = 1</li>
<li><a href="https://issues.apache.org/jira/browse/MRESOURCES-269">MRESOURCES-269</a> - Symlinks cause copying resources to fail</li>
<li><a href="https://issues.apache.org/jira/browse/MRESOURCES-273">MRESOURCES-273</a> - Filtering of Maven properties with long names is not working after transition from 2.6 to 3.2.0</li>
<li><a href="https://issues.apache.org/jira/browse/MRESOURCES-275">MRESOURCES-275</a> - valid location for directory parameter is always required</li>
</ul>
</li>
<li>
<p>New Feature:</p>
<ul>
<li><a href="https://issues.apache.org/jira/browse/MRESOURCES-250">MRESOURCES-250</a> - Add ability to flatten folder structure into target directory when copying resources</li>
</ul>
</li>
<li>
<p>Tasks:</p>
<ul>
<li><a href="https://issues.apache.org/jira/browse/MRESOURCES-277">MRESOURCES-277</a> - Update plugin (requires Maven 3.2.5+)</li>
<li><a href="https://issues.apache.org/jira/browse/MRESOURCES-283">MRESOURCES-283</a> - Require Java 8</li>
</ul>
</li>
<li>
<p>Dependency upgrades:</p>
<ul>
<li><a href="https://issues.apache.org/jira/browse/MRESOURCES-282">MRESOURCES-282</a> - Upgrade maven-plugin parent to 36</li>
<li><a href="https://issues.apache.org/jira/browse/MRESOURCES-286">MRESOURCES-286</a> - Upgrade Maven Filtering to 3.3.0</li>
</ul>
</li>
</ul>
<p>Enjoy,</p>
<p>-The Apache Maven team</p>

    </div>
