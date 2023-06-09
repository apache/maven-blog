---
layout: post
title: Apache Maven Wagon 3.2.0 Released
date: '2018-09-29T00:00:00+00:00'
permalink: apache-maven-wagon-3-2
---
<div class="entry-content"><p>The Apache Maven team is pleased to announce the release of
<a href="https://maven.apache.org/wagon/">Apache Maven Wagon 3.2.0</a>.</p>

<p>Apache Maven Wagon is a transport abstraction that is used in Mavens
artifact and repository handling code.</p>

<p>You can download the appropriate sources etc. from the <a href="https://maven.apache.org/wagon/download.cgi">download page</a>.</p>

<!-- more -->


<p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12318122&amp;version=12343926">Release Notes &ndash; Maven Wagon &ndash; Version 3.2.0</a></p>

<p>Bugs:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/WAGON-478">WAGON-478</a> &ndash; WebDavWagon accepts SC_OK for MKCOL</li>
<li><a href="https://issues.apache.org/jira/browse/WAGON-486">WAGON-486</a> &ndash; Wagon fails to download artifacts if number of dropped pooled connections (by intermediate) are greater than default retry count</li>
<li><a href="https://issues.apache.org/jira/browse/WAGON-500">WAGON-500</a> &ndash; Re-enable ScmCvsExeWagonTest</li>
</ul>


<p>New Features:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/WAGON-526">WAGON-526</a> &ndash; Make the retry handling of HttpClient configurable</li>
<li><a href="https://issues.apache.org/jira/browse/WAGON-531">WAGON-531</a> &ndash; Add default TTL for HTTP connections</li>
</ul>


<p>Improvement:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/WAGON-525">WAGON-525</a> &ndash; Support for detecting and using of KiTTY&rsquo;s klink.exe and kscp.exe</li>
</ul>


<p>Tasks:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/WAGON-527">WAGON-527</a> &ndash; Drop custom user agent in WebDAV Wagon</li>
<li><a href="https://issues.apache.org/jira/browse/WAGON-528">WAGON-528</a> &ndash; Extend and unify compression capabilities in HTTP (Lightweight) Wagon</li>
<li><a href="https://issues.apache.org/jira/browse/WAGON-529">WAGON-529</a> &ndash; Clean up inconsistent status code and reason phrase handling</li>
<li><a href="https://issues.apache.org/jira/browse/WAGON-530">WAGON-530</a> &ndash; Drop invalid header &lsquo;Expires&rsquo;</li>
</ul>


<p>Dependency upgrades:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/WAGON-532">WAGON-532</a> &ndash; Upgrade Maven SCM to 1.11.1</li>
<li><a href="https://issues.apache.org/jira/browse/WAGON-533">WAGON-533</a> &ndash; Upgrade HttpCore to 4.4.10</li>
<li><a href="https://issues.apache.org/jira/browse/WAGON-534">WAGON-534</a> &ndash; Upgrade HttpClient to 4.5.6</li>
<li><a href="https://issues.apache.org/jira/browse/WAGON-535">WAGON-535</a> &ndash; Upgrade EasyMock to 3.6</li>
<li><a href="https://issues.apache.org/jira/browse/WAGON-536">WAGON-536</a> &ndash; Upgrade parent to 32</li>
</ul>


<p>Enjoy,</p>

<p>-The Apache Maven team</p>
</div>
