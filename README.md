[![CircleCI](https://circleci.com/gh/bitnami/bitnami-docker-git/tree/master.svg?style=shield)](https://circleci.com/gh/bitnami/bitnami-docker-git/tree/master)

# What is git?

> Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency

[https://git-scm.com/](https://git-scm.com/)

# TL;DR;

```bash
$ docker run --name git bitnami/git:latest
```

# Why use Bitnami Images?

* Bitnami closely tracks upstream source changes and promptly publishes new versions of this image using our automated systems.
* With Bitnami images the latest bug fixes and features are available as soon as possible.
* Bitnami containers, virtual machines and cloud images use the same components and configuration approach - making it easy to switch between formats based on your project needs.
* Bitnami images are built on CircleCI and automatically pushed to the Docker Hub.
* All our images are based on [minideb](https://github.com/bitnami/minideb) a minimalist Debian based container image which gives you a small base container image and the familiarity of a leading linux distribution.
* Bitnami container images are released daily with the latest distribution packages available.

[![Anchore Image Overview](https://anchore.io/service/badges/image/a2ae03b31357aaad576ae5f527b2c319bfb241a9112529129baea26005ea1186)](https://anchore.io/image/dockerhub/bitnami%2Fgit%3Alatest#security)

> The image overview badge contains a security report with all open CVEs. Click on 'Show only CVEs with fixes' to get the list of actionable security issues.

# Supported tags and respective `Dockerfile` links

Learn more about the Bitnami tagging policy and the difference between rolling tags and immutable tags [in our documentation page](https://docs.bitnami.com/containers/how-to/understand-rolling-tags-containers/).


* [`2-ol-7`, `2.19.1-ol-7-r10` (2/ol-7/Dockerfile)](https://github.com/bitnami/bitnami-docker-git/blob/2.19.1-ol-7-r10/2/ol-7/Dockerfile)
* [`2-debian-9`, `2.19.1-debian-9-r9`, `2`, `2.19.1`, `2.19.1-r9`, `latest` (2/debian-9/Dockerfile)](https://github.com/bitnami/bitnami-docker-git/blob/2.19.1-debian-9-r9/2/debian-9/Dockerfile)

Subscribe to project updates by watching the [bitnami/git GitHub repo](https://github.com/bitnami/bitnami-docker-git).

# Get this image

The recommended way to get the Bitnami Git Docker Image is to pull the prebuilt image from the [Docker Hub Registry](https://hub.docker.com/r/bitnami/git).

```bash
$ docker pull bitnami/git:latest
```

To use a specific version, you can pull a versioned tag. You can view the [list of available versions](https://hub.docker.com/r/bitnami/git/tags/) in the Docker Hub Registry.

```bash
$ docker pull bitnami/git:[TAG]
```

If you wish, you can also build the image yourself.

```bash
$ docker build -t bitnami/git:latest https://github.com/bitnami/bitnami-docker-git.git
```

# Configuration

## Running commands

To run commands inside this container you can use `docker run`, for example to execute `git version` you can follow below example

```bash
$ docker run --name bitnami/git:latest --version
```

# Contributing

We'd love for you to contribute to this container. You can request new features by creating an [issue](https://github.com/bitnami/bitnami-docker-git/issues), or submit a [pull request](https://github.com/bitnami/bitnami-docker-git/pulls) with your contribution.

# Issues

If you encountered a problem running this container, you can file an [issue](https://github.com/bitnami/bitnami-docker-git/issues). For us to provide better support, be sure to include the following information in your issue:

- Host OS and version
- Docker version (`docker version`)
- Output of `docker info`
- Version of this container
- The command you used to run the container, and any relevant output you saw (masking any sensitive information)

# License

Copyright 2018 Bitnami

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
