[![Go](https://github.com/diegoluisi/hello-gitops/actions/workflows/docker-image.yml/badge.svg)](https://github.com/diegoluisi/hello-gitops/actions/workflows/docker-image.yml)
[![CodeQL](https://github.com/diegoluisi/hello-gitops/actions/workflows/codeql.yml/badge.svg)](https://github.com/diegoluisi/hello-gitops/actions/workflows/codeql.yml)
[![App Status](https://argocd.diegoluisi.eti.br/api/badge?name=hello-gitops&revision=true)](https://argocd.diegoluisi.eti.br/applications/hello-gitops)

# **hello-gitops** 👋🏻

## **Go Template App**


### 🛠️ **Requirements**

|  Tools   | Version |
| :------: | :-----: |
| kubectl  | v1.22.3 |
| devspace | 5.18.4  |
|   k3d    | v5.3.0  |

## **Start local development**

### *Create Cluster*

```bash
k3d cluster create --config k3d.yaml
```
### *Create Namespace*
```bash
kubectl create namespace hello-python
```

### *Configure and start DevSpace*

```bash
devspace use namespace hello-python
devspace dev
```

### To Do
