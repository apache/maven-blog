---
layout: post
title: Apache Maven SCM Version 2.0.0-M2 Released
date: '2022-07-30T20:18:18+00:00'
permalink: apache-maven-scm-version-21
---
  <div class="post_body"><p>The Apache Maven team is pleased to announce the release of the
<a href="https://maven.apache.org/scm/">Apache Maven SCM, version 2.0.0-M2</a>.</p>
<p>Maven SCM supports Maven plugins (for example maven-release-plugin) and other tools by providing
them with a common API for source code management operations. You can look at the list of SCMs for
more information on using Maven SCM with your favorite SCM tool.</p>
<p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317828&amp;version=12351598">Release Notes - Maven SCM Version 2.0.0-M2</a></p>
<ul>
<li>
<p>Bugs:</p>
<ul>
<li><a href="https://issues.apache.org/jira/browse/SCM-807">SCM-807</a> - JGit impl check-in fails unless the Maven project is in the working copy root</li>
<li><a href="https://issues.apache.org/jira/browse/SCM-913">SCM-913</a> - NPE on ChangeSet.toString() when no mergedRevisions are set</li>
<li><a href="https://issues.apache.org/jira/browse/SCM-945">SCM-945</a> - Support OpenSSH private keys with maven-scm-provider-jgit</li>
<li><a href="https://issues.apache.org/jira/browse/SCM-976">SCM-976</a> - GitExe changelog does not work in if the user has defined a custom format</li>
<li><a href="https://issues.apache.org/jira/browse/SCM-981">SCM-981</a> - Several integration tests are never run and fail if you do</li>
<li><a href="https://issues.apache.org/jira/browse/SCM-986">SCM-986</a> - SvnExe's SvnRemoteInfoCommand incorrectly implemented</li>
<li><a href="https://issues.apache.org/jira/browse/SCM-991">SCM-991</a> - GitDiffConsumer cannot parse moved files</li>
</ul>
</li>
<li>
<p>New Feature:</p>
<ul>
<li><a href="https://issues.apache.org/jira/browse/SCM-977">SCM-977</a> - Support for retrieving tags from the changelog</li>
</ul>
</li>
<li>
<p>Improvements:</p>
<ul>
<li><a href="https://issues.apache.org/jira/browse/SCM-925">SCM-925</a> - Implement RemoveCommand in maven-scm-provider-jgit with TCK test for all providers</li>
<li><a href="https://issues.apache.org/jira/browse/SCM-942">SCM-942</a> - No run-its, tck-local and tck-hg profiles</li>
<li><a href="https://issues.apache.org/jira/browse/SCM-943">SCM-943</a> - scm:check-local-modification does not support excludes</li>
<li><a href="https://issues.apache.org/jira/browse/SCM-992">SCM-992</a> - Support explicitly configured SSH private key for gitexe provider</li>
<li><a href="https://issues.apache.org/jira/browse/SCM-993">SCM-993</a> - Add tests for SSH private key-based authentication during checkout (clone)</li>
<li><a href="https://issues.apache.org/jira/browse/SCM-994">SCM-994</a> - Add JGit CredentialsProvider based on Plexus Interactivity API</li>
<li><a href="https://issues.apache.org/jira/browse/SCM-999">SCM-999</a> - Document provider IDs</li>
</ul>
</li>
<li>
<p>Test:</p>
<ul>
<li><a href="https://issues.apache.org/jira/browse/SCM-989">SCM-989</a> - Tests fail if svn and/or git are not installed</li>
</ul>
</li>
<li>
<p>Tasks:</p>
<ul>
<li><a href="https://issues.apache.org/jira/browse/SCM-979">SCM-979</a> - Replace Plexus Container Default with Sisu Plexus Shim</li>
<li><a href="https://issues.apache.org/jira/browse/SCM-980">SCM-980</a> - Remove code duplication in ListMojo</li>
<li><a href="https://issues.apache.org/jira/browse/SCM-983">SCM-983</a> - Drop SCM Logger in favor of SLF4J</li>
<li><a href="https://issues.apache.org/jira/browse/SCM-984">SCM-984</a> - Replace use of JUnit 3 PlexusTestCase with Junit 4</li>
<li><a href="https://issues.apache.org/jira/browse/SCM-985">SCM-985</a> - Drop/replace usage of Commons Lang 2</li>
<li><a href="https://issues.apache.org/jira/browse/SCM-995">SCM-995</a> - Upgrade JGit to 5.13.1 and leverage Apache Mina SSHD instead of JSch</li>
</ul>
</li>
<li>
<p>Dependency upgrades:</p>
<ul>
<li><a href="https://issues.apache.org/jira/browse/SCM-978">SCM-978</a> - Upgrade Maven prerequisite to 3.2.5</li>
<li><a href="https://issues.apache.org/jira/browse/SCM-982">SCM-982</a> - Upgrade to Java 8</li>
</ul>
</li>
</ul>
<p>Enjoy,</p>
<p>-The Apache Maven team</p>

    </div>
