---
layout: post
title: Apache Maven Version 3.5.3 Released
date: '2018-03-08T16:30:40+00:00'
permalink: apache-maven-version-3-5
---
<h1>Release Notes &#x2013; Maven 3.5.3</h1>
<p>The Apache Maven team would like to announce the release of Maven 3.5.3</p>
<p>Maven 3.5.3 is <a href="../../download.html">available for download</a>.</p>
<p>Maven is a software project management and comprehension tool. Based on the concept of a project object model (POM), Maven can manage a project&#x2019;s build, reporting and documentation from a central place.</p>
<p>The core release is independent of the plugins available. Further releases of plugins will be made separately. See the <a href="../../plugins/index.html">PluginList</a> for more information.</p>
<p>We hope you enjoy using Maven! If you have any questions, please consult:</p>
<ul>

<li>the web site: <a class="externalLink" href="https://maven.apache.org/">https://maven.apache.org/</a></li>
<li>the maven-user mailing list: <a href="/mail-lists.html">https://maven.apache.org/mail-lists.html</a></li>
<li>the reference documentation: <a href="/ref/3.5.3/">https://maven.apache.org/ref/3.5.3/</a></li>
</ul>
<div class="section">
<h2><a name="Reporters_and_Contributors_of_this_release"></a>Reporters and Contributors of this release</h2>
<p>We really value the contributions of these non committers, so this section is focused on those individuals. Descriptions of the issues fixed can be found at the <a href="#Details">end of these release notes</a>.</p>
<p>Bugs:</p>
<ul>

<li><a class="externalLink" href="https://issues.apache.org/jira/browse/MNG-6323">MNG-6323</a> reporter: Ben Caradoc-Davies</li>
<li><a class="externalLink" href="https://issues.apache.org/jira/browse/MNG-6320">MNG-6320</a> reporter: Eugene Pliskin</li>
<li><a class="externalLink" href="https://issues.apache.org/jira/browse/MNG-6300">MNG-6300</a> reporter: Andreas Kurth</li>
<li><a class="externalLink" href="https://issues.apache.org/jira/browse/MNG-6298">MNG-6298</a> reporter: Ryan Heaton</li>
<li><a class="externalLink" href="https://issues.apache.org/jira/browse/MNG-6296">MNG-6296</a> reporter: Robin M&#xfc;ller</li>
<li><a class="externalLink" href="https://issues.apache.org/jira/browse/MNG-6282">MNG-6282</a> reporter: Dejan Stojadinovi&#x107;</li>
<li><a class="externalLink" href="https://issues.apache.org/jira/browse/MNG-6255">MNG-6255</a> reporter: Andrew Kennedy</li>
</ul>
<p>Improvements:</p>
<ul>

