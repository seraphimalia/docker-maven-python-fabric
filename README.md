# docker-maven-python-fabric

## Purpose

This image was created specifically for usage with continuous integration systems, and contains the minimum requirements to deploy a maven based java project to vm's using [Python Fabric](http://www.fabfile.org/index.html). Currently being used with [wercker](https://app.wercker.com), but should meet the requirements for most CI systems.

## Details

### Base Image

* [maven:3-jdk-7](https://hub.docker.com/_/maven/) - Maven 3 and JDK 7

### Additional Node Modules

* [Python Fabric](http://www.fabfile.org/index.html) - Fabric is a Python (2.5-2.7) library and command-line tool for streamlining the use of SSH for application deployment or systems administration tasks.
