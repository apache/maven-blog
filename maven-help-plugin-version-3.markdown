---
layout: post
title: Maven Help Plugin Version 3.0.0 Released
date: '2018-03-18T09:42:47+00:00'
permalink: maven-help-plugin-version-3
---
<div class="entry-content"><p>The Apache Maven team is pleased to announce the release of the
<a href="http://maven.apache.org/plugins/maven-help-plugin/">Apache Maven Help Plugin, version 3.0.0</a></p>

<p>The Maven Help Plugin is used to get relative information about a project or
the system. It can be used to get a description of a particular plugin,
including the plugin&rsquo;s goals with their parameters and component requirements,
the effective POM and effective settings of the current build, and the profiles
applied to the current project being built.</p>

<p>You should specify the version in your project&rsquo;s plugin configuration:</p>

<figure class='code'><figcaption><span></span></figcaption><div class="highlight"><table><tr><td class="gutter"><pre class="line-numbers"><span class='line-number'>1</span>
<span class='line-number'>2</span>
<span class='line-number'>3</span>
<span class='line-number'>4</span>
<span class='line-number'>5</span>
</pre></td><td class='code'><pre><code class='xml'><span class='line'><span class="nt">&lt;plugin&gt;</span>
</span><span class='line'>  <span class="nt">&lt;groupId&gt;</span>org.apache.maven.plugins<span class="nt">&lt;/groupId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;artifactId&gt;</span>maven-help-plugin<span class="nt">&lt;/artifactId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;version&gt;</span>3.0.0<span class="nt">&lt;/version&gt;</span>
</span><span class='line'><span class="nt">&lt;/plugin&gt;</span>
</span></code></pre></td></tr></table></div></figure>


<p>You can download the appropriate <a href="https://maven.apache.org/plugins/maven-help-plugin/download.cgi">sources etc. from the download page</a>.</p>

<!-- more -->


<p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317522&amp;version=12330788">Release Notes &ndash; Maven Help Plugin &ndash; Version 3.0.0</a></p>

<p>Bugs:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MPH-53">MPH-53</a> &ndash; mvn help:describe returns the version that is specified in metadata instead of  the one in the parent pom</li>
<li><a href="https://issues.apache.org/jira/browse/MPH-87">MPH-87</a> &ndash; help:effective-pom/effective-settings uses platform encoding and garbles non-ASCII characters, emits invalid XML</li>
<li><a href="https://issues.apache.org/jira/browse/MPH-97">MPH-97</a> &ndash; [Patch] maven-help-plugin does not build with latest version of maven-plugin-testing-harness</li>
<li><a href="https://issues.apache.org/jira/browse/MPH-99">MPH-99</a> &ndash; Evaluate has no output in quiet mode</li>
<li><a href="https://issues.apache.org/jira/browse/MPH-105">MPH-105</a> &ndash; Effective pom aggregation is not triggered</li>
<li><a href="https://issues.apache.org/jira/browse/MPH-107">MPH-107</a> &ndash; Mojos use inconsistent line endings throughout</li>
<li><a href="https://issues.apache.org/jira/browse/MPH-108">MPH-108</a> &ndash; Patch for MPH-72 not fully applied</li>
<li><a href="https://issues.apache.org/jira/browse/MPH-110">MPH-110</a> &ndash; Cannot run ITs successfully</li>
<li><a href="https://issues.apache.org/jira/browse/MPH-111">MPH-111</a> &ndash; IT &lsquo;effective-pom_properties&rsquo; fails if run with -Dinvoker.mergeUserSettings</li>
<li><a href="https://issues.apache.org/jira/browse/MPH-114">MPH-114</a> &ndash; Goal fails with “Unable to get the POM for the artifact”</li>
<li><a href="https://issues.apache.org/jira/browse/MPH-119">MPH-119</a> &ndash; The &ldquo;artifact&rdquo; parameter is not taken into account with Maven 3</li>
<li><a href="https://issues.apache.org/jira/browse/MPH-121">MPH-121</a> &ndash; incorrect text in help:describe for cmd</li>
<li><a href="https://issues.apache.org/jira/browse/MPH-123">MPH-123</a> &ndash; all-profiles does not show right active status</li>
</ul>


<p>Improvements:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MPH-106">MPH-106</a> &ndash; add gav parameter to calculate effective pom for any gav, not only reactor</li>
<li><a href="https://issues.apache.org/jira/browse/MPH-109">MPH-109</a> &ndash; Use ISO 8601 date format for the remaining goals</li>
<li><a href="https://issues.apache.org/jira/browse/MPH-116">MPH-116</a> &ndash; Printout the information if a goal is a report goal or not</li>
<li><a href="https://issues.apache.org/jira/browse/MPH-120">MPH-120</a> &ndash; Migrate plugin to Maven 3.0</li>
<li><a href="https://issues.apache.org/jira/browse/MPH-124">MPH-124</a> &ndash; Show parameter aliases in describe goal</li>
</ul>


<p>Tasks:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MPH-103">MPH-103</a> &ndash; Remove unused dependency maven-monitor</li>
<li><a href="https://issues.apache.org/jira/browse/MPH-112">MPH-112</a> &ndash; Upgrade to Commons Lang3</li>
<li><a href="https://issues.apache.org/jira/browse/MPH-126">MPH-126</a> &ndash; Require Java 7</li>
<li><a href="https://issues.apache.org/jira/browse/MPH-132">MPH-132</a> &ndash; Drop parameter &lsquo;medium&rsquo;</li>
<li><a href="https://issues.apache.org/jira/browse/MPH-133">MPH-133</a> &ndash; Drop deprecated alias &lsquo;full&rsquo;</li>
<li><a href="https://issues.apache.org/jira/browse/MPH-134">MPH-134</a> &ndash; Drop deprecated alias &lsquo;mojo&rsquo;</li>
</ul>


<p>Dependency upgrades:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MPH-102">MPH-102</a> &ndash; Upgrade to maven-plugins parent version 27</li>
<li><a href="https://issues.apache.org/jira/browse/MPH-104">MPH-104</a> &ndash; Upgrade maven-plugin-testing-harness to 1.3</li>
<li><a href="https://issues.apache.org/jira/browse/MPH-117">MPH-117</a> &ndash; Upgrade plexus-utils to 3.0.22</li>
<li><a href="https://issues.apache.org/jira/browse/MPH-118">MPH-118</a> &ndash; Upgrade maven-plugins to version 30</li>
<li><a href="https://issues.apache.org/jira/browse/MPH-125">MPH-125</a> &ndash; Upgrade parent to 31</li>
<li><a href="https://issues.apache.org/jira/browse/MPH-127">MPH-127</a> &ndash; Upgrade Maven  Artifact Transfer to 0.9.1</li>
<li><a href="https://issues.apache.org/jira/browse/MPH-128">MPH-128</a> &ndash; Upgrade Maven Reporting Exec to 1.4</li>
<li><a href="https://issues.apache.org/jira/browse/MPH-129">MPH-129</a> &ndash; Upgrade Plexus Utils to 3.1.0</li>
<li><a href="https://issues.apache.org/jira/browse/MPH-130">MPH-130</a> &ndash; Upgrade XStream to 1.4.7</li>
<li><a href="https://issues.apache.org/jira/browse/MPH-131">MPH-131</a> &ndash; Ugprade Commons Lang to 3.7</li>
</ul>


<p>Enjoy,</p>

<p>-The Apache Maven team</p>
</div>
