---
layout: post
title: Apache Maven Release 3.6.1
date: '2019-04-13T11:08:32+00:00'
permalink: apache-maven-core-3-6
---
<div class="entry-content"><p>The Apache Maven team is pleased to announce the release of the Apache
Maven 3.6.1.</p>

<p>Apache Maven is a software project management and comprehension tool. Based
on the concept of a project object model (POM), Maven can manage a
project&rsquo;s build, reporting and documentation from a central piece of
information.</p>

<p>You can find out more about Apache Maven at <a href="https://maven.apache.org">https://maven.apache.org</a></p>

<p>You can download the appropriate sources etc. from
the <a href="https://maven.apache.org/download.cgi">download page</a></p>

<!-- more -->


<p>We really value the contributions of these non committers, so this section is
focused on those individuals. Descriptions of the issues fixed can be found at
the <a href="#Details">end of these release notes</a>.</p>

<p>Issue Reporters of this release:</p>

<ul>
<li><a href="http://issues.apache.org/jira/browse/MNG-5705">MNG-5705</a> Ondra Žižka</li>
<li><a href="http://issues.apache.org/jira/browse/MNG-5965">MNG-5965</a> Matthias Schmalz</li>
<li><a href="http://issues.apache.org/jira/browse/MNG-6059">MNG-6059</a> Andreas Sewe</li>
<li><a href="http://issues.apache.org/jira/browse/MNG-6159">MNG-6159</a> Christian Aistleitner</li>
<li><a href="http://issues.apache.org/jira/browse/MNG-6213">MNG-6213</a> Jin Kwon</li>
<li><a href="http://issues.apache.org/jira/browse/MNG-6256">MNG-6256</a> Christoph Etzel</li>
<li><a href="http://issues.apache.org/jira/browse/MNG-6261">MNG-6261</a> Dawid Weiss</li>
<li><a href="http://issues.apache.org/jira/browse/MNG-6262">MNG-6262</a> Gene Smith</li>
<li><a href="http://issues.apache.org/jira/browse/MNG-6346">MNG-6346</a> Patrik Jetzer</li>
<li><a href="http://issues.apache.org/jira/browse/MNG-6374">MNG-6374</a> Rohan Padhye</li>
<li><a href="http://issues.apache.org/jira/browse/MNG-6495">MNG-6495</a> Elliotte Rusty Harold</li>
<li><a href="http://issues.apache.org/jira/browse/MNG-6506">MNG-6506</a> Andreas Veithen</li>
<li><a href="http://issues.apache.org/jira/browse/MNG-6526">MNG-6526</a> Olaf Otto</li>
<li><a href="http://issues.apache.org/jira/browse/MNG-6529">MNG-6529</a> Michael Istria</li>
<li><a href="http://issues.apache.org/jira/browse/MNG-6530">MNG-6530</a> Michael Istria</li>
<li><a href="http://issues.apache.org/jira/browse/MNG-6533">MNG-6533</a> Michael Istria</li>
<li><a href="http://issues.apache.org/jira/browse/MNG-6543">MNG-6543</a> Romain Manni-Bucau</li>
<li><a href="http://issues.apache.org/jira/browse/MNG-6558">MNG-6558</a> Guy Brand</li>
<li><a href="http://issues.apache.org/jira/browse/MNG-6577">MNG-6577</a> Rohan Padhye</li>
<li><a href="http://issues.apache.org/jira/browse/MNG-6591">MNG-6591</a> Olaf Otto</li>
<li><a href="http://issues.apache.org/jira/browse/MNG-6605">MNG-6605</a> Gunnar Wagenknecht</li>
<li><a href="http://issues.apache.org/jira/browse/MNG-6618">MNG-6618</a> Viacheslav Yakunin</li>
</ul>


<p>Code Contributors of this release:</p>

