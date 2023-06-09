---
layout: post
title: Apache Maven Project Info Reports Plugin version 3.0.0
date: '2018-06-28T18:21:54+00:00'
permalink: apache-maven-project-info-reports
---
<div class="entry-content"><p>The Apache Maven team is pleased to announce the release of the
<a href="https://maven.apache.org/plugins/maven-project-info-reports-plugin/">Maven Project Info Reports Plugin version 3.0.0</a></p>

<p>You should specify the version in your project&rsquo;s plugin configuration:</p>

<figure class='code'><figcaption><span></span></figcaption><div class="highlight"><table><tr><td class="gutter"><pre class="line-numbers"><span class='line-number'>1</span>
<span class='line-number'>2</span>
<span class='line-number'>3</span>
<span class='line-number'>4</span>
<span class='line-number'>5</span>
</pre></td><td class='code'><pre><code class='xml'><span class='line'><span class="nt">&lt;plugin&gt;</span>
</span><span class='line'>  <span class="nt">&lt;groupId&gt;</span>org.apache.maven.plugins<span class="nt">&lt;/groupId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;artifactId&gt;</span>maven-project-info-reports-plugin<span class="nt">&lt;/artifactId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;version&gt;</span>3.0.0<span class="nt">&lt;/version&gt;</span>
</span><span class='line'><span class="nt">&lt;/plugin&gt;</span>
</span></code></pre></td></tr></table></div></figure>


<p>You can download the appropriate sources etc. from the
<a href="https://maven.apache.org/plugins/maven-project-info-reports-plugin/download.cgi">download page</a>.</p>

<!-- more -->


<p></p>

<p><a href="">Release Notes &ndash; Maven Project Info Reports Plugin &ndash; Version 3.0.0</a></p>

<p>Bugs:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MPIR-348">MPIR-348</a> &ndash; Usage of HTTP in web site for git-scm.com resources cause redirects to HTTPS</li>
<li><a href="https://issues.apache.org/jira/browse/MPIR-349">MPIR-349</a> &ndash; Bad modules links in &lsquo;index/modules&rsquo; reports when &lsquo;distributionManagement.site.url&rsquo; comes from settings.xml</li>
<li><a href="https://issues.apache.org/jira/browse/MPIR-359">MPIR-359</a> &ndash; Generated links for Mercurial SCM are broken</li>
<li><a href="https://issues.apache.org/jira/browse/MPIR-362">MPIR-362</a> &ndash; Dependency Management report doesn&rsquo;t exclude system scoped dependencies</li>
<li><a href="https://issues.apache.org/jira/browse/MPIR-365">MPIR-365</a> &ndash; Failed tests on Java 9 due to error with keytool plugin &ldquo;keytool: not found&rdquo;</li>
<li><a href="https://issues.apache.org/jira/browse/MPIR-370">MPIR-370</a> &ndash; Upgrade transitive BCEL to 6.2 to avoid org.apache.bcel.classfile.ClassFormatException</li>
</ul>


<p>Improvements:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MPIR-352">MPIR-352</a> &ndash; Use protocol-agnostic URL for Gravatar</li>
<li><a href="https://issues.apache.org/jira/browse/MPIR-358">MPIR-358</a> &ndash; Add GitHub for issue management</li>
<li><a href="https://issues.apache.org/jira/browse/MPIR-366">MPIR-366</a> &ndash; Drop Maven 2 support</li>
</ul>


<p>Tasks:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MPIR-323">MPIR-323</a> &ndash; Align Mojo class names, goals and output names</li>
<li><a href="https://issues.apache.org/jira/browse/MPIR-345">MPIR-345</a> &ndash; Upgrade to Doxia 1.8</li>
<li><a href="https://issues.apache.org/jira/browse/MPIR-346">MPIR-346</a> &ndash; Upgrade to Doxia Sitetools 1.8.1</li>
<li><a href="https://issues.apache.org/jira/browse/MPIR-347">MPIR-347</a> &ndash; Upgrade to Java 6</li>
<li><a href="https://issues.apache.org/jira/browse/MPIR-350">MPIR-350</a> &ndash; Upgrade of plexus-interpolation to 1.24.</li>
<li><a href="https://issues.apache.org/jira/browse/MPIR-353">MPIR-353</a> &ndash; Upgrade parent to version 30</li>
<li><a href="https://issues.apache.org/jira/browse/MPIR-354">MPIR-354</a> &ndash; Upgrade Maven Site Plugin to version 3.5.1 for ITs</li>
<li><a href="https://issues.apache.org/jira/browse/MPIR-355">MPIR-355</a> &ndash; Upgrade dependencies which are code- and testsafe</li>
<li><a href="https://issues.apache.org/jira/browse/MPIR-356">MPIR-356</a> &ndash; Deprecate not used methods in ProjectInfoReportUtils</li>
<li><a href="https://issues.apache.org/jira/browse/MPIR-367">MPIR-367</a> &ndash; Remove Dependency Repository Locations from dependency report</li>
<li><a href="https://issues.apache.org/jira/browse/MPIR-368">MPIR-368</a> &ndash; Upgrade to Java 7</li>
<li><a href="https://issues.apache.org/jira/browse/MPIR-369">MPIR-369</a> &ndash; Drop Commons Lang for System builtins</li>
<li><a href="https://issues.apache.org/jira/browse/MPIR-372">MPIR-372</a> &ndash; Remove fields duplicating parent class members</li>
</ul>


<p>Dependency upgrades:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MPIR-361">MPIR-361</a> &ndash; Upgrade parent to 31</li>
<li><a href="https://issues.apache.org/jira/browse/MPIR-363">MPIR-363</a> &ndash; Upgrade dependencies to latest versions</li>
</ul>


<p>Enjoy,</p>

<p>-The Apache Maven team</p>
</div>
