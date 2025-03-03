# GitOps Repository

This repository is a GitOps repository for managing the deployment in the Kubernetes cluster.

For that, we are using the following tools:
* [Flux](https://fluxcd.io/)
* [Helm](https://helm.sh/)
* [Kustomize](https://kustomize.io/)

## Flux

### Add source to Flux

```bash
flux create source helm 