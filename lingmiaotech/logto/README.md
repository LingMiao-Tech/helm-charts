
# LingMiaoTech Images Helm chart for Logto

## TL;DR

```console
helm install my-release oci://registry-1.lmtech.ricardo2001zg.com/lingmiaotech-charts/logto
```

## Introduction

This chart bootstraps a [Logto](https://github.com/logto-io/logto) deployment on a [Kubernetes](https://kubernetes.io) cluster using the [Helm](https://helm.sh) package manager.

## Prerequisites

- Kubernetes 1.23+
- Helm 4.0.0+

## Installing the Chart

To install the chart with the release name `my-release`:

```console
helm install my-release oci://REGISTRY_NAME/REPOSITORY_NAME/redis
```

> Note: You need to substitute the placeholders `REGISTRY_NAME` and `REPOSITORY_NAME` with a reference to your Helm chart registry and repository. For example, in the case of LingMiaoTech, you need to use `REGISTRY_NAME=registry-1.lmtech.ricardo2001zg.com` and `REPOSITORY_NAME=lingmiaotech-charts`.

The command deploys Logto on the Kubernetes cluster in the default configuration. The [Parameters](#parameters) section lists the parameters that can be configured during installation.

> **Tip**: List all releases using `helm list`

## Parameters
