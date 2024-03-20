# Configuração do Kubernetes para APIs de Autenticação e Notícias

Este repositório contém a configuração do Kubernetes para implantar duas APIs, uma para autenticação e outra para notícias. Ambas as APIs se comunicam usando RabbitMQ.

## Pré-requisitos

- [Minikube](https://minikube.sigs.k8s.io/docs/)
- [kubectl](https://kubernetes.io/docs/tasks/tools/)

## Configuração do Minikube

Certifique-se de ter o Minikube instalado e em execução antes de prosseguir.

```bash
minikube start
```
## Configuração do Arquivos.yaml
Aplique todos os arquivos yaml utilizando o comando 
```bash
kubectl apply -f nomearquivo.yaml
```
Para uma melhor visualização instale o k9s, não esqueça de ativar as métricas
```bash
minikube addons enable metrics-server
```
