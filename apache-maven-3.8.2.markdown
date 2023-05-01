---
layout: post
title: "Apache Maven 3.8.2 Released"
date: '2021-08-15T13:34:44+00:00'
permalink: apache-maven-3-8-2
categories:
  - Maven-Core-Releases
---
The Apache Maven team is pleased to announce the release of the [Apache Maven 3.8.2](https://maven.apache.org/ref/3.8.2/)

Apache Maven is a software project management and comprehension tool. Based on the concept
of a project object model (POM), Maven can manage a project's build, reporting and documentation
from a central piece of information.

Maven 3.8.2 is available via https://maven.apache.org/download.cgi

The core release is independent of plugin releases. Further releases of plugins will be made
separately.

If you have any questions, please consult:

- the web site: https://maven.apache.org/
- the maven-user mailing list: https://maven.apache.org/mailing-lists.html
- the reference documentation: https://maven.apache.org/ref/3.8.2/

Release Notes - Maven - Version 3.8.2

* Sub-task
    * [MNG-6281](https://issues.apache.org/jira/browse/MNG-6281) - ArrayIndexOutOfBoundsException caused by pom.xml with invalid/duplicate XML

* Bugs:
    * [MNG-4706](https://issues.apache.org/jira/browse/MNG-4706) - Multithreaded building can create bad files for downloaded artifacts in local repository
    * [MNG-5307](https://issues.apache.org/jira/browse/MNG-5307) - NPE during resolution of dependencies - parallel mode
    * [MNG-5315](https://issues.apache.org/jira/browse/MNG-5315) - Artifact resolution sporadically fails in parallel builds
    * [MNG-5838](https://issues.apache.org/jira/browse/MNG-5838) - Maven on No-File-Lock Systems
    * [MNG-5868](https://issues.apache.org/jira/browse/MNG-5868) - Adding serval times the same artifact via MavenProjectHelper (attachArtifact) keep adding to the List duplicate artifacts
    * [MNG-6071](https://issues.apache.org/jira/browse/MNG-6071) - GetResource ('/) returns 'null' if build is started with -f
    * [MNG-6216](https://issues.apache.org/jira/browse/MNG-6216) - ArrayIndexOutOfBoundsException when parsing POM
    * [MNG-6239](https://issues.apache.org/jira/browse/MNG-6239) - Jansi messes up System.err and System.out
    * [MNG-6380](https://issues.apache.org/jira/browse/MNG-6380) - Option -Dstyle.color=always doesn't force color output
    * [MNG-6604](https://issues.apache.org/jira/browse/MNG-6604) - Intermittent failures while downloading GAVs from Nexus
    * [MNG-6648](https://issues.apache.org/jira/browse/MNG-6648) - 'mavenrc_pre' script does not receive arguments like mavenrc in Bourne shell does
    * [MNG-6719](https://issues.apache.org/jira/browse/MNG-6719) - mvn color output escape keys w/ "| tee xxx.log" on Win with git/bash
    * [MNG-6737](https://issues.apache.org/jira/browse/MNG-6737) - StackOverflowError when version ranges are unsolvable and graph contains a cycle
    * [MNG-6767](https://issues.apache.org/jira/browse/MNG-6767) - Plugin with ${project.groupId} resolved improperly
    * [MNG-6819](https://issues.apache.org/jira/browse/MNG-6819) - NullPointerException for DefaultArtifactDescriptorReader.loadPom
    * [MNG-6828](https://issues.apache.org/jira/browse/MNG-6828) - DependencyResolutionException breaks serialization
    * [MNG-6842](https://issues.apache.org/jira/browse/MNG-6842) - ProjectBuilderTest uses Guava, but Guava is not defined in dependencies
    * [MNG-6843](https://issues.apache.org/jira/browse/MNG-6843) - Parallel build fails due to missing JAR artifacts in compilePath
    * [MNG-6850](https://issues.apache.org/jira/browse/MNG-6850) - Prevent printing the EXEC_DIR when it's just a disk letter
    * [MNG-6921](https://issues.apache.org/jira/browse/MNG-6921) - Maven compile with properties ${artifactId} and ${project.build.finalName} occurs java.lang.NullPointerException
    * [MNG-6937](https://issues.apache.org/jira/browse/MNG-6937) - StringSearchModelInterpolatorTest fails on symlinked paths
    * [MNG-6964](https://issues.apache.org/jira/browse/MNG-6964) - Maven version sorting is internally inconsistent
    * [MNG-6983](https://issues.apache.org/jira/browse/MNG-6983) - Plugin key can get out of sync with artifactId and groupId
    * [MNG-7000](https://issues.apache.org/jira/browse/MNG-7000) - metadata.mdo contains invalid link to schema
    * [MNG-7032](https://issues.apache.org/jira/browse/MNG-7032) - Option -B still showing formatting when used with --version
    * [MNG-7034](https://issues.apache.org/jira/browse/MNG-7034) - StackOverflowError thrown if a cycle exists in BOM imports
    * [MNG-7090](https://issues.apache.org/jira/browse/MNG-7090) - mvnDebug does not work on Java 11+
    * [MNG-7127](https://issues.apache.org/jira/browse/MNG-7127) - NullPointerException in MavenCliTest.testStyleColors in JDK 16
    * [MNG-7155](https://issues.apache.org/jira/browse/MNG-7155) - make sources jar reproducible (upgrade maven-source-plugin to 3.2.1)
    * [MNG-7161](https://issues.apache.org/jira/browse/MNG-7161) - Error thrown during uninstalling of JAnsi

* New Feature
    * [MNG-7149](https://issues.apache.org/jira/browse/MNG-7149) - Introduce MAVEN_DEBUG_ADDRESS in mvnDebug scripts

* Improvements:
    * [MNG-2802](https://issues.apache.org/jira/browse/MNG-2802) - Concurrent-safe access to local Maven repository
    * [MNG-6471](https://issues.apache.org/jira/browse/MNG-6471) - Parallel builder should use  the module name as thread name
    * [MNG-6754](https://issues.apache.org/jira/browse/MNG-6754) - Set the same timestamp in multi module builds
    * [MNG-6810](https://issues.apache.org/jira/browse/MNG-6810) - Remove profiles in maven-model
    * [MNG-6811](https://issues.apache.org/jira/browse/MNG-6811) - Remove unnecessary filtering configuration
    * [MNG-6816](https://issues.apache.org/jira/browse/MNG-6816) - Prefer System.lineSeparator() over system properties
    * [MNG-6827](https://issues.apache.org/jira/browse/MNG-6827) - Replace deprecated StringUtils#defaultString() from Plexus Utils
    * [MNG-6837](https://issues.apache.org/jira/browse/MNG-6837) - Simplify detection of the MAVEN_HOME and make it fully qualified on Windows
    * [MNG-6844](https://issues.apache.org/jira/browse/MNG-6844) - Use StandardCharsets and remove outdated @SuppressWarnings
    * [MNG-6853](https://issues.apache.org/jira/browse/MNG-6853) - Don't box primitives where it's not needed
    * [MNG-6859](https://issues.apache.org/jira/browse/MNG-6859) - Build not easily reproducible when built from source release archive
    * [MNG-6873](https://issues.apache.org/jira/browse/MNG-6873) - Inconsistent library versions notice
    * [MNG-6967](https://issues.apache.org/jira/browse/MNG-6967) - Improve the command line output from maven-artifact
    * [MNG-6987](https://issues.apache.org/jira/browse/MNG-6987) - Reorder groupId before artifactId when writing an exclusion using maven-model
    * [MNG-7010](https://issues.apache.org/jira/browse/MNG-7010) - Omit "NB: JAVA_HOME should point to a JDK not a JRE" except when that is the problem
    * [MNG-7064](https://issues.apache.org/jira/browse/MNG-7064) - Use HTTPS for schema location in global settings.xml
    * [MNG-7080](https://issues.apache.org/jira/browse/MNG-7080) - Add a --color option
    * [MNG-7170](https://issues.apache.org/jira/browse/MNG-7170) - Allow to associate pomFile/${basedir} with DefaultProjectBuilder.build(ModelSource, ...)
    * [MNG-7180](https://issues.apache.org/jira/browse/MNG-7180) - Make --color option behave more like BSD/GNU grep's --color option
    * [MNG-7181](https://issues.apache.org/jira/browse/MNG-7181) - Make --version support -q
    * [MNG-7185](https://issues.apache.org/jira/browse/MNG-7185) - Describe explicit and recommended version for VersionRange.createFromVersionSpec()
    * [MNG-7190](https://issues.apache.org/jira/browse/MNG-7190) - Load mavenrc from /usr/local/etc also in Bourne shell script

* Tasks:
    * [MNG-6598](https://issues.apache.org/jira/browse/MNG-6598) - Maven 3.6.0 and Surefire problem
    * [MNG-6884](https://issues.apache.org/jira/browse/MNG-6884) - Cleanup POM File after version upgrade
    * [MNG-7172](https://issues.apache.org/jira/browse/MNG-7172) - Remove expansion of Jansi native libraries
    * [MNG-7184](https://issues.apache.org/jira/browse/MNG-7184) - document .mavenrc/maven_pre.bat|cmd scripts and MAVEN_SKIP_RC environment variable

* Dependency upgrades:
    * [MNG-6872](https://issues.apache.org/jira/browse/MNG-6872) - Found CVEs in your dependencies - plexus-utils (tests)
    * [MNG-6874](https://issues.apache.org/jira/browse/MNG-6874) - Upgrade Maven Parent to 34
    * [MNG-6886](https://issues.apache.org/jira/browse/MNG-6886) - Upgrade plexus-cipher 1.8
    * [MNG-6993](https://issues.apache.org/jira/browse/MNG-6993) - Upgrade SLF4J to 1.7.30
    * [MNG-7152](https://issues.apache.org/jira/browse/MNG-7152) - Upgrade Maven Resolver to 1.6.3
    * [MNG-7177](https://issues.apache.org/jira/browse/MNG-7177) - Upgrade Maven Shared Utils to 3.3.4
    * [MNG-7179](https://issues.apache.org/jira/browse/MNG-7179) - Upgrade Jansi to 2.3.3
    * [MNG-7186](https://issues.apache.org/jira/browse/MNG-7186) - Upgrade Guice to 4.2.2
    * [MNG-7196](https://issues.apache.org/jira/browse/MNG-7196) - Upgrade Jansi to 2.3.4
    * [MNG-7198](https://issues.apache.org/jira/browse/MNG-7198) - Upgrade SLF4J to 1.7.32

* Known Issues:

    * If any of your plugin mojos spawn new threads there might be a change in class loading as a result of the
      fix for https://issues.apache.org/jira/browse/MNG-6843.
      See https://lists.apache.org/thread.html/r0777c9e364f93a609cb4c3da6e634139b9c400166e280856ee25ba72%40%3Cdev.maven.apache.org%3E
      with a possible fix for your plugin mojo as well as a potential general fix
      in https://issues.apache.org/jira/browse/MNG-7212.
    * If any or your projects rely a Maven Core artifacts and your build is performed with Maven 3.8.1 or later a transitive
      dependency parent of Sisu Plexus/CPI API 1.0 will inject a remote repository over HTTP which will be blocked by
      default and (might) lead to build failures.
      See https://lists.apache.org/thread.html/rda29028b2c8985f3b94e721d3014a948b312fbddf95ffaa4971acc03%40%3Cusers.maven.apache.org%3E
      and https://issues.apache.org/jira/browse/MNG-7214 for details.

For more information read https://maven.apache.org/docs/3.8.2/release-notes.html

Enjoy!

- The Maven Team
