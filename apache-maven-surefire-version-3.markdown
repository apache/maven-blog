---
layout: post
title: Apache Maven Surefire Version 3.0.0-M4
date: '2019-11-17T17:16:17+00:00'
permalink: apache-maven-surefire-version-3
---
<div class="entry-content"><p>The Apache Maven team is pleased to announce the release of the
  <a href="https://maven.apache.org/plugins/maven-surefire-plugin/">Apache Maven Surefire Plugin, version 3.0.0-M4</a>.</p>

  <p>The release contains 43 bug fixes.
    Again we received contributions from the community in form of bug reports
    and bug fixes. Thank you and keep them coming!</p>

  <p>You should specify the version in your project&rsquo;s plugin configuration:</p>

  <figure class='code'><figcaption><span></span></figcaption><div class="highlight"><table><tr><td class="gutter"><pre class="line-numbers"><span class='line-number'>1</span>
<span class='line-number'>2</span>
<span class='line-number'>3</span>
<span class='line-number'>4</span>
<span class='line-number'>5</span>
</pre></td><td class='code'><pre><code class='xml'><span class='line'><span class="nt">&lt;plugin&gt;</span>
</span><span class='line'>  <span class="nt">&lt;groupId&gt;</span>org.apache.maven.plugins<span class="nt">&lt;/groupId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;artifactId&gt;</span>maven-surefire-plugin<span class="nt">&lt;/artifactId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;version&gt;</span>3.0.0-M4<span class="nt">&lt;/version&gt;</span>
</span><span class='line'><span class="nt">&lt;/plugin&gt;</span>
</span></code></pre></td></tr></table></div></figure>


  <p>or for failsafe:</p>

  <figure class='code'><figcaption><span></span></figcaption><div class="highlight"><table><tr><td class="gutter"><pre class="line-numbers"><span class='line-number'>1</span>
<span class='line-number'>2</span>
<span class='line-number'>3</span>
<span class='line-number'>4</span>
<span class='line-number'>5</span>
</pre></td><td class='code'><pre><code class='xml'><span class='line'><span class="nt">&lt;plugin&gt;</span>
</span><span class='line'>  <span class="nt">&lt;groupId&gt;</span>org.apache.maven.plugins<span class="nt">&lt;/groupId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;artifactId&gt;</span>maven-failsafe-plugin<span class="nt">&lt;/artifactId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;version&gt;</span>3.0.0-M4<span class="nt">&lt;/version&gt;</span>
</span><span class='line'><span class="nt">&lt;/plugin&gt;</span>
</span></code></pre></td></tr></table></div></figure>


  <p>or for surefire-report:</p>

  <figure class='code'><figcaption><span></span></figcaption><div class="highlight"><table><tr><td class="gutter"><pre class="line-numbers"><span class='line-number'>1</span>
