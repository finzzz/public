```
helm template argo argo/argo-cd --namespace argocd > argo.yaml
kustomize build . > install.yaml
```
