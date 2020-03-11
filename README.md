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


