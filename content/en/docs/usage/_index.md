---
title: "Usage"
linkTitle: "Usage"
weight: 3
description: >
    In depth look into the many options Terrascan supports
---

For steps to install locally, or run Terrascan from docker, see [this section](../getting-started/#installing-terrascan).

## Building Terrascan
Terrascan is a Go binary that you can build locally. This is useful if you want to be on the latest version, or when modding Terrascan.

``` Bash
$ git clone git@github.com:accurics/terrascan.git
$ cd terrascan
$ make build
$ ./bin/terrascan
```

## Using Terrascan

This section provides an overview of the different ways you can use Terrascan:

1. [Command line mode](command_line_mode/) provides list of Terrascan commands with descriptions.
2. [Server mode](server_mode/) using Terrascan as API server

See [Configuring Terrascan](config_options/) to learn more about Terrascan's configuration file.

See [In-File Instrumentation](in-file_instrumentation/) to learn how to granularly customize your scan based on particular resources and rules. For example, by skipping certain rules or resources.

## Integrations

Terrascan can be integrated into various platforms and configured to validate policies to provide run time security. Currently Terrascan supports the following integrations:

1. [Kubernetes (K8s) Admissions webhooks](../integrations/k8s/)
2. [ArgoCD](../integrations/argocd/)
3. [Atlantis](../integrations/atlantis/)
4. [Github and GitLab or CI/CD pipelines](../integrations/cicd/)