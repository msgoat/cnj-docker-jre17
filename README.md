# cnj-docker-jre17

Builds a docker image with JRE 17 plus optional features required by msg environments.

The following architectures are supported:
* linux/amd64
* linux/arm64/v8

> __Note__: Primarily intended to be used as a base image for java-based applications which are run within the msg network. 

## Status

![](https://codebuild.eu-west-1.amazonaws.com/badges?uuid=eyJlbmNyeXB0ZWREYXRhIjoiV0d1Qmo1VmNHdUwwUHNjZExvNGxFaEtSN1pBSHR5cUhrSEpVQTlia1RLd2hFbFkyTFJ5MGsrd1l6VFRodGJrNWw1dnord2EyQWdtams4ZkYwMWZHbFJnPSIsIml2UGFyYW1ldGVyU3BlYyI6IjdWVncycTJIZUVRcktiUmYiLCJtYXRlcmlhbFNldFNlcmlhbCI6MX0%3D&branch=main)

## Release information

A changelog can be found in [changelog.md](changelog.md).

## Docker Pull Command

`docker pull docker.cloudtrain.aws.msgoat.eu/msgoat/cnj-docker-jre17`

## HOW-TO build this docker image locally

If all prerequisites are met, just run the following Maven command in the project folder:

```shell 
mvn clean verify
```

Build results: a multi-architecture Docker image
