```
helm template argo argo/argo-cd --namespace argocd --set fullnameOverride=argocd > argo.yaml
kustomize build . > install.yaml
```
