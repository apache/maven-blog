---
layout: post
title: Maven Parent POMs Version 32
date: '2018-07-20T14:20:17+00:00'
permalink: apache-software-foundation-parent-pom
---
<div class="entry-content"><p>The Apache Maven team is pleased to announce the release of the
<a href="https://maven.apache.org/pom/maven/">Maven Parent POMs Version 32</a></p>

<p>Maven Parent POMs include <a href="https://maven.apache.org/pom/maven/">Maven Parent POM</a>
 itself, but also <a href="https://maven.apache.org/pom/maven/maven-plugins/">Maven Plugins Parent POM</a>,
<a href="https://maven.apache.org/pom/maven/maven-shared-components/">Maven Shared Components Parent POM</a>,
<a href="https://maven.apache.org/pom/maven/maven-skins/">Maven Skins Parent POM</a> and
Maven Doxia Tools Parent POM.</p>

<p><a href="https://maven.apache.org/pom/maven/">https://maven.apache.org/pom/maven/</a></p>

<p>You should specify the version in your project as parent like the following:</p>

<figure class='code'><figcaption><span></span></figcaption><div class="highlight"><table><tr><td class="gutter"><pre class="line-numbers"><span class='line-number'>1</span>
<span class='line-number'>2</span>
<span class='line-number'>3</span>
<span class='line-number'>4</span>
<span class='line-number'>5</span>
</pre></td><td class='code'><pre><code class='xml'><span class='line'><span class="nt">&lt;parent&gt;</span>
</span><span class='line'>   <span class="nt">&lt;groupId&gt;</span>org.apache.maven<span class="nt">&lt;/groupId&gt;</span>
</span><span class='line'>   <span class="nt">&lt;artifactId&gt;</span>maven-parent<span class="nt">&lt;/artifactId&gt;</span>
</span><span class='line'>   <span class="nt">&lt;version&gt;</span>32<span class="nt">&lt;/version&gt;</span>
</span><span class='line'><span class="nt">&lt;/parent&gt;</span>
</span></code></pre></td></tr></table></div></figure>


<p>You can download the appropriate sources etc. from the download page:</p>

<p><a href="https://maven.apache.org/pom/maven/download.html">https://maven.apache.org/pom/maven/download.html</a></p>

<!-- more -->


<p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12311250&amp;version=12342723">Release Notes &ndash; Maven POMs &ndash; Version MAVEN-32</a></p>

<p>Improvements:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MPOM-187">MPOM-187</a> &ndash; Add autoVersionSubmodules=true to maven-release-plugin configuration</li>
<li><a href="https://issues.apache.org/jira/browse/MPOM-189">MPOM-189</a> &ndash; Ensure that Jenkins will fail when maven-invoker-plugin has failures</li>
<li><a href="https://issues.apache.org/jira/browse/MPOM-190">MPOM-190</a> &ndash; Change to https instead of http</li>
</ul>


<p>Task:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MPOM-183">MPOM-183</a> &ndash; remove maven-archetype-bundles</li>
</ul>


<p>Dependency upgrades:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MPOM-184">MPOM-184</a> &ndash; Upgrade maven-surefire/failsafe to 2.21.0 based on JDK 10 issues</li>
<li><a href="https://issues.apache.org/jira/browse/MPOM-188">MPOM-188</a> &ndash; maven-invoker-plugin should copy value of https.protocols system property during invocation</li>
<li><a href="https://issues.apache.org/jira/browse/MPOM-193">MPOM-193</a> &ndash; Upgrade extra-enforcer-rule to 1.0-beta-9</li>
</ul>


<p>Changes since version 31:</p>

<p><a href="https://gitbox.apache.org/repos/asf?p=maven-parent.git;a=blobdiff;f=pom.xml;hb=maven-parent-32;hpb=maven-parent-31">https://gitbox.apache.org/repos/asf?p=maven-parent.git;a=blobdiff;f=pom.xml;hb=maven-parent-32;hpb=maven-parent-31</a></p>

<p>Enjoy,
&ndash; The Apache Maven Team</p>
</div>
