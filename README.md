## flux + k3s (3 controlplane + etcd for HA) + mix of arch/ubuntu base distro

- setup NFS on single host (future options when I have more storage nodes: seaweedfs, longhorn, moosefs)
- install gvisor and [configure it](https://gist.github.com/Frichetten/c77ee24b12edd2ab852738fc8221a1f1) on all nodes
- run the flux bootstrap from flux docs
