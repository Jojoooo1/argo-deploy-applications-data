# Argo infra personal labs

## Data applications

Available Applications:

| Applications  | DNS | Username  | Password | Links |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| Nginx-ingress | | | | <https://kubernetes.github.io/ingress-nginx> |
| ArgoCD |  <http://rabbitmq.local.com.br> | admin  | get password at k3s start script | <https://argo-cd.readthedocs.io/en/stable>  |

## ArgoCD Folders organization

### Base

- **base/applications-data**: Contains k8s observability applications

### Overlay

Environments folders that inherit from base folder. It uses [kustomize](https://github.com/kubernetes-sigs/kustomize) to allow environment based customization.
