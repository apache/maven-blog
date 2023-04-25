---
layout: post
title: 'Apache Maven Shared Component: Maven Archiver Version 3.5.2 released'
date: '2022-01-05T16:41:41+00:00'
permalink: apache-maven-shared-component-maven13
---
<div class="entry-content"><p>The Apache Maven team is pleased to announce the release of the
  <a href="https://maven.apache.org/shared/maven-archiver/">Maven Archiver, version 3.5.2</a>.</p>

  <p>The Maven Archiver is mainly used by plugins to handle packaging. The version
    numbers referenced in the Since column on this page are the version of the
    Maven Archiver component &ndash; not for any specific plugin. To see which version of
    Maven Archiver a plugin uses, go to the site for that plugin.</p>

  <p>You should specify the version in your project&rsquo;s dependency configuration:</p>

  <figure class='code'><figcaption><span></span></figcaption><div class="highlight"><table><tr><td class="gutter"><pre class="line-numbers"><span class='line-number'>1</span>
<span class='line-number'>2</span>
<span class='line-number'>3</span>
<span class='line-number'>4</span>
<span class='line-number'>5</span>
</pre></td><td class='code'><pre><code class='xml'><span class='line'><span class="nt">&lt;dependency&gt;</span>
</span><span class='line'>  <span class="nt">&lt;groupId&gt;</span>org.apache.maven.shared<span class="nt">&lt;/groupId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;artifactId&gt;</span>maven-archiver<span class="nt">&lt;/artifactId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;version&gt;</span>3.5.2<span class="nt">&lt;/version&gt;</span>
</span><span class='line'><span class="nt">&lt;/plugin&gt;</span>
</span></code></pre></td></tr></table></div></figure>


  <p>You can download the appropriate sources etc. from the <a href="https://maven.apache.org/shared/maven-archiver/download.cgi">download page</a>.</p>

  <!-- more -->


  <p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317922&amp;version=123.5.27">Release Notes &ndash; Maven Archiver &ndash; Version 3.5.2</a></p>

  <ul>
    <li><p>Bugs:</p>

      <ul>
        <li><a href="https://issues.apache.org/jira/browse/MSHARED-849">MSHARED-849</a> &ndash; archiver sorts META-INF/MANIFEST.MF before META-INF/ in ZIP header</li>
      </ul>
    </li>
    <li><p>Dependency upgrade:</p>

      <ul>
        <li><a href="https://issues.apache.org/jira/browse/MSHARED-1013">MSHARED-1013</a> &ndash; Upgrade Plexus Archiver to 4.2.7</li>
      </ul>
    </li>
  </ul>


  <p>Enjoy,</p>

  <p>-The Apache Maven team</p>
</div>

