```
helm template argocd argo/argo-cd --namespace argocd > argo.yaml
kustomize build . > install.yaml
```