<span class='line-number'>2</span>
<span class='line-number'>3</span>
<span class='line-number'>4</span>
<span class='line-number'>5</span>
</pre></td><td class='code'><pre><code class='xml'><span class='line'><span class="nt">&lt;plugin&gt;</span>
</span><span class='line'>  <span class="nt">&lt;groupId&gt;</span>org.apache.maven.plugins<span class="nt">&lt;/groupId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;artifactId&gt;</span>maven-surefire-report-plugin<span class="nt">&lt;/artifactId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;version&gt;</span>3.0.0-M4<span class="nt">&lt;/version&gt;</span>
</span><span class='line'><span class="nt">&lt;/plugin&gt;</span>
</span></code></pre></td></tr></table></div></figure>


  <p>You can download the appropriate <a href="https://maven.apache.org/surefire/download.cgi">sources etc. from the download page</a>.</p>

  <!-- more -->


  <p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317927&amp;version=12344668">Release Notes &ndash; Maven Surefire &ndash; Version 3.0.0-M4</a></p>

  <p>Bugs:</p>

  <ul>
    <li><a href="https://issues.apache.org/jira/browse/SUREFIRE-1222">SUREFIRE-1222</a> &ndash; ForkClient attempts to consume unrelated lines</li>
    <li><a href="https://issues.apache.org/jira/browse/SUREFIRE-1464">SUREFIRE-1464</a> &ndash; Failsafe plugin exposes slf4j-jdk14 dependency</li>
    <li><a href="https://issues.apache.org/jira/browse/SUREFIRE-1534">SUREFIRE-1534</a> &ndash; Surefire 2.21.0 ClassNotFoundException: org.apache.maven.plugin.surefire.StartupReportConfiguration using reuseForks set to false</li>
    <li><a href="https://issues.apache.org/jira/browse/SUREFIRE-1546">SUREFIRE-1546</a> &ndash; JUnit 5 runner does not honor JUnit 5 display names</li>
    <li><a href="https://issues.apache.org/jira/browse/SUREFIRE-1664">SUREFIRE-1664</a> &ndash; &ldquo;plugin&rsquo;s wiki page&rdquo; points to non-existing web page</li>
    <li><a href="https://issues.apache.org/jira/browse/SUREFIRE-1669">SUREFIRE-1669</a> &ndash; POJO tests do not call fixture methods setUp and tearDown and test instances are not new between tests</li>
    <li><a href="https://issues.apache.org/jira/browse/SUREFIRE-1670">SUREFIRE-1670</a> &ndash; wrong &ldquo;Filtering by Test Class Names&rdquo; in failsafe &ldquo;Using JUnit 5 Platform&rdquo; page</li>
    <li><a href="https://issues.apache.org/jira/browse/SUREFIRE-1675">SUREFIRE-1675</a> &ndash; Forked JVM terminates with &lsquo;halt&rsquo; when another module&rsquo;s tests fail</li>
    <li><a href="https://issues.apache.org/jira/browse/SUREFIRE-1679">SUREFIRE-1679</a> &ndash; Caching of provider classpath with module-specific changes may break test bootstrapping in subsequent modules</li>
    <li><a href="https://issues.apache.org/jira/browse/SUREFIRE-1684">SUREFIRE-1684</a> &ndash; The documentation of Maven Surefire Report Plugin contains wrong number of plugin goals</li>
    <li><a href="https://issues.apache.org/jira/browse/SUREFIRE-1689">SUREFIRE-1689</a> &ndash; The fast PpidChecker is switched to the slow 30 seconds PING after the subprocess (/bin/ps -o etime= -p &hellip;) failed with exit 1</li>
    <li><a href="https://issues.apache.org/jira/browse/SUREFIRE-1690">SUREFIRE-1690</a> &ndash; Typo fixed: classpathDependencyExclude</li>
    <li><a href="https://issues.apache.org/jira/browse/SUREFIRE-1701">SUREFIRE-1701</a> &ndash; Surefire / Failsafe rerun failed tests functionality fails with JUnit 5 if using @DisplayName</li>
    <li><a href="https://issues.apache.org/jira/browse/SUREFIRE-1707">SUREFIRE-1707</a> &ndash; Forked JVM is killed when GC paused the tests for over 30 seconds</li>
    <li><a href="https://issues.apache.org/jira/browse/SUREFIRE-1712">SUREFIRE-1712</a> &ndash; Running tests with JDK13 fails with Unsupported class file major version 57</li>
    <li><a href="https://issues.apache.org/jira/browse/SUREFIRE-1716">SUREFIRE-1716</a> &ndash; JUnit5 Parameterized tests and re-run should see unique test runs with different parameters</li>
  </ul>


  <p>New Features:</p>

  <ul>
    <li><a href="https://issues.apache.org/jira/browse/SUREFIRE-1584">SUREFIRE-1584</a> &ndash; Rerun Failing Tests with JUnit 5</li>
    <li><a href="https://issues.apache.org/jira/browse/SUREFIRE-1705">SUREFIRE-1705</a> &ndash; new config parameter Exclude Environment Variables</li>
    <li><a href="https://issues.apache.org/jira/browse/SUREFIRE-1711">SUREFIRE-1711</a> &ndash; Support @ParameterizedTest for JUnit 5 test reruns</li>
    <li><a href="https://issues.apache.org/jira/browse/SUREFIRE-1717">SUREFIRE-1717</a> &ndash; Enable Process Checkers</li>
  </ul>


  <p>Improvements:</p>

  <ul>
    <li><a href="https://issues.apache.org/jira/browse/SUREFIRE-1004">SUREFIRE-1004</a> &ndash; Enhance pattern/wildcard capabilities for dependenciesToScan to GAVT</li>
    <li><a href="https://issues.apache.org/jira/browse/SUREFIRE-1585">SUREFIRE-1585</a> &ndash; Align JUnit Platform version at runtime</li>
    <li><a href="https://issues.apache.org/jira/browse/SUREFIRE-1617">SUREFIRE-1617</a> &ndash; Surefire fails with bad message when path contains colon</li>
    <li><a href="https://issues.apache.org/jira/browse/SUREFIRE-1619">SUREFIRE-1619</a> &ndash; FileReporter should not use PintWriter because i/o errors are not thrown</li>
    <li><a href="https://issues.apache.org/jira/browse/SUREFIRE-1620">SUREFIRE-1620</a> &ndash; Replaced deprecated component ArtifactFactory with RepositorySystem</li>
    <li><a href="https://issues.apache.org/jira/browse/SUREFIRE-1634">SUREFIRE-1634</a> &ndash; Add missing since tags to excludesFile and includesFile</li>
    <li><a href="https://issues.apache.org/jira/browse/SUREFIRE-1635">SUREFIRE-1635</a> &ndash; Set properties readonly where it doesn&rsquo;t make sense to change values</li>
    <li><a href="https://issues.apache.org/jira/browse/SUREFIRE-1647">SUREFIRE-1647</a> &ndash; When using junit5, delay loading testClass and use myown classLoader</li>
    <li><a href="https://issues.apache.org/jira/browse/SUREFIRE-1666">SUREFIRE-1666</a> &ndash; printSummary=false does not completely suppress the summary on the console</li>
    <li><a href="https://issues.apache.org/jira/browse/SUREFIRE-1668">SUREFIRE-1668</a> &ndash; The stackTrace should use CDATA in XML report.</li>
    <li><a href="https://issues.apache.org/jira/browse/SUREFIRE-1682">SUREFIRE-1682</a> &ndash; Default value for config parameter &lsquo;shutdown&rsquo; should change from &lsquo;testset&rsquo; to &lsquo;exit&rsquo;</li>
    <li><a href="https://issues.apache.org/jira/browse/SUREFIRE-1702">SUREFIRE-1702</a> &ndash; [JDK 11 Alpine Linux] JAR content is not flushed completely down to drive &ldquo;Error: Invalid or corrupt jarfile target/surefire/surefirebooter13749914711390838584.jar&rdquo;</li>
    <li><a href="https://issues.apache.org/jira/browse/SUREFIRE-1703">SUREFIRE-1703</a> &ndash; [JDK 11 Alpine Linux] Surefire handled random order of pid and /procps does not filter pid on busybox distributions</li>
    <li><a href="https://issues.apache.org/jira/browse/SUREFIRE-1704">SUREFIRE-1704</a> &ndash; [JDK 11 Alpine Linux] long etime within hours has format 2h01 on busybox</li>
  </ul>


  <p>Tasks:</p>

  <ul>
    <li><a href="https://issues.apache.org/jira/browse/SUREFIRE-1678">SUREFIRE-1678</a> &ndash; JUnit5 Integration Tests should test wide spectrum of versions</li>
    <li><a href="https://issues.apache.org/jira/browse/SUREFIRE-1683">SUREFIRE-1683</a> &ndash; Buildfix: TLS 1.2 passed to maven-invoker-plugin via system property</li>
    <li><a href="https://issues.apache.org/jira/browse/SUREFIRE-1706">SUREFIRE-1706</a> &ndash; Use the checkstyle in tests and set includeTestSourceDirectory=true</li>
    <li><a href="https://issues.apache.org/jira/browse/SUREFIRE-1714">SUREFIRE-1714</a> &ndash; Created module &ldquo;surefire-shared-utils&rdquo; as a required dependency in &ldquo;surefire-extensions-api&rdquo; and &ldquo;maven-surefire-common&rdquo;</li>
  </ul>


  <p>Dependency upgrades:</p>

  <ul>
    <li><a href="https://issues.apache.org/jira/browse/SUREFIRE-1642">SUREFIRE-1642</a> &ndash; Upgrade plexus-java to Version 1.0.3</li>
    <li><a href="https://issues.apache.org/jira/browse/SUREFIRE-1646">SUREFIRE-1646</a> &ndash; Upgrade maven-artifact-transfer Version 0.11.0</li>
    <li><a href="https://issues.apache.org/jira/browse/SUREFIRE-1672">SUREFIRE-1672</a> &ndash; DOXIA updated to version 1.9</li>
    <li><a href="https://issues.apache.org/jira/browse/SUREFIRE-1674">SUREFIRE-1674</a> &ndash; DOXIA TOOLS updated to version 1.9.1</li>
    <li><a href="https://issues.apache.org/jira/browse/SUREFIRE-1685">SUREFIRE-1685</a> &ndash; Upgrade maven-fluido-skin to 1.8 and maven-site-plugin to 3.8.2</li>
  </ul>


  <p>Enjoy,</p>

  <p>-The Apache Maven team</p>
</div>

