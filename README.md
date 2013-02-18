Find Security Bugs Sonar Plugin
===================

A Sonar plugin for running [Find Security Bugs](http://h3xstream.github.com/find-sec-bugs/) rules in your Sonar analysis.

All rules are set to a default priority of major - this can be customized in your quality profiles.

## Build

To build this Sonar plugin you need [Maven](https://maven.apache.org/) installed. 

1. Fetch or download the latest version of the master branch.
2. Got to your command line and exectue: `mvn package`
3. The plugin is built to `target/find-sec-bugs-{version}.jar`

## Install 

Simply copy the file resulting from the build to the $SONAR_HOME/extensions/plugins/ and restart your Sonar server.
