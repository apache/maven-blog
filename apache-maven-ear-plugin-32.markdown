---
layout: post
title: Apache Maven EAR Plugin 3.0.2
date: '2019-11-16T17:03:10+00:00'
permalink: apache-maven-ear-plugin-32
---
<div class="entry-content"><p>The Apache Maven team is pleased to announce the release of the
  <a href="http://maven.apache.org/plugins/maven-ear-plugin/">Apache Maven EAR Plugin, version 3.0.2</a></p>

  <p>This plugin generates Java EE Enterprise Archive (EAR) file. It can also
    generate the deployment descriptor file (e.g. application.xml).</p>

  <p>You should specify the version in your project&rsquo;s plugin configuration:</p>

  <figure class='code'><figcaption><span></span></figcaption><div class="highlight"><table><tr><td class="gutter"><pre class="line-numbers"><span class='line-number'>1</span>
<span class='line-number'>2</span>
<span class='line-number'>3</span>
<span class='line-number'>4</span>
<span class='line-number'>5</span>
</pre></td><td class='code'><pre><code class='xml'><span class='line'><span class="nt">&lt;plugin&gt;</span>
</span><span class='line'>  <span class="nt">&lt;groupId&gt;</span>org.apache.maven.plugins<span class="nt">&lt;/groupId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;artifactId&gt;</span>maven-ear-plugin<span class="nt">&lt;/artifactId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;version&gt;</span>3.0.2<span class="nt">&lt;/version&gt;</span>
</span><span class='line'><span class="nt">&lt;/plugin&gt;</span>
</span></code></pre></td></tr></table></div></figure>


  <p>You can download the appropriate <a href="https://maven.apache.org/plugins/maven-ear-plugin/download.cgi">sources etc. from the download page</a>.</p>

  <!-- more -->


  <p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317422&amp;version=12343262">Release Notes &ndash; Maven EAR Plugin &ndash; Version 3.0.2</a></p>

  <p>Bug:</p>

  <ul>
    <li><a href="https://issues.apache.org/jira/browse/MEAR-273">MEAR-273</a> &ndash; Adding extra slash causing issues on eclipse editors</li>
  </ul>


  <p>Wish:</p>

  <ul>
    <li><a href="https://issues.apache.org/jira/browse/MEAR-271">MEAR-271</a> &ndash; Support lookup-name in resource-ref section</li>
  </ul>


  <p>Dependency upgrades:</p>

  <ul>
    <li><a href="https://issues.apache.org/jira/browse/MEAR-270">MEAR-270</a> &ndash; Upgrade maven-plugins parent to version 32</li>
    <li><a href="https://issues.apache.org/jira/browse/MEAR-274">MEAR-274</a> &ndash; Upgrade plexus-interpolation to 1.25</li>
    <li><a href="https://issues.apache.org/jira/browse/MEAR-275">MEAR-275</a> &ndash; Upgrade plexus-archiver to 4.1.0</li>
    <li><a href="https://issues.apache.org/jira/browse/MEAR-277">MEAR-277</a> &ndash; Upgrade maven-invoker-plugin to 3.2.1</li>
  </ul>


  <p>Enjoy,</p>

  <p>-The Apache Maven team</p>
</div>
