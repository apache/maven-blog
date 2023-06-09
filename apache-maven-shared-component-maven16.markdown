---
layout: post
title: 'Apache Maven Shared Component: Maven Verifier Version 2.0.0-M1 Released'
date: '2022-09-26T12:41:41+00:00'
permalink: apache-maven-shared-component-maven16
---
<div class="post_body"><p>The Apache Maven team is pleased to announce the release of the
<a href="https://maven.apache.org/shared/maven-verifier/">Maven Verifier, version 2.0.0-M1</a>.</p>
<p>This library provides a test harness for Maven integration tests.</p>
<p>You should specify the version in your project's dependency configuration:</p>
<div class="highlight"><pre tabindex="0" class="chroma"><code class="language-xml" data-lang="xml"><span class="line"><span class="ln">1</span><span class="cl"><span class="nt">&lt;dependency&gt;</span>
</span></span><span class="line"><span class="ln">2</span><span class="cl">    <span class="nt">&lt;groupId&gt;</span>org.apache.maven.shared<span class="nt">&lt;/groupId&gt;</span>
</span></span><span class="line"><span class="ln">3</span><span class="cl">    <span class="nt">&lt;artifactId&gt;</span>maven-verifier<span class="nt">&lt;/artifactId&gt;</span>
</span></span><span class="line"><span class="ln">4</span><span class="cl">    <span class="nt">&lt;version&gt;</span>2.0.0-M1<span class="nt">&lt;/version&gt;</span>
</span></span><span class="line"><span class="ln">5</span><span class="cl"><span class="nt">&lt;/dependency&gt;</span>
</span></span></code></pre></div><p>You can download the appropriate sources etc. from the <a href="https://maven.apache.org/shared/maven-verifier/download.html">download page</a>.</p>
<p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?version=12351428&amp;styleName=Text&amp;projectId=12317922">Release Notes - Maven Verifier - Version 2.0.0-M1</a></p>
<ul>
<li>
<p>Improvements:</p>
<ul>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-690">MSHARED-690</a> - Change package from org.apache.maven.it to org.apache.maven.shared.verifier</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-1124">MSHARED-1124</a> - Add new version of methods filterFile and newDefaultFilterMap</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-1125">MSHARED-1125</a> - Require Maven args to be provided one by one</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-1127">MSHARED-1127</a> - Remove main method from Verifier</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-1128">MSHARED-1128</a> - Deprecate all executeGoal(s) methods</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-1129">MSHARED-1129</a> - Replace CLI options with CLI args</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-1134">MSHARED-1134</a> - Remove / deprecate internal debug mode in Verifier</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-1135">MSHARED-1135</a> - Deprecate Verifier#setMavenDebug(boolean) for removal</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-1137">MSHARED-1137</a> - Revise Verifier#getDefaultMavenHome()/#getExecutable()</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-1142">MSHARED-1142</a> - Remove e.getMessage() duplication when e is passed as object</li>
</ul>
</li>
<li>
<p>Dependency upgrades:</p>
<ul>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-1075">MSHARED-1075</a> - Upgrade Parent to 36</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-1089">MSHARED-1089</a> - Update maven-verifier to JDK 8 / Junit 5</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-1126">MSHARED-1126</a> - Bump maven-shared-components from 36 to 37</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-1148">MSHARED-1148</a> - Bump junit-jupiter from 5.9.0 to 5.9.1</li>
</ul>
</li>
</ul>
<p>Enjoy,</p>
<p>-The Apache Maven team</p>

    </div>
