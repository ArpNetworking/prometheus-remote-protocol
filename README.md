Prometheus Remote Protocol
===========================

<a href="https://raw.githubusercontent.com/ArpNetworking/prometheus-remote-protocol/master/LICENSE">
    <img src="https://img.shields.io/hexpm/l/plug.svg"
         alt="License: Apache 2">
</a>
<a href="https://travis-ci.com/ArpNetworking/prometheus-remote-protocol">
    <img src="https://travis-ci.com/ArpNetworking/prometheus-remote-protocol.svg?branch=master"
         alt="Travis Build">
</a>
<a href="http://search.maven.org/#search%7Cga%7C1%7Cg%3A%22com.arpnetworking.metrics%22%20a%3A%22prometheus-remote-protocol%22">
    <img src="https://img.shields.io/maven-central/v/com.arpnetworking.metrics/prometheus-remote-protocol.svg"
         alt="Maven Artifact">
</a>

Building
--------

Prerequisites:
* [JDK8](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)

Building:

    prometheus-remote-protocol> ./mvnw verify

To use the local version you must first install it locally:

    prometheus-remote-protocol> ./mvnw install

You can determine the version of the local build from the pom file.  Using the local version is intended only for testing or development.

You may also need to add the local repository to your build in order to pick-up the local version:

* Maven - Included by default.
* Gradle - Add *mavenLocal()* to *build.gradle* in the *repositories* block.
* SBT - Add *resolvers += Resolver.mavenLocal* into *project/plugins.sbt*.

License
-------

Published under Apache Software License 2.0, see LICENSE

&copy; Bruno Green., 2018
