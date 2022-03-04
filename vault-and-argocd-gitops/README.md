# Exploring HashiCorp Vault and ArgoCD - the GitOps Way

## Abstract
A big topic in GitOps that isn't really discussed enough is proper GitOps secrets management and just how serious of an issue it can be in a cloud-native aspect. While normalized usage of Bitnami Sealed Secrets is typically explored, but not much is seen around using HashiCorp Vault. Especially as it pertains to using Vault with Argo Project's continuous delivery tool Argo CD. 

What exactly is HashiCorp Vault? HashiCorp Vault is a secrets management tool created primarily to control access to sensitive credentials in a low-trust environment. It can be used to manage secrets, encryption as a service, and privileged access. This talk will explore integrating HashiCorp Vault with Argo CD, any pros and cons, and (hopefully) what ended up working for Tracy and her sensitive credentials.

## Relevant Links

- [What is Vault](https://www.vaultproject.io/docs/what-is-vault)
- [Argo CD](https://argoproj.github.io/cd)
- [Getting Started With GitOps and Argo CD](https://codefresh.io/argo-platform/getting-started-with-gitops-and-argo-cd/)
- [Injecting Vault Secrets Into Kubernetes Pods via a Sidecar](https://www.hashicorp.com/blog/injecting-vault-secrets-into-kubernetes-pods-via-a-sidecar)
- [Injecting Secrets into Kubernetes Pods via Vault Agent Containers](https://learn.hashicorp.com/tutorials/vault/kubernetes-sidecar?in=vault/kubernetes)
- [Kubernetes Secrets Store CSI Driver](https://github.com/kubernetes-sigs/secrets-store-csi-driver#kubernetes-secrets-store-csi-driver)
- [Bitnami Sealed Secrets](https://github.com/bitnami-labs/sealed-secrets#sealed-secrets-for-kubernetes)
- [Mozilla SOPS](https://github.com/mozilla/sops#sops-secrets-operations)
- [Argo CD Vault Plugin](https://github.com/argoproj-labs/argocd-vault-plugin#argocd-vault-plugin)
