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

## Azure CR

To see currently available containers for each service, visit the [Azure Container Registry](https://portal.azure.com/#@scottlogic.onmicrosoft.com/resource/subscriptions/bc77519f-1060-41f1-8b44-412dc403507b/resourceGroups/CloudTrader/providers/Microsoft.ContainerRegistry/registries/cloudTrader/overview).
