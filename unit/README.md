<!--

********************************************************************************

WARNING:

    DO NOT EDIT "unit/README.md"

    IT IS AUTO-GENERATED

    (from the other files in "unit/" combined with a set of templates)

********************************************************************************

-->

**Note:** this is the "per-architecture" repository for the `amd64` builds of [the `unit` official image](https://hub.docker.com/_/unit) -- for more information, see ["Architectures other than amd64?" in the official images documentation](https://github.com/docker-library/official-images#architectures-other-than-amd64) and ["An image's source changed in Git, now what?" in the official images FAQ](https://github.com/docker-library/faq#an-images-source-changed-in-git-now-what).

# Quick reference

-	**Maintained by**:  
	[the Unit Docker Maintainers](https://github.com/nginx/unit)

-	**Where to get help**:  
	the [GitHub issues page](https://github.com/nginx/unit/issues), the [NGINX Community Slack](https://community.nginx.org/joinslack)

# Supported tags and respective `Dockerfile` links

-	[`1.30.0-go1.20`, `go1.20`, `go1`, `go`](https://github.com/nginx/unit/blob/92ffcb89f8e145299e837438f0a0de93d73ffede/pkg/docker/Dockerfile.go1.20)
-	[`1.30.0-jsc11`, `jsc11`, `jsc`](https://github.com/nginx/unit/blob/92ffcb89f8e145299e837438f0a0de93d73ffede/pkg/docker/Dockerfile.jsc11)
-	[`1.30.0-node18`, `node18`, `node`](https://github.com/nginx/unit/blob/92ffcb89f8e145299e837438f0a0de93d73ffede/pkg/docker/Dockerfile.node18)
-	[`1.30.0-perl5.36`, `perl5.36`, `perl5`, `perl`](https://github.com/nginx/unit/blob/92ffcb89f8e145299e837438f0a0de93d73ffede/pkg/docker/Dockerfile.perl5.36)
-	[`1.30.0-php8.2`, `php8.2`, `php8`, `php`](https://github.com/nginx/unit/blob/92ffcb89f8e145299e837438f0a0de93d73ffede/pkg/docker/Dockerfile.php8.2)
-	[`1.30.0-python3.11`, `python3.11`, `python3`, `python`](https://github.com/nginx/unit/blob/92ffcb89f8e145299e837438f0a0de93d73ffede/pkg/docker/Dockerfile.python3.11)
-	[`1.30.0-ruby3.2`, `ruby3.2`, `ruby3`, `ruby`](https://github.com/nginx/unit/blob/92ffcb89f8e145299e837438f0a0de93d73ffede/pkg/docker/Dockerfile.ruby3.2)
-	[`1.30.0-minimal`, `minimal`, `latest`](https://github.com/nginx/unit/blob/92ffcb89f8e145299e837438f0a0de93d73ffede/pkg/docker/Dockerfile.minimal)

[![amd64/unit build status badge](https://img.shields.io/jenkins/s/https/doi-janky.infosiftr.net/job/multiarch/job/amd64/job/unit.svg?label=amd64/unit%20%20build%20job)](https://doi-janky.infosiftr.net/job/multiarch/job/amd64/job/unit/)

# Quick reference (cont.)

-	**Where to file issues**:  
	[https://github.com/nginx/unit/issues](https://github.com/nginx/unit/issues?q=)

-	**Supported architectures**: ([more info](https://github.com/docker-library/official-images#architectures-other-than-amd64))  
	[`amd64`](https://hub.docker.com/r/amd64/unit/), [`arm64v8`](https://hub.docker.com/r/arm64v8/unit/)

-	**Published image artifact details**:  
	[repo-info repo's `repos/unit/` directory](https://github.com/docker-library/repo-info/blob/master/repos/unit) ([history](https://github.com/docker-library/repo-info/commits/master/repos/unit))  
	(image metadata, transfer size, etc)

-	**Image updates**:  
	[official-images repo's `library/unit` label](https://github.com/docker-library/official-images/issues?q=label%3Alibrary%2Funit)  
	[official-images repo's `library/unit` file](https://github.com/docker-library/official-images/blob/master/library/unit) ([history](https://github.com/docker-library/official-images/commits/master/library/unit))

-	**Source of this description**:  
	[docs repo's `unit/` directory](https://github.com/docker-library/docs/tree/master/unit) ([history](https://github.com/docker-library/docs/commits/master/unit))

# What is Unit?

NGINX Unit is a lightweight and versatile application runtime that provides the essential components for your web application as a single open-source server: running application code, serving static assets, handling TLS and request routing.

For more information, check out [Key Features](https://unit.nginx.org/keyfeatures).

![logo](https://raw.githubusercontent.com/docker-library/docs/d6e69ebb56fe6890bd6ec587295ff1d67e2849fe/unit/logo.svg?sanitize=true)

# Available tags

Please see [Unit's website](https://unit.nginx.org/installation/#docker-images) for details.

# How to use this image

Please check the [Initial Configuration](https://unit.nginx.org/installation/#initial-configuration) section on Unit's website. Additionally, our [Docker howto](https://unit.nginx.org/howto/docker/) can be of help.

# License

View [license information](https://raw.githubusercontent.com/nginx/unit/master/LICENSE) for the software contained in this image.

As with all Docker images, these likely also contain other software which may be under other licenses (such as Bash, etc from the base distribution, along with any direct or indirect dependencies of the primary software being contained).

Some additional license information which was able to be auto-detected might be found in [the `repo-info` repository's `unit/` directory](https://github.com/docker-library/repo-info/tree/master/repos/unit).

As for any pre-built image usage, it is the image user's responsibility to ensure that any use of this image complies with any relevant licenses for all software contained within.
