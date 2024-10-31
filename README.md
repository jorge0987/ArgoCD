# ArgoCD - Study Repository

Este repositório é dedicado ao estudo e implementação do ArgoCD, uma ferramenta de CD (Continuous Deployment) para Kubernetes.

## Descrição

O objetivo deste repositório é fornecer exemplos práticos de como utilizar o ArgoCD para gerenciar e automatizar o processo de deployment de aplicações em clusters Kubernetes.

## Estrutura do Repositório

- [Em construção]

## Pré-requisitos

- Kubernetes 1.18+ 
- ArgoCD 2.0+
- kubectl configurado e conectado ao cluster Kubernetes
- Acesso ao GitHub

## Instalação

### Instalando o ArgoCD

1. Instale o ArgoCD no cluster Kubernetes:
   ```sh
   kubectl create namespace argocd
   kubectl apply -n argocd -f https://raw.githubusercontent.com/argoproj/argo-cd/stable/manifests/install.yaml
   ```