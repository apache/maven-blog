---
layout: post
title: Apache Maven Site Plugin, version 3.9.1 Released
date: '2020-06-26T17:34:50+00:00'
permalink: apache-maven-site-plugin-version1
---
<div class="entry-content"><p>The Apache Maven team is pleased to announce the release of the
  <a href="https://maven.apache.org/plugins/maven-site-plugin/">Apache Maven Site Plugin, version 3.9.1</a>.</p>

  <p>The Site Plugin is used to generate a site for the project. The generated site
    also includes the project&rsquo;s reports that were configured in the POM.</p>

  <p>You can download the appropriate sources etc. from the download page:</p>

  <p><a href="https://maven.apache.org/plugins/maven-site-plugin/download.cgi">https://maven.apache.org/plugins/maven-site-plugin/download.cgi</a></p>

  <figure class='code'><figcaption><span></span></figcaption><div class="highlight"><table><tr><td class="gutter"><pre class="line-numbers"><span class='line-number'>1</span>
<span class='line-number'>2</span>
<span class='line-number'>3</span>
<span class='line-number'>4</span>
<span class='line-number'>5</span>
</pre></td><td class='code'><pre><code class='xml'><span class='line'><span class="nt">&lt;plugin&gt;</span>
</span><span class='line'>  <span class="nt">&lt;groupId&gt;</span>org.apache.maven.plugins<span class="nt">&lt;/groupId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;artifactId&gt;</span>maven-site-plugin<span class="nt">&lt;/artifactId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;version&gt;</span>3.9.1<span class="nt">&lt;/version&gt;</span>
</span><span class='line'><span class="nt">&lt;/plugin&gt;</span>
</span></code></pre></td></tr></table></div></figure>


  <!-- more -->


  <p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317923&amp;version=12347781">Release Notes &ndash; Maven Site Plugin &ndash; Version 3.9.1</a></p>

  <ul>
    <li><p>Bugs:</p>

      <ul>
        <li><a href="https://issues.apache.org/jira/browse/MSITE-856">MSITE-856</a> &ndash; NullPointer on org.apache.maven.plugins.site.render.SiteMap.relativePath</li>
        <li><a href="https://issues.apache.org/jira/browse/MSITE-863">MSITE-863</a> &ndash; NoSuchMethodError: &lsquo;Xpp3Dom.getInputLocation()&rsquo; when running reports with Maven versions &lt; 3.6.1</li>
      </ul>
    </li>
    <li><p>Improvements:</p>

      <ul>
        <li><a href="https://issues.apache.org/jira/browse/MSITE-845">MSITE-845</a> &ndash; Drop Maven 2 support</li>
        <li><a href="https://issues.apache.org/jira/browse/MSITE-862">MSITE-862</a> &ndash; log Doxia source when rendering with site:run</li>
      </ul>
    </li>
    <li><p>Task:</p>

      <ul>
        <li><a href="https://issues.apache.org/jira/browse/MSITE-757">MSITE-757</a> &ndash; drop Maven 2 support</li>
      </ul>
    </li>
  </ul>


  <p>Enjoy,</p>

  <p>-The Apache Maven team</p>
</div>
