# cicd-platform-gitops

GitOps configuration repository for cicd-platform.
Contains Kubernetes manifests managed by ArgoCD.

## Structure
- k8s/base/         - base Kubernetes manifests
- k8s/overlays/staging/    - staging environment overrides
- k8s/overlays/production/ - production environment overrides
