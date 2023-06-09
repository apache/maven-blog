---
layout: post
title: Apache Maven EAR Plugin 3.0.0 Released
date: '2018-03-12T21:14:03+00:00'
permalink: apache-maven-ear-plugin-3
---
<div class="entry-content"><p>The Apache Maven team is pleased to announce the release of the
<a href="http://maven.apache.org/plugins/maven-ear-plugin/">Apache Maven EAR Plugin, version 3.0.0</a></p>

<p>This plugin generates Java EE Enterprise Archive (EAR) file. It can also
generate the deployment descriptor file (e.g. application.xml).</p>

<p>You should specify the version in your project&rsquo;s plugin configuration:</p>

<figure class='code'><figcaption><span></span></figcaption><div class="highlight"><table><tr><td class="gutter"><pre class="line-numbers"><span class='line-number'>1</span>
<span class='line-number'>2</span>
<span class='line-number'>3</span>
<span class='line-number'>4</span>
<span class='line-number'>5</span>
</pre></td><td class='code'><pre><code class='xml'><span class='line'><span class="nt">&lt;plugin&gt;</span>
</span><span class='line'>  <span class="nt">&lt;groupId&gt;</span>org.apache.maven.plugins<span class="nt">&lt;/groupId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;artifactId&gt;</span>maven-ear-plugin<span class="nt">&lt;/artifactId&gt;</span>
</span><span class='line'>  <span class="nt">&lt;version&gt;</span>3.0.0<span class="nt">&lt;/version&gt;</span>
</span><span class='line'><span class="nt">&lt;/plugin&gt;</span>
</span></code></pre></td></tr></table></div></figure>


<p>You can download the appropriate <a href="https://maven.apache.org/plugins/maven-ear-plugin/download.cgi">sources etc. from the download page</a>.</p>

<!-- more -->


<p><a href="https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317422&amp;amp;version=12330696">Release Notes &ndash; Maven EAR Plugin &ndash; Version 3.0.0</a></p>

<p>Bugs:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MEAR-171">MEAR-171</a> &ndash; Full customization of FileNameMapping is needed</li>
<li><a href="https://issues.apache.org/jira/browse/MEAR-217">MEAR-217</a> &ndash; Snapshot dependencies are not deleted from skinny WARs</li>
<li><a href="https://issues.apache.org/jira/browse/MEAR-243">MEAR-243</a> &ndash; Skinny WARs &ndash; JAR not removed from WAR if scope in EAR is set to provided</li>
<li><a href="https://issues.apache.org/jira/browse/MEAR-244">MEAR-244</a> &ndash; Remove link to non-existing Codehaus wiki</li>
<li><a href="https://issues.apache.org/jira/browse/MEAR-246">MEAR-246</a> &ndash; Upgrade the EAR lifecycle to use the maven-resources-plugin 3.0.2.</li>
<li><a href="https://issues.apache.org/jira/browse/MEAR-250">MEAR-250</a> &ndash; IT skinny-wars-javaee5 fails while running with JDK 9</li>
</ul>


<p>New Features:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MEAR-247">MEAR-247</a> &ndash; resource-ref in generated application.xml</li>
<li><a href="https://issues.apache.org/jira/browse/MEAR-248">MEAR-248</a> &ndash; Support lookup-name in env-entry section</li>
</ul>


