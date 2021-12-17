---
title: Google GKE
---

StorageOS is fully compatible with GKE when using the Ubunutu images. To
install StorageOS on GKE, please follow our Kubernetes [installation
instructions]( {{< ref "docs/install/kubernetes.md">}}) page.

For StorageOS to work normally it is __required to use the Ubuntu images__ for
the GKE node pools. The default container image does not fulfil the system
requirements because of the lack of the TCMU kernel modules.

For more details about the OS Distributions check the [System
Configuration]({{< ref "docs/prerequisites/systemconfiguration.md" >}}) page.


## Google Anthos

Ondat is compatible with Google Anthos. However it is required that the
Linux image distribution used fulfils the [System Configuration]({{< ref
"docs/prerequisites/systemconfiguration.md" >}}) prerequisites.

Once a Kubernetes cluster is provisioned, StorageOS can be installed following
the [instructions]( {{< ref "docs/install/kubernetes.md">}}) page.

