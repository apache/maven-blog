---
layout: post
title: Apache Maven Install Plugin Version 3.0.0-M1 Released
date: '2018-10-01T09:28:00+00:00'
permalink: apache-maven-install-plugin-version
---
<div class="entry-content"><p>The Apache Maven team is pleased to announce the release of the
<a href="https://maven.apache.org/plugins/maven-install-plugin/">Apache Maven Install Plugin, version 3.0.0-M1</a>.</p>

<p>The Install Plugin is used during the install phase to add artifact(s) to the
local repository. The Install Plugin uses the information in the POM (groupId,
artifactId, version) to determine the proper location for the artifact within
the local repository.</p>

<p>Important Note since 3.0.0-M1:</p>

<ul>
<li>Maven 3.X only</li>
<li>Minimum JDK 7+</li>
<li>The maven-install-plugin does not generate any kind of checksum
anymore.</li>
</ul>


<p>Usage Note:</p>

<ul>
<li>Use the maven-install-plugin 3.0.0-M1 only in combination
with the maven-deploy-plugin 3.0.0-M1.</li>
</ul>


<figure class='code'><figcaption><span></span></figcaption><div class="highlight"><table><tr><td class="gutter"><pre class="line-numbers"><span class='line-number'>1</span>
<span class='line-number'>2</span>
<span class='line-number'>3</span>
<span class='line-number'>4</span>
<span class='line-number'>5</span>
</pre></td><td class='code'><pre><code class='xml'><span class='line'><span class="nt">&lt;plugin&gt;</span>
</span><span class='line'>  <span class="nt">&lt;groupId&gt;</span>org.apache.maven.plugins<span class="nt">&lt;/groupId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;artifactId&gt;</span>maven-install-plugin<span class="nt">&lt;/artifactId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;version&gt;</span>3.0.0-M1<span class="nt">&lt;/version&gt;</span>
</span><span class='line'><span class="nt">&lt;/plugin&gt;</span>
</span></code></pre></td></tr></table></div></figure>


<p>You can download the appropriate sources etc. from the <a href="https://maven.apache.org/plugins/maven-install-plugin/download.cgi">download page</a>.</p>

<!-- more -->


<p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317524&amp;version=12334343">Release Notes &ndash; Maven Install Plugin Version 3.0.0-M1</a></p>

<p>Bugs:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MINSTALL-121">MINSTALL-121</a> &ndash; The packaging property should not be used for the file extension</li>
<li><a href="https://issues.apache.org/jira/browse/MINSTALL-130">MINSTALL-130</a> &ndash; Remove link to non-existing Codehaus wiki</li>
</ul>


<p>Improvements:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MINSTALL-110">MINSTALL-110</a> &ndash; install-file should also install bundled pom.xml from artifact.</li>
<li><a href="https://issues.apache.org/jira/browse/MINSTALL-114">MINSTALL-114</a> &ndash; Plugin shouldn&rsquo;t depend on maven-compat dependency</li>
<li><a href="https://issues.apache.org/jira/browse/MINSTALL-118">MINSTALL-118</a> &ndash; MavenProject with only attachments must have packaging &ldquo;pom&rdquo;</li>
<li><a href="https://issues.apache.org/jira/browse/MINSTALL-124">MINSTALL-124</a> &ndash; Remove hard code version for maven-invoker-plugin</li>
<li><a href="https://issues.apache.org/jira/browse/MINSTALL-128">MINSTALL-128</a> &ndash; Replace usage of the deprecated ArtifactFactory</li>
<li><a href="https://issues.apache.org/jira/browse/MINSTALL-134">MINSTALL-134</a> &ndash; Remove checksum generation</li>
<li><a href="https://issues.apache.org/jira/browse/MINSTALL-136">MINSTALL-136</a> &ndash; Removed unused dependency</li>
<li><a href="https://issues.apache.org/jira/browse/MINSTALL-143">MINSTALL-143</a> &ndash; Move checksum generation from install to deploy plugin</li>
</ul>