<p>Improvements:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MEAR-198">MEAR-198</a> &ndash; Add LifecycleMapping and ArtifactHandler from maven-core to target packaging plugin</li>
<li><a href="https://issues.apache.org/jira/browse/MEAR-223">MEAR-223</a> &ndash; Link to wiki on documentation page is pointing to shutdown codehaus</li>
<li><a href="https://issues.apache.org/jira/browse/MEAR-226">MEAR-226</a> &ndash; bundleFileName functionality for the acr plugin</li>
<li><a href="https://issues.apache.org/jira/browse/MEAR-228">MEAR-228</a> &ndash; Remove manifestFile parameter</li>
<li><a href="https://issues.apache.org/jira/browse/MEAR-229">MEAR-229</a> &ndash; Change default value for version parameter</li>
<li><a href="https://issues.apache.org/jira/browse/MEAR-232">MEAR-232</a> &ndash; Remove param properties that doesn&rsquo;t make sense for CLI usage</li>
<li><a href="https://issues.apache.org/jira/browse/MEAR-234">MEAR-234</a> &ndash; Upgrade maven-shared-components parent to version 30</li>
<li><a href="https://issues.apache.org/jira/browse/MEAR-241">MEAR-241</a> &ndash; Change package to o.a.m.plugins</li>
<li><a href="https://issues.apache.org/jira/browse/MEAR-242">MEAR-242</a> &ndash; Update lifecycle mapping plugin version</li>
<li><a href="https://issues.apache.org/jira/browse/MEAR-254">MEAR-254</a> &ndash; Support JavaEE version 8</li>
<li><a href="https://issues.apache.org/jira/browse/MEAR-258">MEAR-258</a> &ndash; Upgrade site skin to 1.7</li>
<li><a href="https://issues.apache.org/jira/browse/MEAR-260">MEAR-260</a> &ndash; Remove finalName as a parameter</li>
<li><a href="https://issues.apache.org/jira/browse/MEAR-261">MEAR-261</a> &ndash; In cases where fileNameMapping is used fail the build</li>
<li><a href="https://issues.apache.org/jira/browse/MEAR-262">MEAR-262</a> &ndash; Missing since for outputFileNameMapping parameter</li>
<li><a href="https://issues.apache.org/jira/browse/MEAR-263">MEAR-263</a> &ndash; Wrong docs in examples/customize-file-name-mapping.html</li>
</ul>


<p>Tasks:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MEAR-207">MEAR-207</a> &ndash; Remove the JavaModule/Ejb3Module which are marked deprecated</li>
<li><a href="https://issues.apache.org/jira/browse/MEAR-208">MEAR-208</a> &ndash; Upgrade to Maven 3.0 compatiblity + JDK 6</li>
<li><a href="https://issues.apache.org/jira/browse/MEAR-209">MEAR-209</a> &ndash; Change and use a internal unique id instead of artifactId only</li>
<li><a href="https://issues.apache.org/jira/browse/MEAR-259">MEAR-259</a> &ndash; Fix formatting date issues in apt files</li>
</ul>


<p>Dependency upgrades:</p>

<ul>
<li><a href="https://issues.apache.org/jira/browse/MEAR-224">MEAR-224</a> &ndash; Upgrade plexus-archiver from 2.10.3 to 3.0.1</li>
<li><a href="https://issues.apache.org/jira/browse/MEAR-233">MEAR-233</a> &ndash; Upgrade plexus-archiver from 3.0.3 to 3.1.1</li>
<li><a href="https://issues.apache.org/jira/browse/MEAR-235">MEAR-235</a> &ndash; Upgrade maven-archiver to 3.1.0</li>
<li><a href="https://issues.apache.org/jira/browse/MEAR-236">MEAR-236</a> &ndash; Upgrade maven-filtering to 3.1.1</li>
<li><a href="https://issues.apache.org/jira/browse/MEAR-237">MEAR-237</a> &ndash; Upgrade plexus-archiver to 3.3</li>
<li><a href="https://issues.apache.org/jira/browse/MEAR-238">MEAR-238</a> &ndash; Upgrade of plexus-archiver to 3.4.</li>
<li><a href="https://issues.apache.org/jira/browse/MEAR-240">MEAR-240</a> &ndash; Upgrade of maven-archiver to 3.1.1.</li>
<li><a href="https://issues.apache.org/jira/browse/MEAR-245">MEAR-245</a> &ndash; Upgrade of plexus-interpolation to 1.24.</li>
<li><a href="https://issues.apache.org/jira/browse/MEAR-251">MEAR-251</a> &ndash; Upgrade maven-archiver to 3.2.0</li>
<li><a href="https://issues.apache.org/jira/browse/MEAR-252">MEAR-252</a> &ndash; Upgrade plexus-archiver to 3.5.</li>
<li><a href="https://issues.apache.org/jira/browse/MEAR-253">MEAR-253</a> &ndash; Upgrade plexus-utils to version 3.1.0</li>
<li><a href="https://issues.apache.org/jira/browse/MEAR-255">MEAR-255</a> &ndash; Upgrade parent to 31</li>
<li><a href="https://issues.apache.org/jira/browse/MEAR-256">MEAR-256</a> &ndash; Upgrade maven-verifier component</li>
<li><a href="https://issues.apache.org/jira/browse/MEAR-257">MEAR-257</a> &ndash; Upgrade JUnit to 4.12</li>
</ul>


<p>Enjoy,</p>

<p>-The Apache Maven team</p>
</div>
