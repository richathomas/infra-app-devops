## Install EKS
Please follow the prerequisites doc before this.

### Install a EKS cluster with EKSCTL
```bash
eksctl create cluster --name demo-cluster --region us-east-1 
```

### Delete the cluster
```bash
eksctl delete cluster --name demo-cluster --region us-east-1
```
