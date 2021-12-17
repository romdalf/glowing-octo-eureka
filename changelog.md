# changelog

## structure 
- ~~created an archive, previous, latest, next folders~~
- ~~copy 2.5 in latest~~
- revisit the multiple link between concept, reference and operation 
maybe into a top level topic with a breakdown in 1 or multiple pages
- reduce folder structure to 1 level deep max

## support.md
- 2 links to website support | dead
- link to slack with html <script>
- ~~fix code ref for support bundle with standard link~~

## self-eval.md
- ~~fix the doc link~~
- email to fix
- ~~fix prereq link~~
- ~~fix link to operator repo~~
- ~~fix link to system configuraiton~~
- CLI install to include
- change rancher local path provisioner 
- ~~fix link to etcd prereq~~
- verify ondat install to include
- review the CLI deployment
- licensing to include 
- check default storageclass for first pvc
- ~~fix link to licensing~~
- split the self-eval in multiple pages (too long)
- ~~fix link to rep doc~~
- remove benchmarking from self-eval
don't let people benchmark a sub-optimal setup!
- slack link to fix
- remove image version from reference - use tag latest 
- fix baseurl benchmark

## best-practices.md
- full rewrite
- should be a break down by topics

## concepts
### cluster-topologies.md
- ~~adapt image assets elements~~
- redo diagrams
### clusters.md
### components.md
- ~~modify link to host-storage~~
- ~~modify image links~~
- ~~modify link to operator~~
- ~~modify link to labels~~
### compression.md
- ~~modify link to labels~~
- ~~modify link to replication~~
- ~~modify link to encryption~~
### etcd.md
- review quote
- ~~modify link to etcd~~
### fencing.md
- ~~modify link to operations/fencing~~
### namespaces.md
- ~~mofiy link to policies~~
### nodes.md
- revise the needs of separate pages for hyper/compute mode
- ~~modify link to labels~~
### policies.md
- ~~modify link to namespaces~~
- ~~modify link to operations/policies~~
### replication.md
- ~~modify link to image~~
- ~~modify link to labels/storageclass~~
- ~~modify link to tap~~
- include content/failure-mode
- ~~modify link to failure-mode~~
### rwx.md
- ~~modify link to concepts/volumes~~
- ~~modify link to prerequisites/firewalls~~
- ~~modify link to operations/resize.md~~
### volumes.md
- ~~modify link to reference/filesystem~~
- ~~modify link to operations/trim~~
- ~~modify link to reference/encryption~~

## install
### kubernetes.md
- ~~modify link to prerequisites/_index.md~~
- modify the _index.md name 
- include content for installation
- change tabs to a intro with supported k8s version
- confirm there is no difference despite k8s version
- create a dedicate airgap deployment guide
- ~~modify link to reference/kubectl-plugin~~
- remove first volume
### openshift.md
- break down in 3 pages: operatorhub, markeplace, manual
- check layouts/shortcodes/openshift4-install.md
- ~~modify link to prerequisites/_index.md~~
- ~~modify link to platforms/openshift.md~~
- ~~modify link to platforms/openshift.md~~
- remove first volume
### rancher
- break down in 2 pages: catalog, manual
- ~~modify link to prerequisites/_index.md~~
- ~~modify link to prerequisites/etcd~~
- ~~modify link to prerequisites/etcd~~
- modify this document should be only for production grade
- ~~modify image links~~
- ~~modify link to reference/cluster-operator~~
- ~~modify link to install/rancher.md~~
- ~~modify link to prerequisites/etcd.md~~
- include content for manual = kubernetes installation
- ~~modify link to reference/cluster/operator

## introduction
### overview.md
- ~~modify link to concepts/volumes.md~~
### platforms.md
- seems to ~= support matrix / to revise for more content
- ~~modify link to prerequisites/systemconfiguration~~
- modify variables for k8s versions
### quickstart.md
- revise as this is not a quickstart - quickstart =? self-eval
- ~~modify link to install/kubernetes.md~~
- ~~modify link to install/openshift.md~~
- ~~modify link to install/rancher.md~~
- ~~modify link to usecases~~

