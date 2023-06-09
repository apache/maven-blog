---
layout: post
title: Apache Maven SCM Version 1.10.0 Released
date: '2018-05-28T17:01:42+00:00'
permalink: apache-maven-scm-version-1
---
<div class="entry-content"><p>The Apache Maven team is pleased to announce the release of the
<a href="https://maven.apache.org/scm/">Apache Maven SCM, version 1.10.0</a>.</p>

<p>Maven SCM supports Maven 2.x plugins (e.g. maven-release-plugin) and other
tools (e.g. Continuum) by providing them with a common API for doing SCM
operations. You can look at the list of SCMs for more information on using
Maven SCM with your favorite SCM tool.</p>

<!-- more -->


<p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317828&amp;version=12335750">Release Notes &ndash; Maven SCM Version 1.10.0</a></p>

<p>Bugs:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/SCM-763">SCM-763</a> &ndash; Password masking for svnexe does not handle all cases</li>
<li><a href="https://issues.apache.org/jira/browse/SCM-797">SCM-797</a> &ndash; gitexe checkIn() fails due to Windows command line length limitation</li>
<li><a href="https://issues.apache.org/jira/browse/SCM-814">SCM-814</a> &ndash; Dead links on Maven SCM plugin usage page and Maven SCM Providers Matrix page</li>
<li><a href="https://issues.apache.org/jira/browse/SCM-818">SCM-818</a> &ndash; Updating doesn&rsquo;t work when in detached HEAD</li>
<li><a href="https://issues.apache.org/jira/browse/SCM-821">SCM-821</a> &ndash; fix incorrect resolving of branch name from HG outgoing changes &amp;&amp; NPE in HgUtils.differentOutgoingBranchFound</li>
<li><a href="https://issues.apache.org/jira/browse/SCM-829">SCM-829</a> &ndash; CommandParameter incorrectly removed from parameter list</li>
<li><a href="https://issues.apache.org/jira/browse/SCM-836">SCM-836</a> &ndash; scm:bootstrap throws NPE</li>
<li><a href="https://issues.apache.org/jira/browse/SCM-846">SCM-846</a> &ndash; userInfo in Git HTTP URLs not escaped according to RFC 3986</li>
<li><a href="https://issues.apache.org/jira/browse/SCM-862">SCM-862</a> &ndash; apache-rat complains about Eclipse .checkstyle files</li>
<li><a href="https://issues.apache.org/jira/browse/SCM-863">SCM-863</a> &ndash; NPE in GlobalOptions.setCVSRoot(null) with newer cvsclient</li>
<li><a href="https://issues.apache.org/jira/browse/SCM-865">SCM-865</a> &ndash; cvsnt: rls: invalid option &mdash; d</li>
<li><a href="https://issues.apache.org/jira/browse/SCM-866">SCM-866</a> &ndash; Cvs ScmProvider.list() does not return correct entries</li>
<li><a href="https://issues.apache.org/jira/browse/SCM-867">SCM-867</a> &ndash; ScmWagon has no way to work with CVS and SVN in binary mode</li>
<li><a href="https://issues.apache.org/jira/browse/SCM-868">SCM-868</a> &ndash; gitexe add() does not return added files when invoked in subdir</li>
<li><a href="https://issues.apache.org/jira/browse/SCM-869">SCM-869</a> &ndash; gitexe list() implemented incorrectly</li>
<li><a href="https://issues.apache.org/jira/browse/SCM-874">SCM-874</a> &ndash; ScmResult output password masking does not handle multiline text</li>
<li><a href="https://issues.apache.org/jira/browse/SCM-875">SCM-875</a> &ndash; GitUpdateCommand assumes master branch by default</li>
<li><a href="https://issues.apache.org/jira/browse/SCM-878">SCM-878</a> &ndash; AbstractConsumer#parseDate() logs wrong locale in case of a ParseException</li>
<li><a href="https://issues.apache.org/jira/browse/SCM-879">SCM-879</a> &ndash; JazzChangeLogCommandTest#testListChangesetConsumerWithTimeOnly() fails with NPE on Java 10</li>
<li><a href="https://issues.apache.org/jira/browse/SCM-881">SCM-881</a> &ndash; ScmWagon has no way to work with SVN in binary mode</li>
<li><a href="https://issues.apache.org/jira/browse/SCM-882">SCM-882</a> &ndash; ScmWagon has no way to work with GIT in binary mode</li>
<li><a href="https://issues.apache.org/jira/browse/SCM-886">SCM-886</a> &ndash; Tests with checkin rely on global git config</li>
<li><a href="https://issues.apache.org/jira/browse/SCM-887">SCM-887</a> &ndash; Plexus Utils 3.0.24 makes some tests fail</li>
<li><a href="https://issues.apache.org/jira/browse/SCM-888">SCM-888</a> &ndash; Changelog generation fails on Windows with Mercurial SCM</li>
</ul>


<p>Improvements:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/SCM-739">SCM-739</a> &ndash; Release Plugin: Use &ldquo;git &mdash;depth 1&rdquo; When Checking Out</li>
<li><a href="https://issues.apache.org/jira/browse/SCM-748">SCM-748</a> &ndash; Automatically create parent dirs with &lsquo;svn &mdash;parents&rsquo;</li>
<li><a href="https://issues.apache.org/jira/browse/SCM-855">SCM-855</a> &ndash; Upgrade to Java 7</li>
<li><a href="https://issues.apache.org/jira/browse/SCM-873">SCM-873</a> &ndash; Improve documentation on svn-settings.xml and git-settings.xml</li>
<li><a href="https://issues.apache.org/jira/browse/SCM-884">SCM-884</a> &ndash; Upgrade jgit to last version of java 7 release (4.5.0.201609210915-r)</li>
<li><a href="https://issues.apache.org/jira/browse/SCM-885">SCM-885</a> &ndash; Extend GitChangeLogCommand by using revision only</li>
</ul>


<p>Task:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/SCM-876">SCM-876</a> &ndash; switch from Git-WIP to Gitbox</li>
</ul>


<p>Dependency upgrade:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/SCM-824">SCM-824</a> &ndash; Upgrade Plexus Utils to 3.0.24</li>
</ul>


<p>Enjoy,</p>

<p>-The Apache Maven team</p>
</div>


