---
layout: post
title: Apache Maven Wagon 3.3.1 Released
date: '2019-01-06T21:43:19+00:00'
permalink: apache-maven-wagon-3-3
---
<div class="entry-content"><p>The Apache Maven team is pleased to announce the release of
<a href="https://maven.apache.org/wagon/">Apache Maven Wagon 3.3.1</a>.</p>

<p>Apache Maven Wagon is a transport abstraction that is used in Mavens
artifact and repository handling code.</p>

<p>You can download the appropriate sources etc. from the <a href="https://maven.apache.org/wagon/download.cgi">download page</a>.</p>

<!-- more -->


<p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12318122&amp;version=12344772">Release Notes &ndash; Maven Wagon &ndash; Version 3.3.1</a></p>

<p>Bugs:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/WAGON-538">WAGON-538</a> &ndash; Basic authentication fails if the password contains non-ASCII characters</li>
<li><a href="https://issues.apache.org/jira/browse/WAGON-543">WAGON-543</a> &ndash; wagon-ssh download hangs</li>
</ul>


<p>Improvements:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/WAGON-537">WAGON-537</a> &ndash; Maven transfer speed of large artifacts is slow due to unsuitable buffer strategy</li>
<li><a href="https://issues.apache.org/jira/browse/WAGON-539">WAGON-539</a> &ndash; Explicitly register only supported auth schemes</li>
<li><a href="https://issues.apache.org/jira/browse/WAGON-540">WAGON-540</a> &ndash; Switch to modern-day encoding (UTF-8) of auth credentials</li>
</ul>


<p>Task:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/WAGON-544">WAGON-544</a> &ndash; Work around JSch issue #122</li>
</ul>


<p>Enjoy,</p>

<ul>
<li>The Apache Maven team</li>
</ul>

</div>
