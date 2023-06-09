---
layout: post
title: Apache Maven JXR Plugin Version 3.2.0 Released
date: '2022-03-20T21:27:29+00:00'
permalink: apache-maven-jxr-plugin-version1
---
<div class="entry-content"><p>The Apache Maven team is pleased to announce the release of the
  <a href="https://maven.apache.org/jxr/maven-jxr-plugin/">Apache Maven JXR, version 3.2.0</a>.</p>

  <p>This module generates browsable HTML pages from Java source code.</p>

  <p>You should specify the version in your project&rsquo;s plugin configuration:</p>

  <figure class='code'><figcaption><span></span></figcaption><div class="highlight"><table><tr><td class="gutter"><pre class="line-numbers"><span class='line-number'>1</span>
<span class='line-number'>2</span>
<span class='line-number'>3</span>
<span class='line-number'>4</span>
<span class='line-number'>5</span>
</pre></td><td class='code'><pre><code class='xml'><span class='line'><span class="nt">&lt;plugin&gt;</span>
</span><span class='line'>   <span class="nt">&lt;groupId&gt;</span>org.apache.maven.plugins<span class="nt">&lt;/groupId&gt;</span>
</span><span class='line'>   <span class="nt">&lt;artifactId&gt;</span>maven-jxr-plugin<span class="nt">&lt;/artifactId&gt;</span>
</span><span class='line'>   <span class="nt">&lt;version&gt;</span>3.2.0<span class="nt">&lt;/version&gt;</span>
</span><span class='line'><span class="nt">&lt;/plugin&gt;</span>
</span></code></pre></td></tr></table></div></figure>


  <p>NOTE: Special thanks for the contributions retrieved during the hackathon at JCreate.</p>

  <!-- more -->


  <p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317527&amp;version=12330848">Release Notes &ndash; Maven JXR &ndash; Version 3.2.0</a></p>

  <ul>
    <li><p>Bug:</p>

      <ul>
        <li><a href="https://issues.apache.org/jira/browse/JXR-164">JXR-164</a> &ndash; Full path to local code sources in page title</li>
      </ul>
    </li>
    <li><p>Task:</p>

      <ul>
        <li><a href="https://issues.apache.org/jira/browse/JXR-162">JXR-162</a> &ndash; Lift Minimum Java to Java 8</li>
      </ul>
    </li>
    <li><p>Dependency upgrades:</p>

      <ul>
        <li><a href="https://issues.apache.org/jira/browse/JXR-157">JXR-157</a> &ndash; Upgrade Velocity templating engine</li>
        <li><a href="https://issues.apache.org/jira/browse/JXR-163">JXR-163</a> &ndash; Require Maven 3.2.5+</li>
        <li><a href="https://issues.apache.org/jira/browse/JXR-165">JXR-165</a> &ndash; Upgrade Maven Reporting to 3.1.0</li>
        <li><a href="https://issues.apache.org/jira/browse/JXR-167">JXR-167</a> &ndash; Upgrade Parent to 35</li>
        <li><a href="https://issues.apache.org/jira/browse/JXR-168">JXR-168</a> &ndash; Dependency upgrade and cleanup</li>
      </ul>
    </li>
  </ul>


  <p>Enjoy,</p>

  <p>-The Apache Maven team</p>
</div>