<li><a class="externalLink" href="https://issues.apache.org/jira/browse/MNG-6340">MNG-6340</a> reporter: Tony Guan</li>
<li><a class="externalLink" href="https://issues.apache.org/jira/browse/MNG-6306">MNG-6306</a> reporter: Andy Wilkinson</li>
<li><a class="externalLink" href="https://issues.apache.org/jira/browse/MNG-5992">MNG-5992</a> reporter: Ryan J. McDonough</li>
</ul>
<p>Many thanks to all reporters and contributors for their time and support.</p></div>
<div class="section">
<h2><a name="Preliminary_Testers"></a>Preliminary Testers</h2>
<p>Thank you also for your time and feedback.</p></div>
<div class="section">
<h2><a name="Known_Issues"></a>Known Issues</h2>
<p>One new issue was identified during the release testing. This issue affects Windows users. When running Maven with parallel threads, i.e. the <tt>-T</tt> command line option, Maven may output spurious ANSI escapes such as <tt>[0m [0m</tt> <a class="externalLink" href="https://issues.apache.org/jira/browse/MNG-6372">MNG-6372</a></p></div>
<div class="section">
<h2><a name="Overview_about_the_changes"></a>Overview about the changes</h2>
<ul>

<li>

<p>Issues have been fixed related to colorizations like to clean up the situation while interrupting the build process <a class="externalLink" href="https://issues.apache.org/jira/browse/MNG-6188">MNG-6188</a> and some issues related to Git Bash / Cygwin have been fixed <a class="externalLink" href="https://issues.apache.org/jira/browse/MNG-6282">MNG-6282</a> and the new options <tt>-Dstyle.color</tt> <a class="externalLink" href="https://issues.apache.org/jira/browse/MNG-6296">MNG-6296</a> has been fixed.</p>
</li>
<li>

<p>The handling CRLF in <tt>jvm.config</tt> file has been fixed <a class="externalLink" href="https://issues.apache.org/jira/browse/MNG-6255">MNG-6255</a>.</p>
</li>
<li>

<p>The wrong usage of the CI friendly version was not correctly identified which has been improved <a class="externalLink" href="https://issues.apache.org/jira/browse/MNG-6305">MNG-6305</a>.</p>
</li>
<li>

<p>Wrong encoding of non-ascii filenames has been fixed <a class="externalLink" href="https://issues.apache.org/jira/browse/MNG-6320">MNG-6320</a>.</p>
</li>
<li>

<p>Deadlock in dependency resolution has been fixed <a class="externalLink" href="https://issues.apache.org/jira/browse/MNG-6323">MNG-6323</a>.</p>
</li>
<li>

<p>A regression related to parents <tt>relativePath</tt> verification has been fixed <a class="externalLink" href="https://issues.apache.org/jira/browse/MNG-6330">MNG-6330</a>.</p>
</li>
</ul>
<p>So now some more interesting things about new (small) features:</p>
<ul>

<li>The log output contains now some progress informations related to the number of modules which looks like this <a class="externalLink" href="https://issues.apache.org/jira/browse/MNG-6302">MNG-6302</a>:</li>
</ul>

<div>
<div>
<pre class="source">[INFO] Building parent 5.0.1-SNAPSHOT                                     [1/9]
</pre></div></div>

<p>The number <tt>1</tt> is the current number which is being built where the <tt>9</tt> in this case is the number of modules which have to be built overall. So we are in module 1 of 9.</p>
<p>Furthermore the information about the packaging type and the groupId/artifactId are now being shown during the build like the following <a class="externalLink" href="https://issues.apache.org/jira/browse/MNG-6308">MNG-6308</a>:</p>

<div>
<div>
<pre class="source">[INFO] ------------------&lt; com.soebes.examples.j2ee:parent &gt;-------------------
[INFO] Building parent 5.0.1-SNAPSHOT                                     [1/9]
[INFO] --------------------------------[ pom ]---------------------------------
[INFO]
</pre></div></div>

<p>And finally we have added the version of the modules or the reactor at the end of the build <a class="externalLink" href="https://issues.apache.org/jira/browse/MNG-6352">MNG-6352</a>:</p>

<div>
<div>
<pre class="source">[INFO] ------------------------------------------------------------------------
[INFO] Reactor Summary:
[INFO]
[INFO] parent 5.0.1-SNAPSHOT .............................. SUCCESS [  0.238 s]
[INFO] domain ............................................. SUCCESS [  0.014 s]
[INFO] service-client ..................................... SUCCESS [  0.008 s]
[INFO] webgui ............................................. SUCCESS [  0.010 s]
[INFO] service ............................................ SUCCESS [  0.007 s]
[INFO] app ................................................ SUCCESS [  0.005 s]
[INFO] appasm ............................................. SUCCESS [  0.005 s]
[INFO] shade .............................................. SUCCESS [  0.006 s]
[INFO] assembly 5.0.1-SNAPSHOT ............................ SUCCESS [  0.005 s]
[INFO] ------------------------------------------------------------------------
</pre></div></div>

<p>This can be helpful if you have a large number of modules to get the information about the version being built. This meant in the past to scroll up to the last module and look there for the version. Now this can simply being seen at the end of build. If you have a multi module build where the number is the same for all modules it will be given only on the first line and the last line. If you have an aggregator build the version will be printed out for each project.</p>
<ul>

<li>One more thing has been optimized. We have removed the <tt>System.gc()</tt> call at the end of the build because this can cause costs for example on AWS systems related to the time taken to run Garbage Collection which is not really necessary <a class="externalLink" href="https://issues.apache.org/jira/browse/MNG-6340">MNG-6340</a>. This means also the resulting output will change a little bit like this:</li>
</ul>

<div>
<div>
<pre class="source">[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time: 6.111 s
[INFO] Finished at: 2018-02-25T15:34:10+01:00
[INFO] ------------------------------------------------------------------------
</pre></div></div>

<p>So there is no line anymore telling you about memory stuff.</p>
<ul>

<li>If you have used the deprecated version markers like <tt>RELEASE</tt> or <tt>LATEST</tt> this will now produce a WARNING during the build <a class="externalLink" href="https://issues.apache.org/jira/browse/MNG-6342">MNG-6342</a>.</li>
</ul></div>
<div class="section">
<h2><a name="The_detailed_issue_list"></a><a href="#Details">The detailed issue list</a></h2>
<p>Bugs:</p>
<ul>

<li><a class="externalLink" href="https://issues.apache.org/jira/browse/MNG-6188">MNG-6188</a> - Console color not properly reset when interrupting build process</li>
<li><a class="externalLink" href="https://issues.apache.org/jira/browse/MNG-6255">MNG-6255</a> - Maven script cannot parse <tt>jvm.config</tt> with CRLF</li>
<li><a class="externalLink" href="https://issues.apache.org/jira/browse/MNG-6282">MNG-6282</a> - Console output has no colors in shell (both Git Bash and Cygwin) (regression in Jansi 1.16 / Maven 3.5.1)</li>
<li><a class="externalLink" href="https://issues.apache.org/jira/browse/MNG-6296">MNG-6296</a> - New option <tt>-Dstyle.color</tt> is not working</li>
<li><a class="externalLink" href="https://issues.apache.org/jira/browse/MNG-6298">MNG-6298</a> - 3.5.2: <tt>ClassNotFoundException: javax.annotation.security.RolesAllowed</tt></li>
<li><a class="externalLink" href="https://issues.apache.org/jira/browse/MNG-6300">MNG-6300</a> - Multi module release creates empty directories in war file instead of jars</li>
<li><a class="externalLink" href="https://issues.apache.org/jira/browse/MNG-6305">MNG-6305</a> - Validation of CI friendly version incorrect</li>
<li><a class="externalLink" href="https://issues.apache.org/jira/browse/MNG-6320">MNG-6320</a> - Apparently wrong encoding of non-ascii java class filename in error messages in the maven log</li>
<li><a class="externalLink" href="https://issues.apache.org/jira/browse/MNG-6323">MNG-6323</a> - Deadlock in multithreaded dependency resolution</li>
<li><a class="externalLink" href="https://issues.apache.org/jira/browse/MNG-6330">MNG-6330</a> - (regression) Parents relativePath not verified anymore</li>
</ul>
<div class="section">
<h3><a name="New_Feature"></a>New Feature</h3>
<ul>

<li><a class="externalLink" href="https://issues.apache.org/jira/browse/MNG-6302">MNG-6302</a> - Provide some &#x201c;progress&#x201d; hints</li>
</ul></div>
<div class="section">
<h3><a name="Improvements"></a>Improvements</h3>
<ul>

<li><a class="externalLink" href="https://issues.apache.org/jira/browse/MNG-5992">MNG-5992</a> - Git passwords are exposed as the Super POM still uses Maven Release Plugin 2.3.2</li>
<li><a class="externalLink" href="https://issues.apache.org/jira/browse/MNG-6306">MNG-6306</a> - Replace use of Guava in maven-resolver-provider with a lighter weight alternative</li>
<li><a class="externalLink" href="https://issues.apache.org/jira/browse/MNG-6308">MNG-6308</a> - display packaging &amp; groupId:artifactId when building a module</li>
<li><a class="externalLink" href="https://issues.apache.org/jira/browse/MNG-6332">MNG-6332</a> - Cleaned up <tt>mvn.cmd</tt> Script</li>
<li><a class="externalLink" href="https://issues.apache.org/jira/browse/MNG-6340">MNG-6340</a> - (Performance) To make <tt>System.gc()</tt> call configurable in target summary code</li>
<li><a class="externalLink" href="https://issues.apache.org/jira/browse/MNG-6342">MNG-6342</a> - Emit a WARNING about LATEST/RELEASE in parent</li>
<li><a class="externalLink" href="https://issues.apache.org/jira/browse/MNG-6352">MNG-6352</a> - Printout version information at the end of the build</li>
</ul></div>
<div class="section">
<h3><a name="Task"></a>Task</h3>
<ul>

<li><a class="externalLink" href="https://issues.apache.org/jira/browse/MNG-6331">MNG-6331</a> - Remove maven-bundle-pugin from build pluginManagement</li>
</ul></div>
<div class="section">
<h3><a name="Dependency_upgrade"></a>Dependency upgrade</h3>
<ul>

<li><a class="externalLink" href="https://issues.apache.org/jira/browse/MNG-6312">MNG-6312</a> - Update Maven Wagon dependency</li>
<li><a class="externalLink" href="https://issues.apache.org/jira/browse/MNG-6335">MNG-6335</a> - Update test framework Mockito from 1.10 to 2.12</li>
<li><a class="externalLink" href="https://issues.apache.org/jira/browse/MNG-6353">MNG-6353</a> - Upgrade maven-shared-utils to 3.2.1</li>
</ul>
<p>The full list of changes can be found in our <a class="externalLink" href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12316922&amp;version=12341428">issue management system</a>.</p></div></div>
<div class="section">
<h2><a name="Complete_Release_Notes"></a>Complete Release Notes</h2>
<p>See <a href="../../docs/history.html">complete release notes for all versions</a></p></div>
        </div>
      </div>
    </div>
    <hr/>
