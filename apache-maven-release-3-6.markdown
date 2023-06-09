---
layout: post
title: Apache Maven Release 3.6.0
date: '2018-11-01T13:05:00+00:00'
permalink: apache-maven-release-3-6
---
<div class="entry-content"><p>The Apache Maven team is pleased to announce the release of the Apache
Maven 3.6.0.</p>

<p>Apache Maven is a software project management and comprehension tool. Based
on the concept of a project object model (POM), Maven can manage a
project&rsquo;s build, reporting and documentation from a central piece of
information.</p>

<p>You can find out more about Apache Maven at <a href="https://maven.apache.org">https://maven.apache.org</a></p>

<p>You can download the appropriate sources etc. from
the <a href="https://maven.apache.org/download.cgi">download page</a></p>

<!-- more -->


<p>Code Contributors of this release:</p>

<ul>
<li>Christoph Kunze</li>
<li>David Churcher</li>
</ul>


<p>Issue Reporters of this release:</p>

<ul>
<li>Richard van der Hoff</li>
<li>Jörg Sesterhenn</li>
<li>Andreas Sewe</li>
<li>David Churcher</li>
<li>Adam John Burley</li>
<li>Alexander Griesbaum</li>
<li>Christoph Amshoff</li>
<li>Seckin Onur Selamet</li>
<li>Phillip Webb</li>
<li>John Canny</li>
<li>Hoa Phan</li>
</ul>


<p>Many thanks to contributors and reporters for the support and time.</p>

<p>Participants to the VOTE of the Maven 3.6.0 Release:</p>

<ul>
<li>Filipe Sousa</li>
<li>Eric Lilja</li>
<li>Enrico Olivelli</li>
<li>Gary Gregory</li>
<li>Thomas Collignon</li>
</ul>


<p>Many thanks to those who tested the Maven releases
and thanks for their support as well.</p>

<p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12316922&amp;version=12338966">Release Notes &ndash; Maven &ndash; Version 3.6.0</a></p>

<p>Bugs:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MNG-6311">MNG-6311</a> &ndash; Maven intolerably slow when import scope used heavily in large project</li>
<li><a href="https://issues.apache.org/jira/browse/MNG-6358">MNG-6358</a> &ndash; Maven build should not require access to apache.org</li>
<li><a href="https://issues.apache.org/jira/browse/MNG-6383">MNG-6383</a> &ndash; ProjectBuilder unnecessarily rebuilds modules with ci-friendly versions</li>
<li><a href="https://issues.apache.org/jira/browse/MNG-6412">MNG-6412</a> &ndash; Exceeding project discovery time when using CI friendly versions</li>
<li><a href="https://issues.apache.org/jira/browse/MNG-6415">MNG-6415</a> &ndash; Project Artifacts Cache does not retain the order of classpath entries.</li>
<li><a href="https://issues.apache.org/jira/browse/MNG-6472">MNG-6472</a> &ndash; Mockito cannot mock this class: interface org.eclipse.aether.impl.RepositoryEventDispatcher</li>
<li><a href="https://issues.apache.org/jira/browse/MNG-6490">MNG-6490</a> &ndash; Maven shall not fail reporting circular dependency when the dependency is a classified secondary artifact</li>
</ul>


<p>Improvements:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MNG-4508">MNG-4508</a> &ndash; No way to avoid adding artifactId to site urls</li>
<li><a href="https://issues.apache.org/jira/browse/MNG-5951">MNG-5951</a> &ndash; add an option to avoid path addition to inherited URLs</li>
<li><a href="https://issues.apache.org/jira/browse/MNG-6059">MNG-6059</a> &ndash; Important use cases not covered, as child.inherit.append.path affects all children</li>
<li><a href="https://issues.apache.org/jira/browse/MNG-6164">MNG-6164</a> &ndash; Collections inconsistently immutable</li>
<li><a href="https://issues.apache.org/jira/browse/MNG-6391">MNG-6391</a> &ndash; Printout version of last built module in reactor build</li>
<li><a href="https://issues.apache.org/jira/browse/MNG-6414">MNG-6414</a> &ndash; Add more Apache license header patterns to skip downloading Apache license</li>
<li><a href="https://issues.apache.org/jira/browse/MNG-6467">MNG-6467</a> &ndash; Remove plugin definition from pom file which is inherited</li>
<li><a href="https://issues.apache.org/jira/browse/MNG-6480">MNG-6480</a> &ndash; Eclipse.org site is down, and you are unable to build Maven?</li>
<li><a href="https://issues.apache.org/jira/browse/MNG-6492">MNG-6492</a> &ndash; Minor improvement on Array construction, converson</li>
</ul>


<p>Task:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MNG-6475">MNG-6475</a> &ndash; Remove guava dependencies</li>
</ul>


<p>Dependency upgrades:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MNG-6424">MNG-6424</a> &ndash; Upgrade plexus-interpolation to 1.25</li>
<li><a href="https://issues.apache.org/jira/browse/MNG-6449">MNG-6449</a> &ndash; Upgrade parent to 32</li>
<li><a href="https://issues.apache.org/jira/browse/MNG-6473">MNG-6473</a> &ndash; Update Mockito to 2.21.0</li>
<li><a href="https://issues.apache.org/jira/browse/MNG-6478">MNG-6478</a> &ndash; Upgrade parent to 33 for sha512 checksum on release</li>
<li><a href="https://issues.apache.org/jira/browse/MNG-6479">MNG-6479</a> &ndash; Upgrade XMLUnit to 2.2.1</li>
<li><a href="https://issues.apache.org/jira/browse/MNG-6486">MNG-6486</a> &ndash; Upgrade to Wagon 3.2.0</li>
<li><a href="https://issues.apache.org/jira/browse/MNG-6489">MNG-6489</a> &ndash; Upgrade Maven Resolver to 1.3.0</li>
<li><a href="https://issues.apache.org/jira/browse/MNG-6491">MNG-6491</a> &ndash; Upgrade commons-lang3 to 3.8.1</li>
<li><a href="https://issues.apache.org/jira/browse/MNG-6496">MNG-6496</a> &ndash; Upgrade Maven Resolver to 1.3.1</li>
<li><p><a href="https://issues.apache.org/jira/browse/MNG-6497">MNG-6497</a> &ndash; Upgrade guice to 4.2.1</p></li>
<li><p>The Apache Maven team</p></li>
</ul>
