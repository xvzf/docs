<!--

********************************************************************************

WARNING:

    DO NOT EDIT "gradle/README.md"

    IT IS AUTO-GENERATED

    (from the other files in "gradle/" combined with a set of templates)

********************************************************************************

-->

**Note:** this is the "per-architecture" repository for the `ppc64le` builds of [the `gradle` official image](https://hub.docker.com/_/gradle) -- for more information, see ["Architectures other than amd64?" in the official images documentation](https://github.com/docker-library/official-images#architectures-other-than-amd64) and ["An image's source changed in Git, now what?" in the official images FAQ](https://github.com/docker-library/faq#an-images-source-changed-in-git-now-what).

# Quick reference

-	**Maintained by**:  
	[Keegan Witt (of the Groovy Project)](https://github.com/keeganwitt/docker-gradle), [with the Gradle Project's approval](https://discuss.gradle.org/t/official-docker-images/21159/8)

-	**Where to get help**:  
	[the Docker Community Slack](https://dockr.ly/comm-slack), [Server Fault](https://serverfault.com/help/on-topic), [Unix & Linux](https://unix.stackexchange.com/help/on-topic), or [Stack Overflow](https://stackoverflow.com/help/on-topic)

# Supported tags and respective `Dockerfile` links

-	[`8.1.1-jdk8`, `8.1-jdk8`, `8-jdk8`, `jdk8`, `8.1.1-jdk8-jammy`, `8.1-jdk8-jammy`, `8-jdk8-jammy`, `jdk8-jammy`](https://github.com/keeganwitt/docker-gradle/blob/01f24d7f28637c911d3c2f0650b52d08f526b57f/jdk8/Dockerfile)
-	[`8.1.1-jdk8-focal`, `8.1-jdk8-focal`, `8-jdk8-focal`, `jdk8-focal`](https://github.com/keeganwitt/docker-gradle/blob/01f24d7f28637c911d3c2f0650b52d08f526b57f/jdk8-focal/Dockerfile)
-	[`8.1.1-jdk11`, `8.1-jdk11`, `8-jdk11`, `jdk11`, `8.1.1-jdk11-jammy`, `8.1-jdk11-jammy`, `8-jdk11-jammy`, `jdk11-jammy`](https://github.com/keeganwitt/docker-gradle/blob/01f24d7f28637c911d3c2f0650b52d08f526b57f/jdk11/Dockerfile)
-	[`8.1.1-jdk11-focal`, `8.1-jdk11-focal`, `8-jdk11-focal`, `jdk11-focal`](https://github.com/keeganwitt/docker-gradle/blob/01f24d7f28637c911d3c2f0650b52d08f526b57f/jdk11-focal/Dockerfile)
-	[`8.1.1-jdk17`, `8.1-jdk17`, `8-jdk17`, `jdk17`, `8.1.1-jdk`, `8.1-jdk`, `8-jdk`, `jdk`, `8.1.1`, `8.1`, `8`, `latest`, `8.1.1-jdk17-jammy`, `8.1-jdk17-jammy`, `8-jdk17-jammy`, `jdk17-jammy`, `8.1.1-jdk-jammy`, `8.1-jdk-jammy`, `8-jdk-jammy`, `jdk-jammy`, `8.1.1-jammy`, `8.1-jammy`, `8-jammy`, `jammy`](https://github.com/keeganwitt/docker-gradle/blob/01f24d7f28637c911d3c2f0650b52d08f526b57f/jdk17/Dockerfile)
-	[`8.1.1-jdk17-focal`, `8.1-jdk17-focal`, `8-jdk17-focal`, `jdk17-focal`, `8.1.1-jdk-focal`, `8.1-jdk-focal`, `8-jdk-focal`, `jdk-focal`, `8.1.1-focal`, `8.1-focal`, `8-focal`, `focal`](https://github.com/keeganwitt/docker-gradle/blob/01f24d7f28637c911d3c2f0650b52d08f526b57f/jdk17-focal/Dockerfile)
-	[`7.6.1-jdk8`, `7.6-jdk8`, `7-jdk8`, `7.6.1-jdk8-jammy`, `7.6-jdk8-jammy`, `7-jdk8-jammy`](https://github.com/keeganwitt/docker-gradle/blob/d67e322404924034e73ade97552ff7b1ffd6bbca/jdk8/Dockerfile)
-	[`7.6.1-jdk8-focal`, `7.6-jdk8-focal`, `7-jdk8-focal`](https://github.com/keeganwitt/docker-gradle/blob/d67e322404924034e73ade97552ff7b1ffd6bbca/jdk8-focal/Dockerfile)
-	[`7.6.1-jdk11`, `7.6-jdk11`, `7-jdk11`, `7.6.1-jdk11-jammy`, `7.6-jdk11-jammy`, `7-jdk11-jammy`](https://github.com/keeganwitt/docker-gradle/blob/d67e322404924034e73ade97552ff7b1ffd6bbca/jdk11/Dockerfile)
-	[`7.6.1-jdk11-focal`, `7.6-jdk11-focal`, `7-jdk11-focal`](https://github.com/keeganwitt/docker-gradle/blob/d67e322404924034e73ade97552ff7b1ffd6bbca/jdk11-focal/Dockerfile)
-	[`7.6.1-jdk17`, `7.6-jdk17`, `7-jdk17`, `7.6.1-jdk`, `7.6-jdk`, `7-jdk`, `7.6.1`, `7.6`, `7`, `7.6.1-jdk17-jammy`, `7.6-jdk17-jammy`, `7-jdk17-jammy`, `7.6.1-jdk-jammy`, `7.6-jdk-jammy`, `7-jdk-jammy`, `7.6.1-jammy`, `7.6-jammy`, `7-jammy`](https://github.com/keeganwitt/docker-gradle/blob/d67e322404924034e73ade97552ff7b1ffd6bbca/jdk17/Dockerfile)
-	[`7.6.1-jdk17-focal`, `7.6-jdk17-focal`, `7-jdk17-focal`, `7.6.1-jdk-focal`, `7.6-jdk-focal`, `7-jdk-focal`, `7.6.1-focal`, `7.6-focal`, `7-focal`](https://github.com/keeganwitt/docker-gradle/blob/d67e322404924034e73ade97552ff7b1ffd6bbca/jdk17-focal/Dockerfile)
-	[`6.9.4-jdk8`, `6.9-jdk8`, `6-jdk8`, `6.9.4-jdk8-jammy`, `6.9-jdk8-jammy`, `6-jdk8-jammy`](https://github.com/keeganwitt/docker-gradle/blob/71d126ec98c6eda90e1818a575486e461adef750/jdk8/Dockerfile)
-	[`6.9.4-jdk8-focal`, `6.9-jdk8-focal`, `6-jdk8-focal`](https://github.com/keeganwitt/docker-gradle/blob/71d126ec98c6eda90e1818a575486e461adef750/jdk8-focal/Dockerfile)
-	[`6.9.4-jdk11`, `6.9-jdk11`, `6-jdk11`, `6.9.4-jdk11-jammy`, `6.9-jdk11-jammy`, `6-jdk11-jammy`](https://github.com/keeganwitt/docker-gradle/blob/71d126ec98c6eda90e1818a575486e461adef750/jdk11/Dockerfile)
-	[`6.9.4-jdk11-focal`, `6.9-jdk11-focal`, `6-jdk11-focal`](https://github.com/keeganwitt/docker-gradle/blob/71d126ec98c6eda90e1818a575486e461adef750/jdk11-focal/Dockerfile)
-	[`6.9.4-jdk17`, `6.9-jdk17`, `6-jdk17`, `6.9.4-jdk`, `6.9-jdk`, `6-jdk`, `6.9.4`, `6.9`, `6`, `6.9.4-jdk17-jammy`, `6.9-jdk17-jammy`, `6-jdk17-jammy`, `6.9.4-jdk-jammy`, `6.9-jdk-jammy`, `6-jdk-jammy`, `6.9.4-jammy`, `6.9-jammy`, `6-jammy`](https://github.com/keeganwitt/docker-gradle/blob/71d126ec98c6eda90e1818a575486e461adef750/jdk17/Dockerfile)
-	[`6.9.4-jdk17-focal`, `6.9-jdk17-focal`, `6-jdk17-focal`, `6.9.4-jdk-focal`, `6.9-jdk-focal`, `6-jdk-focal`, `6.9.4-focal`, `6.9-focal`, `6-focal`](https://github.com/keeganwitt/docker-gradle/blob/71d126ec98c6eda90e1818a575486e461adef750/jdk17-focal/Dockerfile)

[![ppc64le/gradle build status badge](https://img.shields.io/jenkins/s/https/doi-janky.infosiftr.net/job/multiarch/job/ppc64le/job/gradle.svg?label=ppc64le/gradle%20%20build%20job)](https://doi-janky.infosiftr.net/job/multiarch/job/ppc64le/job/gradle/)

# Quick reference (cont.)

-	**Where to file issues**:  
	[https://github.com/keeganwitt/docker-gradle/issues](https://github.com/keeganwitt/docker-gradle/issues?q=)

-	**Supported architectures**: ([more info](https://github.com/docker-library/official-images#architectures-other-than-amd64))  
	[`amd64`](https://hub.docker.com/r/amd64/gradle/), [`arm32v7`](https://hub.docker.com/r/arm32v7/gradle/), [`arm64v8`](https://hub.docker.com/r/arm64v8/gradle/), [`ppc64le`](https://hub.docker.com/r/ppc64le/gradle/), [`s390x`](https://hub.docker.com/r/s390x/gradle/)

-	**Published image artifact details**:  
	[repo-info repo's `repos/gradle/` directory](https://github.com/docker-library/repo-info/blob/master/repos/gradle) ([history](https://github.com/docker-library/repo-info/commits/master/repos/gradle))  
	(image metadata, transfer size, etc)

-	**Image updates**:  
	[official-images repo's `library/gradle` label](https://github.com/docker-library/official-images/issues?q=label%3Alibrary%2Fgradle)  
	[official-images repo's `library/gradle` file](https://github.com/docker-library/official-images/blob/master/library/gradle) ([history](https://github.com/docker-library/official-images/commits/master/library/gradle))

-	**Source of this description**:  
	[docs repo's `gradle/` directory](https://github.com/docker-library/docs/tree/master/gradle) ([history](https://github.com/docker-library/docs/commits/master/gradle))

# What is Gradle?

[Gradle](https://gradle.org/) is a build tool with a focus on build automation and support for multi-language development. If you are building, testing, publishing, and deploying software on any platform, Gradle offers a flexible model that can support the entire development lifecycle from compiling and packaging code to publishing web sites. Gradle has been designed to support build automation across multiple languages and platforms including Java, Scala, Android, C/C++, and Groovy, and is closely integrated with development tools and continuous integration servers including Eclipse, IntelliJ, and Jenkins.

![logo](https://raw.githubusercontent.com/docker-library/docs/c3d3ca6beed000f9ba6eabc98f3399158f520256/gradle/logo.png)

# How to use this image

## Building a Gradle project

Run this from the directory of the Gradle project you want to build.

`docker run --rm -u gradle -v "$PWD":/home/gradle/project -w /home/gradle/project ppc64le/gradle gradle <gradle-task>`

Note the above command runs using uid/gid 1000 (user *gradle*) to avoid running as root.

If you are mounting a volume and the uid/gid running Docker is not *1000*, you should run as user *root* (`-u root`). *root* is also the default, so you can also simply not specify a user.

# License

View [license information](https://gradle.org/license/) for the software contained in this image.

As with all Docker images, these likely also contain other software which may be under other licenses (such as Bash, etc from the base distribution, along with any direct or indirect dependencies of the primary software being contained).

Some additional license information which was able to be auto-detected might be found in [the `repo-info` repository's `gradle/` directory](https://github.com/docker-library/repo-info/tree/master/repos/gradle).

As for any pre-built image usage, it is the image user's responsibility to ensure that any use of this image complies with any relevant licenses for all software contained within.
