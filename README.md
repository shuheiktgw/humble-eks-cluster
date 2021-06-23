# Humble EKS Cluster

Create an EKS cluster with minimum running cost. This cluster is mainly for testing.

## How to use
```bash
eksctl create cluster -f cluster.yaml
eksctl delete cluster --region=ap-northeast-1 --name=humble-cluster
```
