# Argo infra personal labs

## Data applications

Available Applications:

Available Applications:

| Applications  | DNS | Username  | Password | Links |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| Clickhouse | <https://clickhouse.local.com.br/play?user=admin> | admin | password | <https://clickhouse.com/> |

## ArgoCD Folders organization

### Base

- **base/applications-data**: Contains k8s observability applications

### Overlay

Environments folders that inherit from base folder. It uses [kustomize](https://github.com/kubernetes-sigs/kustomize) to allow environment based customization.
