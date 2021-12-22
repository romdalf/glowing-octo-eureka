# changelog

Remaining includes are only related to software versioning in
./docs/2.5.0/install/openshift.md
./docs/2.5.0/prerequisites/etcd.md
./docs/2.5.0/operations/uninstall.md
./docs/2.5.0/operations/licensing.md
./docs/2.5.0/self-eval.md
./docs/2.5.0/reference/bundles/support_bundle.md

See below for more details

## structure 
- ~~created an archive, previous, latest, next folders~~
- ~~copy 2.5 in latest~~
- revisit the multiple link between concept, reference and operation 
maybe into a top level topic with a breakdown in 1 or multiple pages
- reduce folder structure to 1 level deep max
- reduce the million links by a good structure!

## support.md
- 2 links to website support | dead

## self-eval.md
- email to fix
- use git artifact to latest instead of version
- change rancher local path provisioner 
- review the CLI deployment
- check default storageclass for first pvc
- split the self-eval in multiple pages (too long)
- remove benchmarking from self-eval
don't let people benchmark a sub-optimal setup!
- slack link to fix
- update git reference from storageos to ondat

## best-practices.md
- should be a break down by topics

## concepts
### cluster-topologies.md
- redo diagrams
### clusters.md
### components.md
### compression.md
### etcd.md
- review quote
### fencing.md
### namespaces.md
### nodes.md
- revise the needs of separate pages for hyper/compute mode
### policies.md
### replication.md
### rwx.md
### volumes.md

## install
### _index.md
### kubernetes.md
- fix versioning of images, cli, ...
- change tabs to a intro with supported k8s version
- create a dedicate airgap deployment guide
- remove first volume
### openshift.md
- break down in 3 pages: operatorhub, markeplace, manual
- fix versioning of images, cli, ...
- remove first volume
### rancher
- break down in 2 pages: catalog, manual
- modify this document should be only for production grade
- fix versioning of images, cli, ...
- remove first volume

## introduction
### overview.md
### platforms.md
- seems to ~= support matrix / to revise for more content
- fix versioning of images, cli, ...
### quickstart.md
- revise as this is not a quickstart - quickstart =? self-eval

## operations
### cluster-id.md
- update the GUI screenshot to reflect license changes
### delete-stos-objects.md
### disk-full.md
### encryption.md
- revisit the content to provide more context
### failure-modes.md
- include the content/failure-modes.md 
### fening.md
### firstpvc.md
- update git reference to ondat account
### health.md
### label-stos.objects.md
### licensing.md
- breakdown into 3 pages; offering, cli, gui
- remove tabs
### managing-host-storage.md
### namespaces.md
- no reference to concepts
### policies.md
### resize.md
### rwx.md
- add reference to firewall for NFS ganesha
### storageclasses.md
- update git reference to point to ondat
### tap.md
### trim.md 
- add TRIM definition
### troubleshooting.md
- collections of includes to breakdown into pages
### uninstall.md
- full revamp for 2.5
### upgrade.md
- check validity of the 2.3 requirements
- page should be part of the release notes
- use git artifact to latest instead of version
- check the need to add a "backup etcd" reco
### users.md
### Etcd
#### index.md
- update git reference to point to ondat
#### migrate-etcd-cluster.md
- update git reference to point to ondat
#### storageos-secret-info.md
- update git reference to coreos (repo archived)
## platforms
- revamp into a single page as support matrix
### _index.md
### aws-eks.md
- add mention to EKS-anywhere
- add mention to modinstall init container
### azure-aks.md
### dockeree.md
### google-gke.md
### openshift.md
### rancher.md
## prerequisites
### _index.md
- update include references
- revise a merge with support matrix
### etcd
- remove tabs
- remove reference to coreos archived repo
- update git reference from storageos to ondat
### firewals.md
### ipv6.md
### max-aio.md
### mountpropagation.md
- may be candidate to archive
### pidlimits.md
- update git reference from storageos to ondat
### systemconfiguration.md
- curation of supported distro should be in a support matrix
## reference
### bundles
- to revamp within a support section
#### _index.md
#### diagnostic-bundle.md
- rebrand gui 
#### support_bundle.md
- update git reference from storageos to ondat
### cli
#### _index.md
- update git reference from storageos to ondat
- use git artifact to latest instead of version
- update EUSA link
- update portal link
#### apply.md
#### attach.md
#### create.md
#### delete.md
#### describe.md
#### detach.md
#### get.md
#### help.md
#### update.md
#### version.md
### cluster-operator
#### _index.md
- update git reference from storageos to ondat 
- cluster-operator is not relevant anymore
#### configuration.md
#### examples.md
- review if still relevant in 2.5
- update git reference from storageos to ondat 
- update dead link to clusterdiscovery
#### install.md
- to be remove as it's just refer to installation
#### upgrade.md
- update git reference from storageos to ondat 
- use git artifact to latest instead of version
- reference to storage-operator not relevant in 2.5
### scheduler
#### _index.md
#### admission-controller.md
### api.md
### contributing.md
- update git reference from storageos to ondat 
- use git artifact to latest instead of version
- to review with the contribution pillars 
### encryption.md
- update email address (to define) 
### filesystems.md
### init-container.md
- update git reference from storageos to ondat 
- use git artifact to latest instead of version
- dbupgrade link is dead
### kubectl-plugin.md
- use git artifact to latest instead of version
- missing the plugin MAN 
### kubernetes-object-sync.md
- update git reference from storageos to ondat 
- use git artifact to latest instead of version
### labels.md
### licence.md
- to consolidate with licensing page
### open_source_attribution.md
### release_notes.md
- only release notes of current major version 2.x should be in, not previous
- include a deprecated section
- update git reference from storageos to ondat 
- use git artifact to latest instead of version
- update slack URL
- update blog post URL release of 2.0
### resource_requests_and_limits.md
### tap.md
- diagram to be updated
### telemetry.md
- add some more details to sentry from a security perspective
### tolerations.nd

## usecases
- check if there is trademark and copyright to be added
- update git reference from storageos to ondat 
- dead link operations/monitoring/prometheus-setup
### _index.md
### cassandra.md
### elasticsearch.md
### influxdb.md
### jenkins.md
### kafka.md
### kubvirt.md
### mssql.md
### mysql.md
### nginx.md
### postgres.md
### prometheus.md
### redis.md
### sidecar-backup.md
### velero-backups.md
### zookeeper.md



