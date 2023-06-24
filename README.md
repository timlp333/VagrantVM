# VagrantVM 說明

## K8S node 說明

### master node provisioning步驟
1. 安裝docker
2. 安裝cri-dockerd
3. 安裝 kubeadm kubelet kubectl
4. init k8s cluster
5. create k8s join cmd
6. 安裝CNI calico

### work node provisioning步驟
1. 安裝docker
2. 安裝cri-dockerd
3. 安裝 kubeadm kubelet kubectl
4. join cluster
