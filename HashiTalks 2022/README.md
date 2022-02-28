# Exploring HashiCorp Vault and ArgoCD - the GitOps Way

## Abstract
A big topic in GitOps that isn't really discussed enough is proper GitOps secrets management and just how serious of an issue it can be in a cloud-native aspect. While normalized usage of Bitnami Sealed Secrets is typically explored, but not much is seen around using HashiCorp Vault. Especially as it pertains to using Vault with Argo Project's continuous delivery tool Argo CD. 

What exactly is HashiCorp Vault? HashiCorp Vault is a secrets management tool created primarily to control access to sensitive credentials in a low-trust environment. It can be used to manage secrets, encryption as a service, and privileged access. This talk will explore integrating HashiCorp Vault with Argo CD, any pros and cons, and (hopefully) what ended up working for Tracy and her sensitive credentials.

## Relevant Links