<p>Tasks:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MINSTALL-129">MINSTALL-129</a> &ndash; Use released version of maven-artifact-transfer</li>
<li><a href="https://issues.apache.org/jira/browse/MINSTALL-131">MINSTALL-131</a> &ndash; Rename package to org.apache.maven.plugins</li>
<li><a href="https://issues.apache.org/jira/browse/MINSTALL-145">MINSTALL-145</a> &ndash; Remove unused dependencies in pom</li>
<li><a href="https://issues.apache.org/jira/browse/MINSTALL-148">MINSTALL-148</a> &ndash; Document change about createChecksums</li>
<li><a href="https://issues.apache.org/jira/browse/MINSTALL-149">MINSTALL-149</a> &ndash; Remove updateReleaseInfo parameter</li>
<li><a href="https://issues.apache.org/jira/browse/MINSTALL-150">MINSTALL-150</a> &ndash; Lift JDK minimum to JDK 7</li>
</ul>


<p>Dependency upgrades:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MINSTALL-109">MINSTALL-109</a> &ndash; Update version of plexus-utils to 3.0.18</li>
<li><a href="https://issues.apache.org/jira/browse/MINSTALL-111">MINSTALL-111</a> &ndash; Upgrade to maven-plugins parent version 27</li>
<li><a href="https://issues.apache.org/jira/browse/MINSTALL-112">MINSTALL-112</a> &ndash; Upgrade maven-plugin-testing-harness to 1.3</li>
<li><a href="https://issues.apache.org/jira/browse/MINSTALL-113">MINSTALL-113</a> &ndash; Upgrade maven-shared-utils to 0.7</li>
<li><a href="https://issues.apache.org/jira/browse/MINSTALL-117">MINSTALL-117</a> &ndash; Upgrade maven-shared-utils to 3.0.0</li>
<li><a href="https://issues.apache.org/jira/browse/MINSTALL-122">MINSTALL-122</a> &ndash; Upgrade maven-shared-components parent to version 30</li>
<li><a href="https://issues.apache.org/jira/browse/MINSTALL-123">MINSTALL-123</a> &ndash; Upgrade maven-shared-utils to 3.0.1</li>
<li><a href="https://issues.apache.org/jira/browse/MINSTALL-125">MINSTALL-125</a> &ndash; Upgrade of commons-io to 2.5.</li>
<li><a href="https://issues.apache.org/jira/browse/MINSTALL-127">MINSTALL-127</a> &ndash; Upgrade maven-shared-utils to 3.1.0</li>
<li><a href="https://issues.apache.org/jira/browse/MINSTALL-137">MINSTALL-137</a> &ndash; Upgrade maven-artifact-transfer to version 0.9.1</li>
<li><a href="https://issues.apache.org/jira/browse/MINSTALL-140">MINSTALL-140</a> &ndash; maven-shared-utils 3.1.0 to 3.2.0</li>
<li><a href="https://issues.apache.org/jira/browse/MINSTALL-141">MINSTALL-141</a> &ndash; plexus-utils 3.0.24 to 3.1.0</li>
<li><a href="https://issues.apache.org/jira/browse/MINSTALL-142">MINSTALL-142</a> &ndash; Upgrade parent to 31</li>
<li><a href="https://issues.apache.org/jira/browse/MINSTALL-144">MINSTALL-144</a> &ndash; Upgrade mave-surefire/failsafe-plugin 2.21.0</li>
<li><a href="https://issues.apache.org/jira/browse/MINSTALL-146">MINSTALL-146</a> &ndash; Upgrade maven-plugin parent to version 32</li>
<li><a href="https://issues.apache.org/jira/browse/MINSTALL-147">MINSTALL-147</a> &ndash; Upgrade JUnit to 4.12</li>
</ul>


<p>Enjoy,</p>

<p>-The Apache Maven team</p>
