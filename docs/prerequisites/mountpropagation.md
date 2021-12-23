---
linkTitle: Mount Propagation
weight: 300
---

# Mount Propagation

> Modern versions of Kubernetes, Docker or other Container Runtimes enable
> mount propagation by default.

Ondat requires mount propagation enabled to present devices as volumes for
containers (see linux kernel documentation
[here](http://man7.org/linux/man-pages/man2/mount.2.html)).

Certain versions of docker ship with a systemd manifest with
[MountFlags](https://www.freedesktop.org/software/systemd/man/systemd.exec.html#) set
to 'slave', thus preventing Ondat from working. This can be removed or set
to 'shared' with a systemd drop in:

```bash
mkdir -p /etc/systemd/system/docker.service.d/
cat <<EOF > /etc/systemd/system/docker.service.d/mount_propagation_flags.conf
[Service]
MountFlags=shared
EOF

# systemctl daemon-reload
# systemctl restart docker.service
```

To confirm behaviour, the following command should run without error.

```
docker run -it --rm -v /mnt:/mnt:shared busybox sh -c /bin/date
```

Orchestrators such as Kubernetes or OpenShift have their own ways of exposing
this setting. Kubernetes 1.10 and OpenShift 3.10 have mount propagation enabled by
default. Previous versions require that feature gates are enabled on the
Kubernetes master's `controller-manager` and `apiserver` services and in the
`kubelet` service on each node.

Installations of orchestrators using Docker require that mount propagation is
enabled for both.

Refer to our installation pages for the orchestrators to see details on how to
check and enable mount propagation where appropriate.
