---
layout: post
title: "Apache Shared Component: Maven Dependency Tree Version 3.2.0 Released"
date: '2022-08-25T17:15:15+00:00'
permalink: apache-maven-dependency-tree-3-2-0
categories:
- Maven
- Maven-Shared
---
The Apache Maven team is pleased to announce the release of the
[Apache Shared Component: Apache Maven Dependency Tree Version 3.2.0](https://maven.apache.org/shared/maven-dependency-tree/)

A tree-based API for resolution of Maven project dependencies.

```xml
<plugin>
  <groupId>org.apache.maven.shared</groupId>
  <artifactId>maven-dependency-tree</artifactId>
  <version>3.2.0</version>
</plugin>
```

[Release Notes Apache Shared Componet Maven Dependency Tree 3.2.0](https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12317922&version=12351759)

* Bug:

    * [MSHARED-1016](https://issues.apache.org/jira/browse/MSHARED-1016) - Transitive provided dependencies are not removed from collected dependency graph

* Improvements:

    * [MSHARED-1070](https://issues.apache.org/jira/browse/MSHARED-1070) - Migrate plexus component to JSR-330
    * [MSHARED-1071](https://issues.apache.org/jira/browse/MSHARED-1071) - Drop maven 3.0 compatibility

* Dependency upgrade:

    * [MSHARED-1114](https://issues.apache.org/jira/browse/MSHARED-1114) - Bump maven-shared-components from 36 to 37

Enjoy,

-The Maven team
