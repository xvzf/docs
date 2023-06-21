<!--

********************************************************************************

WARNING:

    DO NOT EDIT "flink/README.md"

    IT IS AUTO-GENERATED

    (from the other files in "flink/" combined with a set of templates)

********************************************************************************

-->

**Note:** this is the "per-architecture" repository for the `arm64v8` builds of [the `flink` official image](https://hub.docker.com/_/flink) -- for more information, see ["Architectures other than amd64?" in the official images documentation](https://github.com/docker-library/official-images#architectures-other-than-amd64) and ["An image's source changed in Git, now what?" in the official images FAQ](https://github.com/docker-library/faq#an-images-source-changed-in-git-now-what).

# Quick reference

-	**Maintained by**:  
	[Apache Flink](https://flink.apache.org/community.html#people)

-	**Where to get help**:  
	[Official Apache Flink Mailing lists](https://flink.apache.org/community.html#mailing-lists) and [StackOverflow (tag `apache-flink`)](https://stackoverflow.com/questions/tagged/apache-flink)

# Supported tags and respective `Dockerfile` links

-	[`1.17.1-scala_2.12-java8`, `1.17-scala_2.12-java8`, `scala_2.12-java8`, `1.17.1-java8`, `1.17-java8`, `java8`](https://github.com/apache/flink-docker/blob/abc36dd88483a221c0f5495c742bd95c349e9ac2/1.17/scala_2.12-java8-ubuntu/Dockerfile)
-	[`1.17.1-scala_2.12-java11`, `1.17-scala_2.12-java11`, `scala_2.12-java11`, `1.17.1-scala_2.12`, `1.17-scala_2.12`, `scala_2.12`, `1.17.1-java11`, `1.17-java11`, `java11`, `1.17.1`, `1.17`, `latest`](https://github.com/apache/flink-docker/blob/abc36dd88483a221c0f5495c742bd95c349e9ac2/1.17/scala_2.12-java11-ubuntu/Dockerfile)
-	[`1.16.2-scala_2.12-java8`, `1.16-scala_2.12-java8`, `1.16.2-java8`, `1.16-java8`](https://github.com/apache/flink-docker/blob/45c6d230407d89aa83b0d170dd056d6868cf808e/1.16/scala_2.12-java8-ubuntu/Dockerfile)
-	[`1.16.2-scala_2.12-java11`, `1.16-scala_2.12-java11`, `1.16.2-scala_2.12`, `1.16-scala_2.12`, `1.16.2-java11`, `1.16-java11`, `1.16.2`, `1.16`](https://github.com/apache/flink-docker/blob/45c6d230407d89aa83b0d170dd056d6868cf808e/1.16/scala_2.12-java11-ubuntu/Dockerfile)
-	[`1.15.4-scala_2.12-java8`, `1.15-scala_2.12-java8`, `1.15.4-java8`, `1.15-java8`](https://github.com/apache/flink-docker/blob/c9754889a57fad2d8fff2a1975f076a0caebb28c/1.15/scala_2.12-java8-ubuntu/Dockerfile)
-	[`1.15.4-scala_2.12-java11`, `1.15-scala_2.12-java11`, `1.15.4-scala_2.12`, `1.15-scala_2.12`, `1.15.4-java11`, `1.15-java11`, `1.15.4`, `1.15`](https://github.com/apache/flink-docker/blob/c9754889a57fad2d8fff2a1975f076a0caebb28c/1.15/scala_2.12-java11-ubuntu/Dockerfile)

[![arm64v8/flink build status badge](https://img.shields.io/jenkins/s/https/doi-janky.infosiftr.net/job/multiarch/job/arm64v8/job/flink.svg?label=arm64v8/flink%20%20build%20job)](https://doi-janky.infosiftr.net/job/multiarch/job/arm64v8/job/flink/)

# Quick reference (cont.)

-	**Where to file issues**:  
	https://issues.apache.org/jira/browse/FLINK

-	**Supported architectures**: ([more info](https://github.com/docker-library/official-images#architectures-other-than-amd64))  
	[`amd64`](https://hub.docker.com/r/amd64/flink/), [`arm64v8`](https://hub.docker.com/r/arm64v8/flink/)

-	**Published image artifact details**:  
	[repo-info repo's `repos/flink/` directory](https://github.com/docker-library/repo-info/blob/master/repos/flink) ([history](https://github.com/docker-library/repo-info/commits/master/repos/flink))  
	(image metadata, transfer size, etc)

-	**Image updates**:  
	[official-images repo's `library/flink` label](https://github.com/docker-library/official-images/issues?q=label%3Alibrary%2Fflink)  
	[official-images repo's `library/flink` file](https://github.com/docker-library/official-images/blob/master/library/flink) ([history](https://github.com/docker-library/official-images/commits/master/library/flink))

-	**Source of this description**:  
	[docs repo's `flink/` directory](https://github.com/docker-library/docs/tree/master/flink) ([history](https://github.com/docker-library/docs/commits/master/flink))

# What is Apache Flink?

[Apache Flink](https://flink.apache.org/) is an open source stream processing framework with powerful stream- and batch-processing capabilities.

![logo](https://raw.githubusercontent.com/docker-library/docs/71398f44551617e3934a86b4b7a3c770ae093b59/flink/logo.png)

# How to use Apache Flink with Docker?

Please refer to the official [Apache Flink documentation](https://ci.apache.org/projects/flink/flink-docs-master/) about [how to use Apache Flink with Docker](https://ci.apache.org/projects/flink/flink-docs-master/ops/deployment/docker.html).

# License

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

	      https://www.apache.org/licenses/LICENSE-2.0

Apache Flink, Flink®, Apache®, the squirrel logo, and the Apache feather logo are either registered trademarks or trademarks of [The Apache Software Foundation](https://apache.org/).

As with all Docker images, these likely also contain other software which may be under other licenses (such as Bash, etc from the base distribution, along with any direct or indirect dependencies of the primary software being contained).

Some additional license information which was able to be auto-detected might be found in [the `repo-info` repository's `flink/` directory](https://github.com/docker-library/repo-info/tree/master/repos/flink).

As for any pre-built image usage, it is the image user's responsibility to ensure that any use of this image complies with any relevant licenses for all software contained within.
