# argo

This is the prerequisite for setting up argo for the CI demo for K8S platform components.

```bash
kubectl apply -f _namespace.yaml -f argo-storage-class.yaml -f argo-rbac.yaml
helm repo add argo https://argoproj.github.io/argo-helm
helm install argo argo/argo-cd -n argo -f tools/argo/base/argo.yaml
```
