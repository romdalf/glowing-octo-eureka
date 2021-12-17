# Kubernetes

> Make sure the
> [prerequisites for Ondat](../prerequisites/_index.md) are
> satisfied before proceeding.

> Any Kubernetes managed service such as EKS, AKS, GKE, DO or DockerEE
> platform can use the following Kubernetes guide to install Ondat.

> Ondat supports the five most recent Kubernetes releases, at minimum.

> Make sure to add a Ondat licence after installing.

&nbsp;

{{< tabs tabTotal="6" tabID="1" tabHREFPrefix="k8s-" tabName1="1.22" tabName2="1.21" tabName3="1.20" tabName4="1.19" tabName5="1.18">}}
{{% tab firstTab="true" tabRef="k8s-122" %}}

# Install ondat on kubernetes 1.22

{{% plugin-curl-install plugin_version="v1.0.0" %}}
{{% ondat-plugin-install %}}
{{% verify-ondat-install %}}
{{% license-cluster-plugin-install %}}

{{% /tab %}}

{{% tab tabRef="k8s-121" %}}

# Install Ondat on Kubernetes 1.21

{{% plugin-curl-install plugin_version="v1.0.0" %}}
{{% ondat-plugin-install %}}
{{% verify-ondat-install %}}
{{% license-cluster-plugin-install %}}

{{% /tab %}}
{{% tab tabRef="k8s-120" %}}
# Install Ondat on Kubernetes 1.20

{{% plugin-curl-install plugin_version="v1.0.0" %}}
{{% ondat-plugin-install %}}
{{% verify-ondat-install %}}
{{% license-cluster-plugin-install %}}

{{% /tab %}}

{{% tab tabRef="k8s-119" %}}
# Install Ondat on Kubernetes 1.19

{{% plugin-curl-install plugin_version="v1.0.0" %}}
{{% ondat-plugin-install %}}
{{% verify-ondat-install %}}
{{% license-cluster-plugin-install %}}
{{% /tab %}}

{{% tab tabRef="k8s-118" %}}
# Install Ondat on Kubernetes 1.18

{{% plugin-curl-install plugin_version="v1.0.0" %}}
{{% ondat-plugin-install %}}
{{% verify-ondat-install %}}
{{% license-cluster-plugin-install %}}

{{% /tab %}}
{{< /tabs >}}

## Airgapped clusters

Airgapped clusters can install Ondat by defining the container images uploaded
on private registries using the Custom Resource definition of the
StorageOSCluster. Check the kubectl plugin reference for the 
[declarative installation](../reference/kubectl-plugin#declarative-installation).

{{% include "content/first-volume.md" %}}
