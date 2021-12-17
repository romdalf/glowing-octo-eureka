---
title: AWS EKS
---

Ondat is fully compatible with AWS EKS. To install Ondat on EKS, 
follow our Kubernetes [installation instructions](
{{< ref "docs/install/kubernetes.md">}}) page.

An EKS deployment of Kubernetes uses AWS Linux by default with an optimized
kernel. As the requisite kernel modules are not available for Ondat to use
TCMU, FUSE will be used as a fallback. Using FUSE instead of TCMU has
performance implications.

For more details about the OS Distributions, see the [System
Configuration]({{< ref "docs/prerequisites/systemconfiguration.md" >}})
page.
