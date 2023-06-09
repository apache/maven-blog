---
layout: post
title: Apache Maven Help Plugin Version 3.0.1 Released
date: '2018-03-28T17:29:11+00:00'
permalink: apache-maven-help-plugin-version
---
<div class="entry-content"><p>The Apache Maven team is pleased to announce the release of the
<a href="http://maven.apache.org/plugins/maven-help-plugin/">Apache Maven Help Plugin, version 3.0.1</a></p>

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
</span><span class='line'>  <span class="nt">&lt;version&gt;</span>3.0.1<span class="nt">&lt;/version&gt;</span>
</span><span class='line'><span class="nt">&lt;/plugin&gt;</span>
</span></code></pre></td></tr></table></div></figure>


<p>You can download the appropriate <a href="https://maven.apache.org/plugins/maven-help-plugin/download.cgi">sources etc. from the download page</a>.</p>

<!-- more -->


<p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317522&amp;version=12342960">Release Notes &ndash; Maven Help Plugin &ndash; Version 3.0.1</a></p>

<p>Bugs:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MPH-135">MPH-135</a> &ndash; help:effective-pom crashes with NPE in multi module builds with -Doutput set</li>
<li><a href="https://issues.apache.org/jira/browse/MPH-139">MPH-139</a> &ndash; Invalid default namespace set for effective settings</li>
<li><a href="https://issues.apache.org/jira/browse/MPH-140">MPH-140</a> &ndash; Multiple XML declarations written</li>
</ul>


<p>Tasks:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MPH-137">MPH-137</a> &ndash; Use JDOM&rsquo;s PrettyFormatter throughout</li>
<li><a href="https://issues.apache.org/jira/browse/MPH-138">MPH-138</a> &ndash; Drop AbstractEffectiveMojo#addMavenNamespace()</li>
<li><a href="https://issues.apache.org/jira/browse/MPH-141">MPH-141</a> &ndash; Use non-deprecated field in DateFormatUtils</li>
</ul>


<p>Dependency upgrade:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MPH-136">MPH-136</a> &ndash; Upgrade JDOM to 1.1.3</li>
</ul>


<p>Enjoy,</p>

<p>-The Apache Maven team</p>
</div>