## operations
### cluster-id.md
- update the GUI screenshot to reflect license changes
- ~~modify image link~~
### delete-stos-objects.md
### disk-full.md
- ~~modify link to operations/managing-host-storage~~
- ~~modify link to operations/managing-host-storage~~
### encryption.md
- ~~modify link to reference/encryption~~
- revisit the content to provide more context
### failure-modes.md
- ~~modify link to concepts/replication~~
- include the content/failure-modes.md 
### fening.md
- ~~modify link to concepts/fencing.md~~
### firstpvc.md
- update git reference to ondat account
- ~~modify link to usecases/_index.md~~
### health.md
- ~~modify link to reference/cli/_index.md~~
### label-stos.objects.md
- ~~modify link to reference/kubernetes-object-sync.md~~
- ~~modify link to operations/firstpvc.md~~
### licensing.md
- breakdown into 3 pages; offering, cli, gui
- remove tabs
- ~~modify link to self-eval.md~~
- ~~modify image links~~
- ~~modify link to reference/cli~~
### managing-host-storage.md
### namespaces.md
- no reference to concepts
### policies.md
- ~~modify link to operations/namespaces.md~~
- ~~modify link to reference/cli/create.md~~
### resize.md
- ~~modify link to concepts/volumes~~
- ~~modify image link~~
### rwx.md
- ~~modify link to operations/firstpvc.md~~
- add reference to firewall for NFS ganesha
### storageclasses.md
- update git reference to point to ondat
- ~~modify link to reference/tap.md~~
- ~~modify link to operations/failure-modes.md~~
### tap.md
### trim.md 
- add TRIM definition
### troubleshooting.md
- collections of includes to breakdown into pages
- ~~modify the link to github cli to internal doc cli~~
- ~~modify link to support.md~~
### uninstall.md
- full revamp for 2.5
### upgrade.md
- check validity of the 2.3 requirements
- page should be part of the release notes
- replace container image version by "latest" 
- check the need to add a "backup etcd" reco
### users.md
- ~~modify link to operations/namespaces.md~~
- ~~modify link to operations/policies.md~~
### Etcd
#### index.md
- ~~modify link to prerequisites/etc.md~~
- ~~modify link to prerequisites/etc.md~~
- ~~modify link to operations/etcd/_index.md~~
- update git reference to point to ondat
#### migrate-etcd-cluster.md
- ~~modify link to prerequisites/etcd.md~~
- update git reference to point to ondat
- ~~modify link to prerequisites/etcd.md~~
#### storageos-secret-info.md
- update git reference to coreos (repo archived)
## platforms
- revamp into a single page as support matrix
### _index.md
- ~~modify link to prerequisites/_index.md~~
### aws-eks.md
- add mention to EKS-anywhere
- ~~modify link to install/kubernetes.md~~
- ~~modify link to prerequisites/systemconfiguration.md~~
- add mention to modinstall init container
### azure-aks.md
- ~~modify link to install/kubernetes.md~~
### dockeree.md
- ~~modify link to install/kubernetes.md~~
- ~~modify link to prerequisites/systemconfiguration.md~~
### google-gke.md
- ~~modify link to install/kubernetes.md~~
- ~~modify link to prerequisites/systemconfiguration.md~~
- ~~modify link to prerequisites/systemconfiguration.md~~
- ~~modify link to install/kubernetes.md~~
### openshift.md
- ~~modify link to install/openshift.md~~
- ~~modify link to prerequisites/pidlimits~~
- ~~modify link to prerequisites/systemconfiguration.md~~
### rancher.md
- ~~modify link to install/rancher.md~~
- ~~modify link to prerequisites/systemconfiguration.md~~
## prerequisites
### _index.md
- update include references
- revise a merge with support matrix
- ~~modify link to prerequisites/mountpropagation.md~~
- ~~modify link to prerequisites/etcd.md~~
- ~~modify link to prerequisites/systemconfiguration.md~~
- ~~modify link to reference/cli/_index.md~~
- ~~modify link to prerequisites/ipv6.md~~
### etcd
- ~~modify link to concepts/etcd.md~~
- ~~modify link to operations/etcd/_index.md~~
- remove tabs
- remove reference to coreos archived repo
- ~~modify link to operations/etcd/_index.md~~
- ~~modify page hyperlinks~~
- ~~modify link to operations/etcd/_index.md~~
- update git reference from storageos to ondat
- ~~modify link to reference/cluster-operator/examples.md~~
### firewals.md
### ipv6.md
### max-aio.md
### mountpropagation.md
- may be candidate to archive
### pidlimits.md
- update git reference from storageos to ondat
### systemconfiguration.md
- curation of supported distro should be in a support matrix
- ~~fix bad internal hyperlinks~~
- ~~modify link to reference/cluster-operator/configuration.md~~