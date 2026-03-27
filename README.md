# KubePattern Project: Pattern as Code Registry

Welcome to the official public registry for the KubePattern project. This repository contains a collection of "Pattern as Code" definitions.

## What is "Pattern as Code"?

**Pattern as Code** is a declarative approach to defining Kubernetes smells.

These patterns are Kubernetes Custom Resources written in YAML files, each describing the unique characteristics, resources, and relationships of a specific configuration bad practice.

The [KubePattern](https://kubepattern.dev) analysis tool uses these definitions to analyze your Kubernetes cluster. By comparing the cluster's state against the patterns defined in this registry, KubePattern can identify existing bad configurations and link to remediation documentation comprehensive of practical suggestions for enforcing best practices.

## Learn to write Pattern as Code
Check out the official documentation: [KubePattern Documentation](https://kubepattern.dev/docs)
