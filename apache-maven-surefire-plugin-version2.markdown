---
layout: post
title: Apache Maven Surefire Plugin Version 2.22.2 Released
date: '2019-05-06T10:13:42+00:00'
permalink: apache-maven-surefire-plugin-version2
---
<div class="entry-content"><p>The Apache Maven team is pleased to announce the release of the
    <a href="http://maven.apache.org/plugins/maven-surefire-plugin/">Apache Maven Surefire Plugin, version 2.22.2</a>.</p>

    <p>The release contains 17 bug fixes.
        Again we received contributions from the community in form of bug reports
        and bug fixes.
        Thank you and keep them coming!</p>

    <p>You should specify the version in your project&rsquo;s plugin configuration:</p>

    <figure class='code'><figcaption><span></span></figcaption><div class="highlight"><table><tr><td class="gutter"><pre class="line-numbers"><span class='line-number'>1</span>
<span class='line-number'>2</span>
<span class='line-number'>3</span>
<span class='line-number'>4</span>
<span class='line-number'>5</span>
</pre></td><td class='code'><pre><code class='xml'><span class='line'><span class="nt">&lt;plugin&gt;</span>
</span><span class='line'>  <span class="nt">&lt;groupId&gt;</span>org.apache.maven.plugins<span class="nt">&lt;/groupId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;artifactId&gt;</span>maven-surefire-plugin<span class="nt">&lt;/artifactId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;version&gt;</span>2.22.2<span class="nt">&lt;/version&gt;</span>
</span><span class='line'><span class="nt">&lt;/plugin&gt;</span>
</span></code></pre></td></tr></table></div></figure>


    <p>or for failsafe:</p>

    <figure class='code'><figcaption><span></span></figcaption><div class="highlight"><table><tr><td class="gutter"><pre class="line-numbers"><span class='line-number'>1</span>
<span class='line-number'>2</span>
<span class='line-number'>3</span>
<span class='line-number'>4</span>
<span class='line-number'>5</span>
</pre></td><td class='code'><pre><code class='xml'><span class='line'><span class="nt">&lt;plugin&gt;</span>
</span><span class='line'>  <span class="nt">&lt;groupId&gt;</span>org.apache.maven.plugins<span class="nt">&lt;/groupId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;artifactId&gt;</span>maven-failsafe-plugin<span class="nt">&lt;/artifactId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;version&gt;</span>2.22.2<span class="nt">&lt;/version&gt;</span>
</span><span class='line'><span class="nt">&lt;/plugin&gt;</span>
</span></code></pre></td></tr></table></div></figure>


    <p>or for surefire-report:</p>

    <figure class='code'><figcaption><span></span></figcaption><div class="highlight"><table><tr><td class="gutter"><pre class="line-numbers"><span class='line-number'>1</span>
<span class='line-number'>2</span>
<span class='line-number'>3</span>
<span class='line-number'>4</span>
<span class='line-number'>5</span>
</pre></td><td class='code'><pre><code class='xml'><span class='line'><span class="nt">&lt;plugin&gt;</span>
</span><span class='line'>  <span class="nt">&lt;groupId&gt;</span>org.apache.maven.plugins<span class="nt">&lt;/groupId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;artifactId&gt;</span>maven-surefire-report-plugin<span class="nt">&lt;/artifactId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;version&gt;</span>2.22.2<span class="nt">&lt;/version&gt;</span>
</span><span class='line'><span class="nt">&lt;/plugin&gt;</span>
</span></code></pre></td></tr></table></div></figure>




    <!-- more -->


    <p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317927&amp;version=12343425">Release Notes &ndash; Maven Surefire &ndash; Version 2.22.2</a></p>

    <p>Bugs:</p>

    <ul>
        <li><a href="https://issues.apache.org/jira/browse/SUREFIRE-1614">SUREFIRE-1614</a>&ndash; JUnit Runner that writes to System.out corrupts Surefire&rsquo;s STDOUT when using JUnit&rsquo;s Vintage Engine</li>
    </ul>


    <p>Enjoy,</p>

    <p>-The Apache Maven team</p>
</div>
