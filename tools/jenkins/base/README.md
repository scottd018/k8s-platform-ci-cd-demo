# jenkins

This is the prerequisite for setting up Jenkins for the CI demo for K8S platform components.

```bash
kubectl apply -f _namespace.yaml -f jenkins-storage-class.yaml -f jenkins-rbac.yaml
helm install jenkins jenkinsci/jenkins -n jenkins -f tools/jenkins/base/jenkins.yaml
```
