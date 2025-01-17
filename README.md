# minikube

![Actions Status](https://github.com/kubernetes/minikube/workflows/build/badge.svg)

![GoReport Widget](https://goreportcard.com/badge/github.com/kubernetes/minikube)

![GitHub All Releases](https://img.shields.io/github/downloads/kubernetes/minikube/total.svg)

![Latest Release](https://img.shields.io/github/v/release/kubernetes/minikube?include_prereleases)

![minikube logo](https://github.com/kubernetes/minikube/raw/master/images/logo/logo.png)

minikube implements a local Kubernetes cluster on macOS, Linux, and Windows. minikube's [primary goals](https://minikube.sigs.k8s.io/docs/concepts/principles/) are to be the best tool for local Kubernetes application development and to support all Kubernetes features that fit.

![screenshot](https://raw.githubusercontent.com/kubernetes/minikube/master/site/static/images/screenshot.png)

## Features

minikube runs the latest stable release of Kubernetes, with support for standard Kubernetes features like:

*   [LoadBalancer](https://minikube.sigs.k8s.io/docs/handbook/accessing/#loadbalancer-access) - using `minikube tunnel`
*   Multi-cluster - using `minikube start -p <name>`
*   NodePorts - using `minikube service`
*   [Persistent Volumes](https://minikube.sigs.k8s.io/docs/handbook/persistent_volumes/)
*   [Ingress](https://kubernetes.io/docs/tasks/access-application-cluster/ingress-minikube/)
*   [Dashboard](https://minikube.sigs.k8s.io/docs/handbook/dashboard/) - `minikube dashboard`
*   [Container runtimes](https://minikube.sigs.k8s.io/docs/handbook/config/#runtime-configuration) - `minikube start --container-runtime`
*   [Configure apiserver and kubelet options](https://minikube.sigs.k8s.io/docs/handbook/config/#modifying-kubernetes-defaults) via command-line flags
*   Supports common [CI environments](https://github.com/minikube-ci/examples)

As well as developer-friendly features:

*   [Addons](https://minikube.sigs.k8s.io/docs/handbook/deploying/#addons) - a marketplace for developers to share configurations for running services on minikube
*   [NVIDIA GPU support](https://minikube.sigs.k8s.io/docs/tutorials/nvidia_gpu/) - for machine learning
*   [Filesystem mounts](https://minikube.sigs.k8s.io/docs/handbook/mount/)

**For more information, see the official** [**minikube website**](https://minikube.sigs.k8s.io)

## Installation

See the [Getting Started Guide](https://minikube.sigs.k8s.io/docs/start/)

:mega: **Please fill out our** [**fast 5-question survey**](https://forms.gle/Gg3hG5ZySw8c1C24A) so that we can learn how & why you use minikube, and what improvements we should make. Thank you! :dancers:

KALI LINUX

curl -LO [https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64](https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64)

AS SUDO

install minikube-linux-amd64 /usr/local/bin/minikube

minikube start --force

![](https://user-images.githubusercontent.com/9384127/228987615-a33f0730-2d7e-4019-b3fd-7dc5f8657ea2.png)

![](https://user-images.githubusercontent.com/9384127/228991171-2c86e1ce-40f5-4f22-8a5d-3a35b1df61d5.png)

minikube kubectl -- get pods -A

![](https://user-images.githubusercontent.com/9384127/229299171-f4d38fc1-0909-40c6-ad55-62d2e7ebb2f4.png)

minikube dashboard

![](https://user-images.githubusercontent.com/9384127/229636484-f85ad94f-9e96-4685-9d16-3ac887023b7f.png)

Documentation

See https://minikube.sigs.k8s.io/docs/

## More Examples

See minikube in action [here](https://minikube.sigs.k8s.io/docs/handbook/controls/)

## Community

minikube is a Kubernetes [#sig-cluster-lifecycle](https://github.com/kubernetes/community/tree/master/sig-cluster-lifecycle) project.

[**#minikube on Kubernetes Slack**](https://kubernetes.slack.com) - Live chat with minikube developers!

[minikube-users mailing list](https://groups.google.com/g/minikube-users)

[minikube-dev mailing list](https://groups.google.com/g/minikube-dev)

[Contributing](https://minikube.sigs.k8s.io/docs/contrib/)

[Development Roadmap](https://minikube.sigs.k8s.io/docs/contrib/roadmap/)

Join our meetings:

*   [Bi-weekly office hours, Mondays @ 11am PST](https://tinyurl.com/minikube-oh)
*   [Triage Party](https://minikube.sigs.k8s.io/docs/contrib/triage/)
