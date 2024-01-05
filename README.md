# crictl-export-command

if use can't find the crictl with the installation of k3s, rke/rke2, please use the following command to export the binary:
```
export CRI_CONFIG_FILE=/var/lib/rancher/rke2/agent/etc/crictl.yaml
export CONTAINERD_ADDRESS=unix:///run/k3s/containerd/containerd.sock
export PATH=$PATH:/var/lib/rancher/rke2/bin
```