<ul>
<li><a href="http://issues.apache.org/jira/browse/MNG-6374">MNG-6374</a> Gabriel Belingueres (indirectly via plexus-utils PR)</li>
<li><a href="http://issues.apache.org/jira/browse/MNG-6529">MNG-6529</a> Michael Istria</li>
<li><a href="http://issues.apache.org/jira/browse/MNG-6530">MNG-6530</a> Michael Istria</li>
<li><a href="http://issues.apache.org/jira/browse/MNG-6558">MNG-6558</a> Guy Brand</li>
<li><a href="http://issues.apache.org/jira/browse/MNG-6261">MNG-6261</a> Fabiano C. de Oliveira</li>
<li><a href="http://issues.apache.org/jira/browse/MNG-6533">MNG-6533</a> Michael Istria</li>
</ul>


<p>Many thanks to all reporters and contributors for their time and support.</p>

<p>(Please send an email to the dev list if we missed one to mention).</p>

<h2>Preliminary Testers</h2>

<p>Thanks to the following preliminary testers:</p>

<ul>
<li>Gabriel Belingueres</li>
<li>Francois Papon</li>
<li>Eric Lilja</li>
</ul>


<h2>Known Issues</h2>

<p>If you are using Maven reporting, it might happen that you will get an exception which looks like this:</p>

<figure class='code'><div class="highlight"><table><tr><td class="gutter"><pre class="line-numbers"><span class='line-number'>1</span>
<span class='line-number'>2</span>
<span class='line-number'>3</span>
<span class='line-number'>4</span>
<span class='line-number'>5</span>
<span class='line-number'>6</span>
<span class='line-number'>7</span>
<span class='line-number'>8</span>
</pre></td><td class='code'><pre><code class=''><span class='line'>[INFO] Scanning for projects...
</span><span class='line'>[ERROR] Internal error: java.lang.NullPointerException -&gt; [Help 1]
</span><span class='line'>org.apache.maven.InternalErrorException: Internal error: java.lang.NullPointerException
</span><span class='line'>    at org.apache.maven.DefaultMaven.execute (DefaultMaven.java:120)
</span><span class='line'>...
</span><span class='line'>Caused by: java.lang.NullPointerException
</span><span class='line'>    at org.apache.maven.model.plugin.DefaultReportingConverter.convert (DefaultReportingConverter.java:243)
</span><span class='line'>...</span></code></pre></td></tr></table></div></figure>


<p>This is caused by using a <code>&lt;reportSet&gt;..&lt;/reportSet&gt;</code> which does not contain
a <code>&lt;report&gt;&lt;/report&gt;</code> element.</p>

<p>Temporarily this issue can circumvented by adding an empty <code>&lt;report&gt;&lt;/report&gt;</code> element
inside the <code>&lt;reportSet&gt;&lt;/reportSet&gt;</code>.</p>

<p>An <a href="https://issues.apache.org/jira/browse/MNG-6636">issue has been created</a> to track the fix.</p>

<h2>Overview about the changes</h2>

<ul>
<li><p>An issue has been fixed causing multiple executions of plugin goals, related to
using parallel build options like <code>mvn plugin:goal -T 4</code>. This resulted in duplicated
executions of phases. This has been fixed with <a href="http://issues.apache.org/jira/browse/MNG-5965">MNG-5965</a>.</p></li>
<li><p>NullPointerException related to call in parallel build like <code>mvn -T 1C clean javadoc:aggregate</code>
<a href="http://issues.apache.org/jira/browse/MNG-5705">MNG-5705</a></p></li>
<li><p>A performance issue related to artifact transfer has been found related to <a href="http://issues.apache.org/jira/browse/WAGON-537">WAGON-537</a>. It
has been solved via the update to <a href="http://issues.apache.org/jira/browse/MNG-6526">Maven Wagon 3.3.1</a>.</p></li>
<li><p>There had been issues related calling Maven script like this: <code>mvn -f ..</code></p>

