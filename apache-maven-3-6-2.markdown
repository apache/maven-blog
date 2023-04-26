---
layout: post
title: "Apache Maven 3.6.2 Released"
date: '2019-09-07T16:30:00+00:00'
permalink: apache-maven-3-6-1
categories:
  - Maven
  - Maven-Releases
---
The Apache Maven team is pleased to announce the release of the Apache
Maven 3.6.2.

Apache Maven is a software project management and comprehension tool. Based
on the concept of a project object model (POM), Maven can manage a
project's build, reporting and documentation from a central piece of
information.

You can find out more about Apache Maven at https://maven.apache.org

You can download the appropriate sources etc. from
the [download page](https://maven.apache.org/download.cgi)

<!-- more -->

We really value the contributions of these non committers, so this section is
focused on those individuals. Descriptions of the issues fixed can be found at
the [end of these release notes](#Details).

Issue Reporters of this release:

* Benoit GUERIN
* Christian Schulte
* Elliotte Rusty Harold
* Falko Modler
* Francesco Chicchiriccò
* Guillaume Nodet,
* guofei
* Joseph Walton
* Louis Mills
* Mark Derricutt,
* Mark McKelvy
* Mickael Istria
* Nicolas Echegut
* Nicolas Radde
* Raphael Rösch
* Ray Tsang
* Robert Thornton
* Rohan Padhye
* Sergey Chernov
* Stefan Oehme
* Thibaud Lepretre
* zhb.

Code Contributors of this release:

* Guillaume Nodet
* Mickael Istria
* Ray Tsang
* Stefan Oehme
* Joseph Walton
* Bo Zhang
* AElMehdi
* Christian Schulte
* Mao Shuai
* MartinKanters
* Sergey Chernov
* Jesse Glick.

Many thanks to all reporters and contributors for their time and support.

(Please send an email to the dev list if we missed one to mention).

## Known Issues

None.

## Overview about the changes

- This release focuses mostly performance improvements, better memory footprint, and less CPU usage.

- We are continuing to convert Maven Core to use JSR 330 annotations instead of Plexus
  (still not finished, see MNG-5577).

- New support for ‘release’ qualifier (see MNG-6655).

- The `toolchain.xml` file supports environment variables (see MNG-6665).


## User visible Changes

`toolchain.xml` now supports usage of environment variables which looks like this:

```xml
<toolchain>
    <type>jdk</type>
    <provides>
      <version>1.8</version>
      <vendor>sun</vendor>
    </provides>
    <configuration>
	<jdkHome>${env.JDK_HOME_8}</jdkHome>
    </configuration>
</toolchain>
```
## The detailed issue list[](#Details)

### Bugs:

- [MNG-6375](https://issues.apache.org/jira/browse/MNG-6375) - NullPointerException when pom.xml has incomplete XML tag
- [MNG-6626](https://issues.apache.org/jira/browse/MNG-6626) - NullPointerException in DefaultExceptionHandler
- [MNG-6629](https://issues.apache.org/jira/browse/MNG-6629) - DefaultModelValidator.validateId is inefficient
- [MNG-6630](https://issues.apache.org/jira/browse/MNG-6630) - ComparableVersion.parseVersion is inefficient
- [MNG-6631](https://issues.apache.org/jira/browse/MNG-6631) - DefaultArtifactVersion.parseVersion is inefficient
- [MNG-6632](https://issues.apache.org/jira/browse/MNG-6632) - ArtifactHandlerManager.getArtifactHandler is inefficient
- [MNG-6633](https://issues.apache.org/jira/browse/MNG-6633) - ExcludesArtifactFilter is a memory hog
- [MNG-6636](https://issues.apache.org/jira/browse/MNG-6636) - NPE on reporting convertion (DefaultReportingConverter) when inheritance of with no reports
- [MNG-6639](https://issues.apache.org/jira/browse/MNG-6639) - Child inherit.append.path attributes not defined in Maven POM XSD
- [MNG-6642](https://issues.apache.org/jira/browse/MNG-6642) - Tycho-based modules do not build with 3.6.1 (works with 3.6.0)
- [MNG-6643](https://issues.apache.org/jira/browse/MNG-6643) - Version comparison CLI does not work anymore
- [MNG-6644](https://issues.apache.org/jira/browse/MNG-6644) - NPE in DefaultReportingConverter when reports has no InputLocation (using polyglot Maven)
- [MNG-6647](https://issues.apache.org/jira/browse/MNG-6647) - NPE in DefaultReportingConverter (when reports injected by Repaint IO maven-tiles)
- [MNG-6653](https://issues.apache.org/jira/browse/MNG-6653) - DefaultProjectBuildingRequest copy constructor does not copy all fields
- [MNG-6668](https://issues.apache.org/jira/browse/MNG-6668) - Model location handling uses too much memory
- [MNG-6669](https://issues.apache.org/jira/browse/MNG-6669) - Tycho cannot resolve project dependencies
- [MNG-6700](https://issues.apache.org/jira/browse/MNG-6700) - Equal compile source roots are added multiple times
- [MNG-6703](https://issues.apache.org/jira/browse/MNG-6703) - DefaultUrlNormalizer doesn't normalize all relative URIs
- [MNG-6704](https://issues.apache.org/jira/browse/MNG-6704) - MavenRepositorySystemUtils.newSession() misses assignment
- [MNG-6707](https://issues.apache.org/jira/browse/MNG-6707) - Maven XML parser does not accept '>' in XML processing instructions
- [MNG-6712](https://issues.apache.org/jira/browse/MNG-6712) - Downgrade maven-resolver:1.4.0 to 1.3.3
- [MNG-6713](https://issues.apache.org/jira/browse/MNG-6713) - Fix ExclusionArtifactFilter to respect wildcard
- [MNG-6716](https://issues.apache.org/jira/browse/MNG-6716) - relative testSourceDirectory on macos throw duplicate class error
- [MNG-6720](https://issues.apache.org/jira/browse/MNG-6720) - MultiThreadedBuilder: wait for parallel running projects when using --fail-fast
- [MNG-6723](https://issues.apache.org/jira/browse/MNG-6723) - MavenProject.getParentFile() not set when using ProjectBuilder.build(List<File>, ...)

### Improvements

- [MNG-6069](https://issues.apache.org/jira/browse/MNG-6069) - Migrate to non deprecated parts of Commons CLI
- [MNG-6638](https://issues.apache.org/jira/browse/MNG-6638) - Prevent reparsing POMs in MavenMetadataSource
- [MNG-6655](https://issues.apache.org/jira/browse/MNG-6655) - Add support for "release" qualifier
- [MNG-6665](https://issues.apache.org/jira/browse/MNG-6665) - toolchain.xml file should support environment variables
- [MNG-6667](https://issues.apache.org/jira/browse/MNG-6667) - Hint at Maven upgrade requirement when trying to build a pom.xml with a newer modelVersion
- [MNG-6675](https://issues.apache.org/jira/browse/MNG-6675) - Make Resolver debug log messages for projects and plugins consistent
- [MNG-6695](https://issues.apache.org/jira/browse/MNG-6695) - Improve speed in collection merging
- [MNG-6696](https://issues.apache.org/jira/browse/MNG-6696) - Speed improvements while parsing big reactor projects
- [MNG-6697](https://issues.apache.org/jira/browse/MNG-6697) - Add a fast interpolator not using reflection
- [MNG-6698](https://issues.apache.org/jira/browse/MNG-6698) - Lazily compute the ManagedVersionMap
- [MNG-6701](https://issues.apache.org/jira/browse/MNG-6701) - Document maven.repo.local system property
- [MNG-6702](https://issues.apache.org/jira/browse/MNG-6702) - Improve DefaultModelValidator performance
- [MNG-6705](https://issues.apache.org/jira/browse/MNG-6705) - Speep up Artifact version check and Parent interpolation
- [MNG-6718](https://issues.apache.org/jira/browse/MNG-6718) - Upgrade Plexus Utils to 3.2.1
- [MNG-6729](https://issues.apache.org/jira/browse/MNG-6729) - StringSearchModelInterpolator introspects objects from Java API
- [MNG-6747](https://issues.apache.org/jira/browse/MNG-6747) - Generalize 'resume from' message when build reactor fails

### Test

- [MNG-6535](https://issues.apache.org/jira/browse/MNG-6535) - Improve test coverage of org.apache.maven.model.path.DefaultUrlNormalizer

### Wish

### Task

- [MNG-6681](https://issues.apache.org/jira/browse/MNG-6681) - improve documentation: dependency type = file classifier(optional)+extension + additional hints on dependency features

### Dependency upgrade

- [MNG-6549](https://issues.apache.org/jira/browse/MNG-6549) - Remove unused transitive dependencies of Guava
- [MNG-6627](https://issues.apache.org/jira/browse/MNG-6627) - upgrade plexus-component-metadata to 2.0.0 to get reproducible `META-INF/plexus/components.xml`
- [MNG-6646](https://issues.apache.org/jira/browse/MNG-6646) - Upgrade maven-assembly-plugin to 3.1.1
- [MNG-6671](https://issues.apache.org/jira/browse/MNG-6671) - Upgrade Modello to 1.11
- [MNG-6674](https://issues.apache.org/jira/browse/MNG-6674) - Upgrade Wagon to 3.3.3
- [MNG-6738](https://issues.apache.org/jira/browse/MNG-6738) - Upgrade maven-resolver to 1.4.1


### Sub Tasks

- [MNG-6680](https://issues.apache.org/jira/browse/MNG-6680) - Convert Maven Settings Builder to JSR 330
- [MNG-6685](https://issues.apache.org/jira/browse/MNG-6685) - Convert Maven Model Builder to JSR 330
- [MNG-6686](https://issues.apache.org/jira/browse/MNG-6686) - Convert Maven Embedder to JSR 330

The full list of changes can be found in our [issue management system][4].

## Complete Release Notes

See [complete release notes for all versions][5]

- The Apache Maven Team.


[0]: ../../download.html
[1]: ../../plugins/index.html
[2]: https://maven.apache.org/
[4]: https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12316922&version=12345234
[5]: ../../docs/history.html
[MNG-6680]: https://issues.apache.org/jira/browse/MNG-6680
[MNG-6685]: https://issues.apache.org/jira/browse/MNG-6685
[MNG-6686]: https://issues.apache.org/jira/browse/MNG-6686
[MNG-6375]: https://issues.apache.org/jira/browse/MNG-6375
[MNG-6626]: https://issues.apache.org/jira/browse/MNG-6626
[MNG-6629]: https://issues.apache.org/jira/browse/MNG-6629
[MNG-6630]: https://issues.apache.org/jira/browse/MNG-6630
[MNG-6631]: https://issues.apache.org/jira/browse/MNG-6631
[MNG-6632]: https://issues.apache.org/jira/browse/MNG-6632
[MNG-6633]: https://issues.apache.org/jira/browse/MNG-6633
[MNG-6636]: https://issues.apache.org/jira/browse/MNG-6636
[MNG-6639]: https://issues.apache.org/jira/browse/MNG-6639
[MNG-6642]: https://issues.apache.org/jira/browse/MNG-6642
[MNG-6643]: https://issues.apache.org/jira/browse/MNG-6643
[MNG-6644]: https://issues.apache.org/jira/browse/MNG-6644
[MNG-6647]: https://issues.apache.org/jira/browse/MNG-6647
[MNG-6653]: https://issues.apache.org/jira/browse/MNG-6653
[MNG-6668]: https://issues.apache.org/jira/browse/MNG-6668
[MNG-6669]: https://issues.apache.org/jira/browse/MNG-6669
[MNG-6700]: https://issues.apache.org/jira/browse/MNG-6700
[MNG-6703]: https://issues.apache.org/jira/browse/MNG-6703
[MNG-6704]: https://issues.apache.org/jira/browse/MNG-6704
[MNG-6707]: https://issues.apache.org/jira/browse/MNG-6707
[MNG-6712]: https://issues.apache.org/jira/browse/MNG-6712
[MNG-6713]: https://issues.apache.org/jira/browse/MNG-6713
[MNG-6716]: https://issues.apache.org/jira/browse/MNG-6716
[MNG-6720]: https://issues.apache.org/jira/browse/MNG-6720
[MNG-6723]: https://issues.apache.org/jira/browse/MNG-6723
[MNG-6069]: https://issues.apache.org/jira/browse/MNG-6069
[MNG-6638]: https://issues.apache.org/jira/browse/MNG-6638
[MNG-6655]: https://issues.apache.org/jira/browse/MNG-6655
[MNG-6665]: https://issues.apache.org/jira/browse/MNG-6665
[MNG-6667]: https://issues.apache.org/jira/browse/MNG-6667
[MNG-6675]: https://issues.apache.org/jira/browse/MNG-6675
[MNG-6695]: https://issues.apache.org/jira/browse/MNG-6695
[MNG-6696]: https://issues.apache.org/jira/browse/MNG-6696
[MNG-6697]: https://issues.apache.org/jira/browse/MNG-6697
[MNG-6698]: https://issues.apache.org/jira/browse/MNG-6698
[MNG-6701]: https://issues.apache.org/jira/browse/MNG-6701
[MNG-6702]: https://issues.apache.org/jira/browse/MNG-6702
[MNG-6705]: https://issues.apache.org/jira/browse/MNG-6705
[MNG-6729]: https://issues.apache.org/jira/browse/MNG-6729
[MNG-6747]: https://issues.apache.org/jira/browse/MNG-6747
[MNG-6535]: https://issues.apache.org/jira/browse/MNG-6535
[MNG-6681]: https://issues.apache.org/jira/browse/MNG-6681
[MNG-6549]: https://issues.apache.org/jira/browse/MNG-6549
[MNG-6627]: https://issues.apache.org/jira/browse/MNG-6627
[MNG-6646]: https://issues.apache.org/jira/browse/MNG-6646
[MNG-6671]: https://issues.apache.org/jira/browse/MNG-6671
[MNG-6674]: https://issues.apache.org/jira/browse/MNG-6674
[MNG-6718]: https://issues.apache.org/jira/browse/MNG-6718
[MNG-6738]: https://issues.apache.org/jira/browse/MNG-6738
