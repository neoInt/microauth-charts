# Microauth charts

This repository contains the charts for Microauth framework. The main chart is the microauth chart. It contains several tools to setup a minimum Microservice authentication and authorization.

## TL;DR

```bash
$ helm repo add microauth https://charts.microauth.io/microauth
$ helm search repo microauth
$ helm install my-release microauth/<chart>
```

## Before you begin

### Prerequisites

* Kubernetes 1.19+
* Helm 3.2.0+

### Install Helm

Microauth helm charts requires tooling Helm.

To install Helm, refer to the Helm install guide and ensure that the helm binary is in the PATH of your shell.

### Add Repo

The following command allows you to download and install all the charts from this repository:

```bash
$ helm repo add microauth https://charts.microauth.io/microauth
```

### Using Helm

Once you have installed the Helm client, you can deploy a Microauth Helm Chart into a Kubernetes cluster.

Useful Helm Client Commands:

* View available charts: helm search repo
* Install a chart: helm install my-release microauth/<package-name>
* Upgrade your application: helm upgrade
