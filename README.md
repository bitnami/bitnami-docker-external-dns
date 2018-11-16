[![CircleCI](https://circleci.com/gh/bitnami/bitnami-docker-external-dns/tree/master.svg?style=shield)](https://circleci.com/gh/bitnami/bitnami-docker-external-dns/tree/master)

# What is ExternalDNS?

ExternalDNS is a Kubernetes addon that configures public DNS servers with information about exposed Kubernetes services to make them discoverable.

[https://github.com/kubernetes-incubator/external-dns](https://github.com/kubernetes-incubator/external-dns)

# TL;DR;

Deploy ExternalDNS on your [GKE cluster](https://github.com/kubernetes-incubator/external-dns/blob/master/docs/tutorials/nginx-ingress.md).

```bash
$ docker run --name external-dns bitnami/external-dns:latest
```

# Why use Bitnami Images?

* Bitnami closely tracks upstream source changes and promptly publishes new versions of this image using our automated systems.
* With Bitnami images the latest bug fixes and features are available as soon as possible.
* Bitnami containers, virtual machines and cloud images use the same components and configuration approach - making it easy to switch between formats based on your project needs.
* Bitnami images are built on CircleCI and automatically pushed to the Docker Hub.
* All our images are based on [minideb](https://github.com/bitnami/minideb) a minimalist Debian based container image which gives you a small base container image and the familiarity of a leading linux distribution.
* Bitnami container images are released daily with the latest distribution packages available.

[![Anchore Image Overview](https://anchore.io/service/badges/image/1de1ffa2abfac6b951646713f54e4a1a592a6acbda03c345906d734dcb0127e0)](https://anchore.io/image/dockerhub/bitnami%2Fexternal-dns%3Alatest#security)

> The image overview badge contains a security report with all open CVEs. Click on 'Show only CVEs with fixes' to get the list of actionable security issues.

# How to deploy ExternalDNS in Kubernetes?

Deploying Bitnami applications as Helm Charts is the easiest way to get started with our applications on Kubernetes. Read more about the installation in the [Bitnami ExternalDNS Chart GitHub repository](https://github.com/bitnami/charts/tree/master/bitnami/external-dns).

Bitnami containers can be used with [Kubeapps](https://kubeapps.com/) for deployment and management of Helm Charts in clusters.

# Why use a non-root container?

Non-root container images add an extra layer of security and are generally recommended for production environments. However, because they run as a non-root user, privileged tasks are typically off-limits. Learn more about non-root containers [in our docs](https://docs.bitnami.com/containers/how-to/work-with-non-root-containers/).

# Supported tags and respective `Dockerfile` links

> NOTE: Debian 8 images have been deprecated in favor of Debian 9 images. Bitnami will not longer publish new Docker images based on Debian 8.

Learn more about the Bitnami tagging policy and the difference between rolling tags and immutable tags [in our documentation page](https://docs.bitnami.com/containers/how-to/understand-rolling-tags-containers/).


* [`0-ol-7`, `0.5.8-ol-7-r30` (0/ol-7/Dockerfile)](https://github.com/bitnami/bitnami-docker-external-dns/blob/0.5.8-ol-7-r30/0/ol-7/Dockerfile)
* [`0-debian-9`, `0.5.8-debian-9-r13`, `0`, `0.5.8`, `0.5.8-r13`, `latest` (0/debian-9/Dockerfile)](https://github.com/bitnami/bitnami-docker-external-dns/blob/0.5.8-debian-9-r13/0/debian-9/Dockerfile)

Subscribe to project updates by watching the [bitnami/external-dns GitHub repo](https://github.com/bitnami/bitnami-docker-external-dns).

# Configuration

For further documentation, please check [here](https://github.com/kubernetes-incubator/external-dns).

# Contributing

We'd love for you to contribute to this container. You can request new features by creating an [issue](https://github.com/bitnami/bitnami-docker-external-dns/issues), or submit a [pull request](https://github.com/bitnami/bitnami-docker-external-dns/pulls) with your contribution.

# Issues

<!-- If you encountered a problem running this container, you can file an [issue](https://github.com/bitnami/bitnami-docker-external-dns/issues). For us to provide better support, be sure to include the following information in your issue: -->

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
