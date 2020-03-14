# kubeadm-cli

## To initialize k8s master node
``` kubeadm init [flags] ```
## To join worker node with master
``` kubeadm join --token [] --discovery-token-ca-cert-hash []```
## To generate token
``` kubeadm token [CREATE|DELETE|LIST|GENERATE] [flags] ```
##To check version
``` kubeadm version [flags] ```
##To upgrade/downgrade
``` kubeadm upgrade plan [version] [flags]```

[Read more](https://kubernetes.io/docs/reference/setup-tools/kubeadm/kubeadm/)

There's six steps to install and run a k8s cluster,

1. Disable swap and SELinux from all nodes
2. Install kubeadm, kubelet kubectl, docker on all nodes
3. Start and enable docker and kubelet services on all nodes
4. Initialize the master node
5. Configure pod networks
6. Join worker nodes with master

```Note```: It is recommended to use at least 2 core for each node, but practical experience states that there should be at least 3 core and 3 GB memory for each node.


