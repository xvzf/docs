<!--

********************************************************************************

WARNING:

    DO NOT EDIT "eclipse-temurin/README.md"

    IT IS AUTO-GENERATED

    (from the other files in "eclipse-temurin/" combined with a set of templates)

********************************************************************************

-->

**Note:** this is the "per-architecture" repository for the `amd64` builds of [the `eclipse-temurin` official image](https://hub.docker.com/_/eclipse-temurin) -- for more information, see ["Architectures other than amd64?" in the official images documentation](https://github.com/docker-library/official-images#architectures-other-than-amd64) and ["An image's source changed in Git, now what?" in the official images FAQ](https://github.com/docker-library/faq#an-images-source-changed-in-git-now-what).

# Quick reference

-	**Maintained by**:  
	[Adoptium](https://github.com/adoptium/containers)

-	**Where to get help**:  
	[Adoptium Slack](https://adoptium.net/slack); [Adoptium Support](https://github.com/adoptium/adoptium-support/issues/new/choose)

# Supported tags and respective `Dockerfile` links

(See ["What's the difference between 'Shared' and 'Simple' tags?" in the FAQ](https://github.com/docker-library/faq#whats-the-difference-between-shared-and-simple-tags).)

## Simple Tags

-	[`8u372-b07-jdk-alpine`, `8-jdk-alpine`, `8-alpine`](https://github.com/adoptium/containers/blob/15919f7dd6a903f0f966f484461954dcf7e28620/8/jdk/alpine/Dockerfile.releases.full)
-	[`8u372-b07-jdk-focal`, `8-jdk-focal`, `8-focal`](https://github.com/adoptium/containers/blob/920efae8fe37e2b8f2b288b5f7f9e67134ecad1d/8/jdk/ubuntu/focal/Dockerfile.releases.full)
-	[`8u372-b07-jdk-jammy`, `8-jdk-jammy`, `8-jammy`](https://github.com/adoptium/containers/blob/920efae8fe37e2b8f2b288b5f7f9e67134ecad1d/8/jdk/ubuntu/jammy/Dockerfile.releases.full)
-	[`8u372-b07-jdk-centos7`, `8-jdk-centos7`, `8-centos7`](https://github.com/adoptium/containers/blob/920efae8fe37e2b8f2b288b5f7f9e67134ecad1d/8/jdk/centos/Dockerfile.releases.full)
-	[`8u372-b07-jdk-ubi9-minimal`, `8-jdk-ubi9-minimal`, `8-ubi9-minimal`](https://github.com/adoptium/containers/blob/920efae8fe37e2b8f2b288b5f7f9e67134ecad1d/8/jdk/ubi/ubi9-minimal/Dockerfile.releases.full)
-	[`8u372-b07-jre-alpine`, `8-jre-alpine`](https://github.com/adoptium/containers/blob/15919f7dd6a903f0f966f484461954dcf7e28620/8/jre/alpine/Dockerfile.releases.full)
-	[`8u372-b07-jre-focal`, `8-jre-focal`](https://github.com/adoptium/containers/blob/920efae8fe37e2b8f2b288b5f7f9e67134ecad1d/8/jre/ubuntu/focal/Dockerfile.releases.full)
-	[`8u372-b07-jre-jammy`, `8-jre-jammy`](https://github.com/adoptium/containers/blob/920efae8fe37e2b8f2b288b5f7f9e67134ecad1d/8/jre/ubuntu/jammy/Dockerfile.releases.full)
-	[`8u372-b07-jre-centos7`, `8-jre-centos7`](https://github.com/adoptium/containers/blob/920efae8fe37e2b8f2b288b5f7f9e67134ecad1d/8/jre/centos/Dockerfile.releases.full)
-	[`8u372-b07-jre-ubi9-minimal`, `8-jre-ubi9-minimal`](https://github.com/adoptium/containers/blob/920efae8fe37e2b8f2b288b5f7f9e67134ecad1d/8/jre/ubi/ubi9-minimal/Dockerfile.releases.full)
-	[`11.0.19_7-jdk-alpine`, `11-jdk-alpine`, `11-alpine`](https://github.com/adoptium/containers/blob/15919f7dd6a903f0f966f484461954dcf7e28620/11/jdk/alpine/Dockerfile.releases.full)
-	[`11.0.19_7-jdk-focal`, `11-jdk-focal`, `11-focal`](https://github.com/adoptium/containers/blob/920efae8fe37e2b8f2b288b5f7f9e67134ecad1d/11/jdk/ubuntu/focal/Dockerfile.releases.full)
-	[`11.0.19_7-jdk-jammy`, `11-jdk-jammy`, `11-jammy`](https://github.com/adoptium/containers/blob/920efae8fe37e2b8f2b288b5f7f9e67134ecad1d/11/jdk/ubuntu/jammy/Dockerfile.releases.full)
-	[`11.0.19_7-jdk-centos7`, `11-jdk-centos7`, `11-centos7`](https://github.com/adoptium/containers/blob/920efae8fe37e2b8f2b288b5f7f9e67134ecad1d/11/jdk/centos/Dockerfile.releases.full)
-	[`11.0.19_7-jdk-ubi9-minimal`, `11-jdk-ubi9-minimal`, `11-ubi9-minimal`](https://github.com/adoptium/containers/blob/920efae8fe37e2b8f2b288b5f7f9e67134ecad1d/11/jdk/ubi/ubi9-minimal/Dockerfile.releases.full)
-	[`11.0.19_7-jre-alpine`, `11-jre-alpine`](https://github.com/adoptium/containers/blob/15919f7dd6a903f0f966f484461954dcf7e28620/11/jre/alpine/Dockerfile.releases.full)
-	[`11.0.19_7-jre-focal`, `11-jre-focal`](https://github.com/adoptium/containers/blob/920efae8fe37e2b8f2b288b5f7f9e67134ecad1d/11/jre/ubuntu/focal/Dockerfile.releases.full)
-	[`11.0.19_7-jre-jammy`, `11-jre-jammy`](https://github.com/adoptium/containers/blob/920efae8fe37e2b8f2b288b5f7f9e67134ecad1d/11/jre/ubuntu/jammy/Dockerfile.releases.full)
-	[`11.0.19_7-jre-centos7`, `11-jre-centos7`](https://github.com/adoptium/containers/blob/920efae8fe37e2b8f2b288b5f7f9e67134ecad1d/11/jre/centos/Dockerfile.releases.full)
-	[`11.0.19_7-jre-ubi9-minimal`, `11-jre-ubi9-minimal`](https://github.com/adoptium/containers/blob/920efae8fe37e2b8f2b288b5f7f9e67134ecad1d/11/jre/ubi/ubi9-minimal/Dockerfile.releases.full)
-	[`17.0.7_7-jdk-alpine`, `17-jdk-alpine`, `17-alpine`](https://github.com/adoptium/containers/blob/15919f7dd6a903f0f966f484461954dcf7e28620/17/jdk/alpine/Dockerfile.releases.full)
-	[`17.0.7_7-jdk-focal`, `17-jdk-focal`, `17-focal`](https://github.com/adoptium/containers/blob/920efae8fe37e2b8f2b288b5f7f9e67134ecad1d/17/jdk/ubuntu/focal/Dockerfile.releases.full)
-	[`17.0.7_7-jdk-jammy`, `17-jdk-jammy`, `17-jammy`](https://github.com/adoptium/containers/blob/920efae8fe37e2b8f2b288b5f7f9e67134ecad1d/17/jdk/ubuntu/jammy/Dockerfile.releases.full)
-	[`17.0.7_7-jdk-centos7`, `17-jdk-centos7`, `17-centos7`](https://github.com/adoptium/containers/blob/920efae8fe37e2b8f2b288b5f7f9e67134ecad1d/17/jdk/centos/Dockerfile.releases.full)
-	[`17.0.7_7-jdk-ubi9-minimal`, `17-jdk-ubi9-minimal`, `17-ubi9-minimal`](https://github.com/adoptium/containers/blob/920efae8fe37e2b8f2b288b5f7f9e67134ecad1d/17/jdk/ubi/ubi9-minimal/Dockerfile.releases.full)
-	[`17.0.7_7-jre-alpine`, `17-jre-alpine`](https://github.com/adoptium/containers/blob/15919f7dd6a903f0f966f484461954dcf7e28620/17/jre/alpine/Dockerfile.releases.full)
-	[`17.0.7_7-jre-focal`, `17-jre-focal`](https://github.com/adoptium/containers/blob/920efae8fe37e2b8f2b288b5f7f9e67134ecad1d/17/jre/ubuntu/focal/Dockerfile.releases.full)
-	[`17.0.7_7-jre-jammy`, `17-jre-jammy`](https://github.com/adoptium/containers/blob/920efae8fe37e2b8f2b288b5f7f9e67134ecad1d/17/jre/ubuntu/jammy/Dockerfile.releases.full)
-	[`17.0.7_7-jre-centos7`, `17-jre-centos7`](https://github.com/adoptium/containers/blob/920efae8fe37e2b8f2b288b5f7f9e67134ecad1d/17/jre/centos/Dockerfile.releases.full)
-	[`17.0.7_7-jre-ubi9-minimal`, `17-jre-ubi9-minimal`](https://github.com/adoptium/containers/blob/920efae8fe37e2b8f2b288b5f7f9e67134ecad1d/17/jre/ubi/ubi9-minimal/Dockerfile.releases.full)
-	[`20.0.1_9-jdk-alpine`, `20-jdk-alpine`, `20-alpine`](https://github.com/adoptium/containers/blob/15919f7dd6a903f0f966f484461954dcf7e28620/20/jdk/alpine/Dockerfile.releases.full)
-	[`20.0.1_9-jdk-jammy`, `20-jdk-jammy`, `20-jammy`](https://github.com/adoptium/containers/blob/920efae8fe37e2b8f2b288b5f7f9e67134ecad1d/20/jdk/ubuntu/jammy/Dockerfile.releases.full)
-	[`20.0.1_9-jdk-ubi9-minimal`, `20-jdk-ubi9-minimal`, `20-ubi9-minimal`](https://github.com/adoptium/containers/blob/920efae8fe37e2b8f2b288b5f7f9e67134ecad1d/20/jdk/ubi/ubi9-minimal/Dockerfile.releases.full)
-	[`20.0.1_9-jre-alpine`, `20-jre-alpine`](https://github.com/adoptium/containers/blob/15919f7dd6a903f0f966f484461954dcf7e28620/20/jre/alpine/Dockerfile.releases.full)
-	[`20.0.1_9-jre-jammy`, `20-jre-jammy`](https://github.com/adoptium/containers/blob/920efae8fe37e2b8f2b288b5f7f9e67134ecad1d/20/jre/ubuntu/jammy/Dockerfile.releases.full)
-	[`20.0.1_9-jre-ubi9-minimal`, `20-jre-ubi9-minimal`](https://github.com/adoptium/containers/blob/920efae8fe37e2b8f2b288b5f7f9e67134ecad1d/20/jre/ubi/ubi9-minimal/Dockerfile.releases.full)

## Shared Tags

-	`8u372-b07-jdk`, `8-jdk`, `8`:
	-	[`8u372-b07-jdk-jammy`](https://github.com/adoptium/containers/blob/920efae8fe37e2b8f2b288b5f7f9e67134ecad1d/8/jdk/ubuntu/jammy/Dockerfile.releases.full)
-	`8u372-b07-jre`, `8-jre`:
	-	[`8u372-b07-jre-jammy`](https://github.com/adoptium/containers/blob/920efae8fe37e2b8f2b288b5f7f9e67134ecad1d/8/jre/ubuntu/jammy/Dockerfile.releases.full)
-	`11.0.19_7-jdk`, `11-jdk`, `11`:
	-	[`11.0.19_7-jdk-jammy`](https://github.com/adoptium/containers/blob/920efae8fe37e2b8f2b288b5f7f9e67134ecad1d/11/jdk/ubuntu/jammy/Dockerfile.releases.full)
-	`11.0.19_7-jre`, `11-jre`:
	-	[`11.0.19_7-jre-jammy`](https://github.com/adoptium/containers/blob/920efae8fe37e2b8f2b288b5f7f9e67134ecad1d/11/jre/ubuntu/jammy/Dockerfile.releases.full)
-	`17.0.7_7-jdk`, `17-jdk`, `17`:
	-	[`17.0.7_7-jdk-jammy`](https://github.com/adoptium/containers/blob/920efae8fe37e2b8f2b288b5f7f9e67134ecad1d/17/jdk/ubuntu/jammy/Dockerfile.releases.full)
-	`17.0.7_7-jre`, `17-jre`:
	-	[`17.0.7_7-jre-jammy`](https://github.com/adoptium/containers/blob/920efae8fe37e2b8f2b288b5f7f9e67134ecad1d/17/jre/ubuntu/jammy/Dockerfile.releases.full)
-	`20.0.1_9-jdk`, `20-jdk`, `20`, `latest`:
	-	[`20.0.1_9-jdk-jammy`](https://github.com/adoptium/containers/blob/920efae8fe37e2b8f2b288b5f7f9e67134ecad1d/20/jdk/ubuntu/jammy/Dockerfile.releases.full)
-	`20.0.1_9-jre`, `20-jre`:
	-	[`20.0.1_9-jre-jammy`](https://github.com/adoptium/containers/blob/920efae8fe37e2b8f2b288b5f7f9e67134ecad1d/20/jre/ubuntu/jammy/Dockerfile.releases.full)

[![amd64/eclipse-temurin build status badge](https://img.shields.io/jenkins/s/https/doi-janky.infosiftr.net/job/multiarch/job/amd64/job/eclipse-temurin.svg?label=amd64/eclipse-temurin%20%20build%20job)](https://doi-janky.infosiftr.net/job/multiarch/job/amd64/job/eclipse-temurin/)

# Quick reference (cont.)

-	**Where to file issues**:  
	[GitHub](https://github.com/adoptium/containers/issues); The [adoptium support](https://adoptium.net/support) page has more information on quality, roadmap and support levels for Eclipse Temurin builds. Vulnerabilities not related to Eclipse Temurin itself should be be raised to their respective projects (e.g Ubuntu vulnerabilities need to be raised directly to the Ubuntu project).

-	**Supported architectures**: ([more info](https://github.com/docker-library/official-images#architectures-other-than-amd64))  
	[`amd64`](https://hub.docker.com/r/amd64/eclipse-temurin/), [`arm32v7`](https://hub.docker.com/r/arm32v7/eclipse-temurin/), [`arm64v8`](https://hub.docker.com/r/arm64v8/eclipse-temurin/), [`ppc64le`](https://hub.docker.com/r/ppc64le/eclipse-temurin/), [`s390x`](https://hub.docker.com/r/s390x/eclipse-temurin/), [`windows-amd64`](https://hub.docker.com/r/winamd64/eclipse-temurin/)

-	**Published image artifact details**:  
	[repo-info repo's `repos/eclipse-temurin/` directory](https://github.com/docker-library/repo-info/blob/master/repos/eclipse-temurin) ([history](https://github.com/docker-library/repo-info/commits/master/repos/eclipse-temurin))  
	(image metadata, transfer size, etc)

-	**Image updates**:  
	[official-images repo's `library/eclipse-temurin` label](https://github.com/docker-library/official-images/issues?q=label%3Alibrary%2Feclipse-temurin)  
	[official-images repo's `library/eclipse-temurin` file](https://github.com/docker-library/official-images/blob/master/library/eclipse-temurin) ([history](https://github.com/docker-library/official-images/commits/master/library/eclipse-temurin))

-	**Source of this description**:  
	[docs repo's `eclipse-temurin/` directory](https://github.com/docker-library/docs/tree/master/eclipse-temurin) ([history](https://github.com/docker-library/docs/commits/master/eclipse-temurin))

## Overview

The images in this repository contain OpenJDK binaries that are built by Eclipse Temurin.

# What is Eclipse Temurin ?

The Eclipse Temurin project provides code and processes that support the building of runtime binaries and associated technologies that are high performance, enterprise-caliber, cross-platform, open-source licensed, and Java SE TCK-tested for general use across the Java ecosystem.

![logo](https://raw.githubusercontent.com/docker-library/docs/cb27e17c8b50fddc58f1933d266a1a7686fea8ed/eclipse-temurin/logo.png)

# Do you provide JRE (Java Runtime Environment) Images?

JRE images are available for all versions of Eclipse Temurin but it is recommended that you produce a custom JRE-like runtime using `jlink` (see usage below).

# How to use this Image

To run a pre-built jar file with the latest OpenJDK 11, use the following Dockerfile:

```dockerfile
FROM amd64/eclipse-temurin:11
RUN mkdir /opt/app
COPY japp.jar /opt/app
CMD ["java", "-jar", "/opt/app/japp.jar"]
```

You can build and run the Docker Image as shown in the following example:

```console
docker build -t japp .
docker run -it --rm japp
```

### Using a different base Image

If you are using a distribution that we don't provide an image for you can copy the JDK using a similar Dockerfile to the one below:

```dockerfile
# Example
FROM <base image>
ENV JAVA_HOME=/opt/java/openjdk
COPY --from=amd64/eclipse-temurin:11 $JAVA_HOME $JAVA_HOME
ENV PATH="${JAVA_HOME}/bin:${PATH}"
```

### Creating a JRE using jlink

On OpenJDK 11+, a JRE can be generated using `jlink`, see the following Dockerfile:

```dockerfile
# Example of custom Java runtime using jlink in a multi-stage container build
FROM amd64/eclipse-temurin:11 as jre-build

# Create a custom Java runtime
RUN $JAVA_HOME/bin/jlink \
         --add-modules java.base \
         --strip-debug \
         --no-man-pages \
         --no-header-files \
         --compress=2 \
         --output /javaruntime

# Define your base image
FROM debian:buster-slim
ENV JAVA_HOME=/opt/java/openjdk
ENV PATH "${JAVA_HOME}/bin:${PATH}"
COPY --from=jre-build /javaruntime $JAVA_HOME

# Continue with your application deployment
RUN mkdir /opt/app
COPY japp.jar /opt/app
CMD ["java", "-jar", "/opt/app/japp.jar"]
```

If you want to place the jar file on the host file system instead of inside the container, you can mount the host path onto the container by using the following commands:

```dockerfile
FROM amd64/eclipse-temurin:11.0.12_7-jdk
CMD ["java", "-jar", "/opt/app/japp.jar"]
```

```console
docker build -t japp .
docker run -it -v /path/on/host/system/jars:/opt/app japp
```

# Image Variants

The `amd64/eclipse-temurin` images come in many flavors, each designed for a specific use case.

## `amd64/eclipse-temurin:<version>`

This is the defacto image. If you are unsure about what your needs are, you probably want to use this one. It is designed to be used both as a throw away container (mount your source code and start the container to start your app), as well as the base to build other images off of.

Some of these tags may have names like focal or jammy in them. These are the suite code names for releases of [Ubuntu](https://wiki.ubuntu.com/Releases) and indicate which release the image is based on. If your image needs to install any additional packages beyond what comes with the image, you'll likely want to specify one of these explicitly to minimize breakage when there are new releases of Ubuntu.

## `amd64/eclipse-temurin:<version>-alpine`

This image is based on the popular [Alpine Linux project](https://alpinelinux.org), available in [the `alpine` official image](https://hub.docker.com/_/alpine). Alpine Linux is much smaller than most distribution base images (~5MB), and thus leads to much slimmer images in general.

This variant is useful when final image size being as small as possible is your primary concern. The main caveat to note is that it does use [musl libc](https://musl.libc.org) instead of [glibc and friends](https://www.etalabs.net/compare_libcs.html), so software will often run into issues depending on the depth of their libc requirements/assumptions. See [this Hacker News comment thread](https://news.ycombinator.com/item?id=10782897) for more discussion of the issues that might arise and some pro/con comparisons of using Alpine-based images.

To minimize image size, it's uncommon for additional related tools (such as `git` or `bash`) to be included in Alpine-based images. Using this image as a base, add the things you need in your own Dockerfile (see the [`alpine` image description](https://hub.docker.com/_/alpine/) for examples of how to install packages if you are unfamiliar).

# License

The Dockerfiles and associated scripts are licensed under the [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.html).

Licenses for the products installed within the images:

-	OpenJDK: The project license is GNU GPL v2 with Classpath Exception.

As with all Docker images, these likely also contain other software which may be under other licenses (such as Bash, etc from the base distribution, along with any direct or indirect dependencies of the primary software being contained).

Some additional license information which was able to be auto-detected might be found in [the `repo-info` repository's `eclipse-temurin/` directory](https://github.com/docker-library/repo-info/tree/master/repos/eclipse-temurin).

As for any pre-built image usage, it is the image user's responsibility to ensure that any use of this image complies with any relevant licenses for all software contained within.
