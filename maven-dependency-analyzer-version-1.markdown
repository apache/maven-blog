---
layout: post
title: Maven Dependency Analyzer Version 1.13.0 Released
date: '2022-08-24T21:34:34+00:00'
permalink: maven-dependency-analyzer-version-1
---
<div class="post_body"><p>The Apache Maven team is pleased to announce the release of the
<a href="https://maven.apache.org/shared/maven-dependency-analyzer/">Apache Maven Shared Component: Maven Dependency Analyzer Version 1.13.0</a></p>
<p>Analyzes the dependencies of a project for undeclared or unused artifacts.</p>
<p>You should specify the version in your project's dependency list:</p>
<div class="highlight"><pre tabindex="0" class="chroma"><code class="language-xml" data-lang="xml"><span class="line"><span class="ln">1</span><span class="cl"><span class="nt">&lt;dependency&gt;</span>
</span></span><span class="line"><span class="ln">2</span><span class="cl">  <span class="nt">&lt;groupId&gt;</span>org.apache.maven.shared<span class="nt">&lt;/groupId&gt;</span>
</span></span><span class="line"><span class="ln">3</span><span class="cl">  <span class="nt">&lt;artifactId&gt;</span>maven-dependency-analyzer<span class="nt">&lt;/artifactId&gt;</span>
</span></span><span class="line"><span class="ln">4</span><span class="cl">  <span class="nt">&lt;version&gt;</span>1.13.0<span class="nt">&lt;/version&gt;</span>
</span></span><span class="line"><span class="ln">5</span><span class="cl"><span class="nt">&lt;/dependency&gt;</span>
</span></span></code></pre></div><p>You can download the appropriate sources etc. from the download page:</p>
<ul>
<li><a href="https://maven.apache.org/shared/maven-dependency-analyzer/download.cgi">https://maven.apache.org/shared/maven-dependency-analyzer/download.cgi</a></li>
</ul>
<p>Release Notes - Maven Shared Components - Version 1.13.0</p>
<ul>
<li>
<p>Bugs:</p>
<ul>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-1037">MSHARED-1037</a> - method type signature should not add be added to classes</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-1038">MSHARED-1038</a> - Inner classes are in same compilation unit as container class</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-1039">MSHARED-1039</a> - Array parsing is incorrect</li>
</ul>
</li>
<li>
<p>Improvements:</p>
<ul>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-1035">MSHARED-1035</a> - Get rid of maven-plugin-testing-tools for IT test</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-1036">MSHARED-1036</a> - Project classes are analyzed many times</li>
</ul>
</li>
<li>
<p>Task:</p>
<ul>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-1119">MSHARED-1119</a> - Cleanup IT tests</li>
</ul>
</li>
<li>
<p>Dependency upgrades:</p>
<ul>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-916">MSHARED-916</a> - Require Maven 3.2.5+ (drop dependency to Maven 2.0.5)</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-1084">MSHARED-1084</a> - Bump asm from 9.2 to 9.3 -  Java 19 support</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-1085">MSHARED-1085</a> - Upgrade Parent to 37</li>
</ul>
</li>
</ul>
<p>Enjoy,</p>
<p>-The Apache Maven team</p>

    </div>
