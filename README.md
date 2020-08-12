# Introduction

Deployment and service `.yaml` for the cloudtrader services.

## Getting Started

### Requirements

- Azure CLI ([download](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli))
  - Logged in (using `az login`)
- Kubectl ([download](https://v1-16.docs.kubernetes.io/docs/tasks/tools/install-kubectl/))

### Usage

To configure `Kubectl` to use the cloudtrader cluster:

```bash
az aks get-credentials -g cloudtrader -n cloudtrader-cluster
```

To update the cluster with new `.yaml` descriptions:

```bash
kubectl apply -f <file / folder>
```
