---
layout: post
title: 'Apache Shared Component: Apache Maven Artifact Transfer Version 0.10.0 Released'
date: '2018-07-05T17:37:31+00:00'
permalink: apache-shared-component-apache-maven
---
<div class="entry-content"><p>The Apache Maven team is pleased to announce the release of the
<a href="http://maven.apache.org/shared/maven-artifact-transfer/">Apache Shared Component: Apache Maven Artifact Transfer Version 0.10.0</a></p>

<p>An API to install, deploy and resolving artifacts with Maven3</p>

<figure class='code'><figcaption><span></span></figcaption><div class="highlight"><table><tr><td class="gutter"><pre class="line-numbers"><span class='line-number'>1</span>
<span class='line-number'>2</span>
<span class='line-number'>3</span>
<span class='line-number'>4</span>
<span class='line-number'>5</span>
</pre></td><td class='code'><pre><code class='xml'><span class='line'><span class="nt">&lt;dependency&gt;</span>
</span><span class='line'>  <span class="nt">&lt;groupId&gt;</span>org.apache.maven.shared<span class="nt">&lt;/groupId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;artifactId&gt;</span>maven-artifact-transfer<span class="nt">&lt;/artifactId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;version&gt;</span>0.10.0<span class="nt">&lt;/version&gt;</span>
</span><span class='line'><span class="nt">&lt;/dependency&gt;</span>
</span></code></pre></td></tr></table></div></figure>




<!-- more -->


<p><a href="https://issues.apache.org/jira/projects/MSHARED/versions/12338168">Release Notes Apache Shared Componet Maven Artifact Transfer 0.10.0</a></p>

<p>Bugs:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-641">MSHARED-641</a> &ndash; NoSuchMethodException using DependencyResolver with Maven 3.0</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-724">MSHARED-724</a> &ndash; Upgrade mave-surefire/failsafe-plugin 2.21.0</li>
</ul>


<p>Improvements:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-655">MSHARED-655</a> &ndash; ArtifactInstaller check for integrity of parameters null, empty collection, being a directory</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-656">MSHARED-656</a> &ndash; Make integration testing for different Maven versions possible</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-658">MSHARED-658</a> &ndash; ArtifactDeployer check for integrity of parameters null, empty collection, being a directory</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-677">MSHARED-677</a> &ndash; Add null checks for ArtifactResolver interface.</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-678">MSHARED-678</a> &ndash; Add null check for ProjectInstaller Interface</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-679">MSHARED-679</a> &ndash; Make all classes package private in internal package</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-695">MSHARED-695</a> &ndash; Move checksum creation from install part to deploy part</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-696">MSHARED-696</a> &ndash; Add missing Maven Version 3.5.2 to ArtifactDeployerTest</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-697">MSHARED-697</a> &ndash; Add Maven Version 3.5.3 to all Integration tests after releasing Maven 3.5.3</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-701">MSHARED-701</a> &ndash; Remove installation of pom checksum &ndash; IT&rsquo;s do not fail</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-705">MSHARED-705</a> &ndash; Remove updateReleaseInfo from ProjectInstallerRequest</li>
</ul>


<p>Tasks:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-698">MSHARED-698</a> &ndash; Change the package to org.apache.maven.shared.transfer.*</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-703">MSHARED-703</a> &ndash; Try to identify why IT&rsquo;s not running with Maven 3.0.5</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-742">MSHARED-742</a> &ndash; Add null check for DependencyResolver Interface</li>
</ul>


<p>Dependency upgrades:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-651">MSHARED-651</a> &ndash; Upgrade plexus-utils to version 3.1.0</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-652">MSHARED-652</a> &ndash; Upgrade to maven-shade-plugin to version 3.0.0</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-682">MSHARED-682</a> &ndash; Upgrade maven-shared-components parent to version 31</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-693">MSHARED-693</a> &ndash; Upgrade JUnit from 4.11 to 4.12</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-699">MSHARED-699</a> &ndash; Upgrade parent to 31 in IT example project</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-737">MSHARED-737</a> &ndash; Upgrade mockito-core to 2.18.3 JDK 10 support</li>
<li><a href="https://issues.apache.org/jira/browse/MSHARED-741">MSHARED-741</a> &ndash; Upgrade commons-codec to 1.11</li>
</ul>


<p>Enjoy,</p>

<p>-The Maven team</p>