<ul>
<li>Having parentheses within the path, which has been fixed with <a href="http://issues.apache.org/jira/browse/MNG-6346">MNG-6346</a>.</li>
<li>Script can break having special characters as part of the path, which has
been solved with <a href="http://issues.apache.org/jira/browse/MNG-6256">MNG-6256</a>.</li>
</ul>
</li>
<li><p>Issue related to the Maven Resolver API which broke some IDEs (for example <a href="https://youtrack.jetbrains.com/issue/IDEA-201282">https://youtrack.jetbrains.com/issue/IDEA-201282</a>);
this has been fixed by <a href="http://issues.apache.org/jira/browse/MNG-6538">MNG-6538</a>.</p></li>
<li><p>Issue related to missing event for ToolchainsBuildingResult on EventSpy <a href="http://issues.apache.org/jira/browse/MNG-6558">MNG-6558</a>.</p></li>
<li><p>Issue related to support Java 9+ <code>ClassLoader.findClass(String moduleName, String name)</code> in Mojos.
This has been fixed with <a href="http://issues.apache.org/jira/browse/MNG-6543">MNG-6543</a>.</p></li>
<li><p>Improvement about the memory consumption has been done with <a href="http://issues.apache.org/jira/browse/MNG-6571">MNG-6571</a>.</p></li>
<li><p>Issue related to relative parent POM resolution failing in 3.5.0 with complex multimodule builds
has been fixed with <a href="http://issues.apache.org/jira/browse/MNG-6261">MNG-6261</a>.</p></li>
<li><p>Missing export for org.slf4j.event.Level has been done with <a href="http://issues.apache.org/jira/browse/MNG-6618">MNG-6618</a></p></li>
</ul>


<h2>User visible Changes</h2>

<p>Maven has now a an option to suppress the transfer progress when downloading/uploading
in interactive mode.</p>

<figure class='code'><div class="highlight"><table><tr><td class="gutter"><pre class="line-numbers"><span class='line-number'>1</span>
</pre></td><td class='code'><pre><code class=''><span class='line'>mvn --no-transfer-progress ....</span></code></pre></td></tr></table></div></figure>


<p>or in short:</p>

<figure class='code'><div class="highlight"><table><tr><td class="gutter"><pre class="line-numbers"><span class='line-number'>1</span>
</pre></td><td class='code'><pre><code class=''><span class='line'>mvn -ntp ... ....</span></code></pre></td></tr></table></div></figure>


<p>There had been an issues like <a href="http://issues.apache.org/jira/browse/MNG-6505">MNG-6505</a> and <a href="http://issues.apache.org/jira/browse/MNG-6059">MNG-6059</a> related to the construction of
URL&rsquo;s etc. within <code>distributionManagement</code> and <code>scm</code> part in the pom for multi module
builds like this:</p>

<figure class='code'><div class="highlight"><table><tr><td class="gutter"><pre class="line-numbers"><span class='line-number'>1</span>
<span class='line-number'>2</span>
<span class='line-number'>3</span>
<span class='line-number'>4</span>
<span class='line-number'>5</span>
<span class='line-number'>6</span>
</pre></td><td class='code'><pre><code class=''><span class='line'>&lt;scm child.scm.connection.inherit.append.path="true"
</span><span class='line'>     child.scm.developerConnection.inherit.append.path="true"
</span><span class='line'>     child.scm.url.inherit.append.path="true" /&gt;
</span><span class='line'>&lt;distributionManagement&gt;
</span><span class='line'>   &lt;site child.site.url.inherit.append.path="true" /&gt;
</span><span class='line'> &lt;/distributionManagement&gt;</span></code></pre></td></tr></table></div></figure>


<p>Detailed explanations can be found in <a href="https://maven.apache.org/ref/3.6.1/maven-model-builder/index.html#Inheritance_Assembly">Inheritance Assembly</a> and in <a href="http://issues.apache.org/jira/browse/MNG-6059">MNG-6059</a></p>

<h2>The detailed issue list<a href="#Details"></a></h2>

<h3>Bugs:</h3>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MNG-5705">MNG-5705</a> &ndash; NPE on parallel build in BuilderCommon.handleBuildError(BuilderCommon.java:147)</li>
<li><a href="https://issues.apache.org/jira/browse/MNG-5965">MNG-5965</a> &ndash; Parallel build multiplies work if multiple goals are given</li>
<li><a href="https://issues.apache.org/jira/browse/MNG-5995">MNG-5995</a> &ndash; Maven itself cannot run without maven-compat</li>
<li><a href="https://issues.apache.org/jira/browse/MNG-6256">MNG-6256</a> &ndash; Maven script can break if &ldquo;-f&rdquo; path contains special characters</li>
<li><a href="https://issues.apache.org/jira/browse/MNG-6261">MNG-6261</a> &ndash; Relative parent POM resolution failing in 3.5.0 with complex multimodule builds</li>
<li><a href="https://issues.apache.org/jira/browse/MNG-6262">MNG-6262</a> &ndash; getCanonicalFile() is not used consistently during project resolution</li>
<li><a href="https://issues.apache.org/jira/browse/MNG-6346">MNG-6346</a> &ndash; &hellip; was unexpected at this time when using -f option and path contains brackets</li>
<li><a href="https://issues.apache.org/jira/browse/MNG-6374">MNG-6374</a> &ndash; ModelBuilder hangs with malformed pom.xml</li>
<li><a href="https://issues.apache.org/jira/browse/MNG-6429">MNG-6429</a> &ndash; Integration Test site publishing requires Java 7 (or javadoc errors ignored)</li>
<li><a href="https://issues.apache.org/jira/browse/MNG-6495">MNG-6495</a> &ndash; ModelResolver cannot be null</li>
<li><a href="https://issues.apache.org/jira/browse/MNG-6505">MNG-6505</a> &ndash; child.(x.y).inherit.append.path value should be inherited</li>
<li><a href="https://issues.apache.org/jira/browse/MNG-6506">MNG-6506</a> &ndash; Mojos are unable to load package annotations on Java >= 9</li>
<li><a href="https://issues.apache.org/jira/browse/MNG-6529">MNG-6529</a> &ndash; <code>ProjectBuilder.build(List&lt;File&gt; projects, boolean, ProjectBuildingRequest)</code> doesn&rsquo;t honor <code>ProjectBuildingRequest.isResolveDependencies()</code></li>
<li><a href="https://issues.apache.org/jira/browse/MNG-6530">MNG-6530</a> &ndash; Regression in ProjectBuilder when file change between invocations (introduced by MNG-6311)</li>
<li><a href="https://issues.apache.org/jira/browse/MNG-6533">MNG-6533</a> &ndash; <code>ProjectBuilder.build(list_of_projects,...)</code> does not contain MavenProject in exception report</li>
<li><a href="https://issues.apache.org/jira/browse/MNG-6543">MNG-6543</a> &ndash; Upgrade plexus classworld to support java 9+ <code>ClassLoader.findClass(String moduleName, String name)</code> in Mojos</li>
<li><a href="https://issues.apache.org/jira/browse/MNG-6558">MNG-6558</a> &ndash; ToolchainsBuildingResult event is not sent on EventSpy</li>
<li><a href="https://issues.apache.org/jira/browse/MNG-6577">MNG-6577</a> &ndash; pom.xml: Uncaught IllegalArgumentException when parsing unicode entity ref</li>
<li><a href="https://issues.apache.org/jira/browse/MNG-6590">MNG-6590</a> &ndash; DefaultProjectArtifactsCache java.lang.IllegalStateException: Duplicate artifact resolution result</li>
<li><a href="https://issues.apache.org/jira/browse/MNG-6599">MNG-6599</a> &ndash; unknown version in model id when version is defined from parent</li>
</ul>


<h3>Improvements</h3>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MNG-6059">MNG-6059</a> &ndash; Important use cases not covered, as child.inherit.append.path affects all children</li>
<li><a href="https://issues.apache.org/jira/browse/MNG-6159">MNG-6159</a> &ndash; Child path adjustments break git scm urls</li>
<li><a href="https://issues.apache.org/jira/browse/MNG-6213">MNG-6213</a> &ndash; Maven doesn&rsquo;t check the validity of scope value</li>
<li><a href="https://issues.apache.org/jira/browse/MNG-6481">MNG-6481</a> &ndash; Allow to compile and test Maven with Java 11</li>
<li><a href="https://issues.apache.org/jira/browse/MNG-6513">MNG-6513</a> &ndash; Replace depreated Plexus javadoc tags with annotations in ITs</li>
<li><a href="https://issues.apache.org/jira/browse/MNG-6515">MNG-6515</a> &ndash; Fix javadoc build errors under Java 8 and 11</li>
<li><a href="https://issues.apache.org/jira/browse/MNG-6520">MNG-6520</a> &ndash; Update assembly descriptors to 2.0.0</li>
<li><a href="https://issues.apache.org/jira/browse/MNG-6522">MNG-6522</a> &ndash; Prepare Maven&rsquo;s Core Integration Test Suite to test with Java 12 and 13-ea</li>
<li><a href="https://issues.apache.org/jira/browse/MNG-6572">MNG-6572</a> &ndash; use int or long instead of BigIntegers for little numbers in ComparableVersion</li>
<li><a href="https://issues.apache.org/jira/browse/MNG-6593">MNG-6593</a> &ndash; track input location for super-pom</li>
<li><a href="https://issues.apache.org/jira/browse/MNG-6597">MNG-6597</a> &ndash; add input location tracking for plugins configuration</li>
<li><a href="https://issues.apache.org/jira/browse/MNG-6600">MNG-6600</a> &ndash; add input location tracking for default lifecycle bindings executions</li>
<li><a href="https://issues.apache.org/jira/browse/MNG-6601">MNG-6601</a> &ndash; add input location tracking for site&rsquo;s reportPlugins injected by reports conversion</li>
<li><a href="https://issues.apache.org/jira/browse/MNG-6605">MNG-6605</a> &ndash; Allow to suppress download messages in interactive mode</li>
<li><a href="https://issues.apache.org/jira/browse/MNG-6611">MNG-6611</a> &ndash; Update animal-sniffer-maven-plugin to 1.17</li>
</ul>


<h3>Wish</h3>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MNG-6571">MNG-6571</a> &ndash; Maven memory consumption issue</li>
</ul>


<h3>Task</h3>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MNG-6538">MNG-6538</a> &ndash; Upgrade Maven Artifact Resolver to 1.3.3 to restore API</li>
<li><a href="https://issues.apache.org/jira/browse/MNG-6544">MNG-6544</a> &ndash; Replace CacheUtils#{eq,hash} with Objects</li>
<li><a href="https://issues.apache.org/jira/browse/MNG-6573">MNG-6573</a> &ndash; Use latest Maven 3.6.0 to build Maven Core and plugins with ASF CI</li>
<li><a href="https://issues.apache.org/jira/browse/MNG-6618">MNG-6618</a> &ndash; Maven doesn&rsquo;t export org.slf4j.event.Level</li>
</ul>


<h3>Dependency upgrade</h3>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MNG-6526">MNG-6526</a> &ndash; Upgrade to Wagon 3.3.1 (from 3.2.0)</li>
<li><a href="https://issues.apache.org/jira/browse/MNG-6591">MNG-6591</a> &ndash; Upgrade to Wagon 3.3.2</li>
</ul>


<p>The full list of changes can be found in our <a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?version=12344378&amp;projectId=12316922">issue management system</a>.</p>

<h2>Complete Release Notes</h2>

<p>See <a href="../../docs/history.html">complete release notes for all versions</a></p>

<ul>
<li>The Apache Maven Team.</li>
</ul>

</div>
