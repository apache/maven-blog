---
layout: post
title: Apache Maven Surefire/Failsafe Plugin Version 3.0.0-M8 Released
date: '2023-01-11T21:59:59+00:00'
permalink: apache-maven-surefire-failsafe-plugin1
---
 <div class="post_body"><p>The Apache Maven team is pleased to announce the release of the
<a href="https://maven.apache.org/plugins/maven-surefire-plugin/">Apache Maven Surefire Plugin, version 3.0.0-M8</a>.</p>
<p>The release contains 18 fixes and enhancements.
Again we received contributions from the community in form of bug reports
and bug fixes. Thank you and keep them coming!</p>
<p>You should specify the version in your project's plugin configuration:</p>
<div class="highlight"><pre tabindex="0" class="chroma"><code class="language-xml" data-lang="xml"><span class="line"><span class="ln">1</span><span class="cl"><span class="nt">&lt;plugin&gt;</span>
</span></span><span class="line"><span class="ln">2</span><span class="cl">  <span class="nt">&lt;groupId&gt;</span>org.apache.maven.plugins<span class="nt">&lt;/groupId&gt;</span>
</span></span><span class="line"><span class="ln">3</span><span class="cl">  <span class="nt">&lt;artifactId&gt;</span>maven-surefire-plugin<span class="nt">&lt;/artifactId&gt;</span>
</span></span><span class="line"><span class="ln">4</span><span class="cl">  <span class="nt">&lt;version&gt;</span>3.0.0-M8<span class="nt">&lt;/version&gt;</span>
</span></span><span class="line"><span class="ln">5</span><span class="cl"><span class="nt">&lt;/plugin&gt;</span>
</span></span></code></pre></div><p>or for failsafe:</p>
<div class="highlight"><pre tabindex="0" class="chroma"><code class="language-xml" data-lang="xml"><span class="line"><span class="ln">1</span><span class="cl"><span class="nt">&lt;plugin&gt;</span>
</span></span><span class="line"><span class="ln">2</span><span class="cl">  <span class="nt">&lt;groupId&gt;</span>org.apache.maven.plugins<span class="nt">&lt;/groupId&gt;</span>
</span></span><span class="line"><span class="ln">3</span><span class="cl">  <span class="nt">&lt;artifactId&gt;</span>maven-failsafe-plugin<span class="nt">&lt;/artifactId&gt;</span>
</span></span><span class="line"><span class="ln">4</span><span class="cl">  <span class="nt">&lt;version&gt;</span>3.0.0-M8<span class="nt">&lt;/version&gt;</span>
</span></span><span class="line"><span class="ln">5</span><span class="cl"><span class="nt">&lt;/plugin&gt;</span>
</span></span></code></pre></div><p>or for surefire-report:</p>
<div class="highlight"><pre tabindex="0" class="chroma"><code class="language-xml" data-lang="xml"><span class="line"><span class="ln">1</span><span class="cl"><span class="nt">&lt;plugin&gt;</span>
</span></span><span class="line"><span class="ln">2</span><span class="cl">  <span class="nt">&lt;groupId&gt;</span>org.apache.maven.plugins<span class="nt">&lt;/groupId&gt;</span>
</span></span><span class="line"><span class="ln">3</span><span class="cl">  <span class="nt">&lt;artifactId&gt;</span>maven-surefire-report-plugin<span class="nt">&lt;/artifactId&gt;</span>
</span></span><span class="line"><span class="ln">4</span><span class="cl">  <span class="nt">&lt;version&gt;</span>3.0.0-M8<span class="nt">&lt;/version&gt;</span>
</span></span><span class="line"><span class="ln">5</span><span class="cl"><span class="nt">&lt;/plugin&gt;</span>
</span></span></code></pre></div><p>You can download the appropriate <a href="https://maven.apache.org/surefire/download.cgi">sources etc. from the download page</a>.</p>
<p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317927&amp;version=12351809">Release Notes - Maven Surefire - Version 3.0.0-M8</a></p>
<ul>
<li>
<p>Bugs:</p>
<ul>
<li><a href="https://issues.apache.org/jira/browse/SUREFIRE-2032">SUREFIRE-2032</a> - When declare the @Disabled annotation at the class level, skip displayed in other test class</li>
<li><a href="https://issues.apache.org/jira/browse/SUREFIRE-2082">SUREFIRE-2082</a> - Huge test sets may open too many files</li>
<li><a href="https://issues.apache.org/jira/browse/SUREFIRE-2090">SUREFIRE-2090</a> - Xref link to source code with specified line number doesn't work. Missing &quot;L&quot; in anchor</li>
<li><a href="https://issues.apache.org/jira/browse/SUREFIRE-2101">SUREFIRE-2101</a> - Phrased test names with missing @DisplayName result in a &quot;null&quot; test name</li>
<li><a href="https://issues.apache.org/jira/browse/SUREFIRE-2109">SUREFIRE-2109</a> - User cannot write temporary file to surefire/ temp directory</li>
<li><a href="https://issues.apache.org/jira/browse/SUREFIRE-2117">SUREFIRE-2117</a> - XML report omits package and outer class name for tests in @Nested inner class if testset reporter is configured to use phrased naming</li>
<li><a href="https://issues.apache.org/jira/browse/SUREFIRE-2135">SUREFIRE-2135</a> - On Unix-like OS and JDK 18+ Surefire kills the forked JVM if PpidChecker is active and argLine is set to -Dfile.encoding=UTF-16</li>
</ul>
</li>
<li>
<p>New Feature</p>
<ul>
<li><a href="https://issues.apache.org/jira/browse/SUREFIRE-2139">SUREFIRE-2139</a> - Fully support Java 19 byte code</li>
</ul>
</li>
<li>
<p>Improvements:</p>
<ul>
<li><a href="https://issues.apache.org/jira/browse/SUREFIRE-1654">SUREFIRE-1654</a> - Remove deprecated parameter 'forkMode' and use only 'forkCount'</li>
<li><a href="https://issues.apache.org/jira/browse/SUREFIRE-1962">SUREFIRE-1962</a> - Unit test for ProviderInfo#isApplicable</li>
<li><a href="https://issues.apache.org/jira/browse/SUREFIRE-2100">SUREFIRE-2100</a> - Improve behaviour for surefire-report goal with aggregate parameter</li>
<li><a href="https://issues.apache.org/jira/browse/SUREFIRE-2133">SUREFIRE-2133</a> - Make anchors start <em>before</em> the headings</li>
<li><a href="https://issues.apache.org/jira/browse/SUREFIRE-2136">SUREFIRE-2136</a> - UmlautDirIT: Revert special paths with colon in it to regular ones after test</li>
<li><a href="https://issues.apache.org/jira/browse/SUREFIRE-2138">SUREFIRE-2138</a> - Update JUnit versions used in docs/ITs</li>
</ul>
</li>
<li>
<p>Tasks:</p>
<ul>
<li><a href="https://issues.apache.org/jira/browse/SUREFIRE-2122">SUREFIRE-2122</a> - Document how to develop on Surefire using IntelliJ</li>
<li><a href="https://issues.apache.org/jira/browse/SUREFIRE-2126">SUREFIRE-2126</a> - Use the latest surefire version 3.0.0-M7 with self testing</li>
<li><a href="https://issues.apache.org/jira/browse/SUREFIRE-2137">SUREFIRE-2137</a> - Run junit jupiter platform ITs with latest 5.8.x and 5.9.x as well</li>
</ul>
</li>
<li>
<p>Dependency upgrade</p>
<ul>
<li><a href="https://issues.apache.org/jira/browse/SUREFIRE-2129">SUREFIRE-2129</a> - Upgrade Maven Reporting API to 3.1.1/Maven Reporting Impl to 3.2.0</li>
</ul>
</li>
</ul>
<p>Enjoy,</p>
<p>-The Apache Maven team</p>

    </div>
