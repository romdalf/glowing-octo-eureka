# Supported Platforms and Orchestrators

## OS

- Linux X86_64
- Kernels satisfying our module [prerequisites](.../prerequisites/systemconfiguration.md)
- 3.x kernels have a limitation of 256 active volumes per node
- 4.x kernels have a limitation of 4096 active volumes per node
- We are distribution agnostic as long as our prerequisites are met

## Orchestrators

- Kubernetes {{< param oldest_k8s_supported >}} to {{< param newest_k8s_supported >}}
- OpenShift 4.0+

