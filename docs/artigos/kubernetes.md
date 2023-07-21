# Suco de Kubernetes 
Se você trabalha ou quer trabalhar com TI, inevitavelmente vai acabar se deparando com cloud, 

## Por que é bom aprender Kubernetes?

* Kubernetes é o sistema operacional da nuvem, vc consegue tirar sua aplicação de uma nuvem e levar pra outra. 
* Se uma empresa não usa Kubernetes, está em vias dê, mercado muito grande de Kubernetes
* Desenvolvedor precisa saber escrever os arquivos .yaml que serão os entregáveis (deployments, etc) ao invés de um binário, precisa entender kubernetes pois a aplicação vai rodar lá.
* DevOps, SRE, Platform Engineer vai utilizar Kubernetes com certeza, pois é lá onde a grande maioria das aplicações irão rodar
* O Kubernetes e containerização estão numa fase mais madura no mercado, hoje existe muita coisa em volta disso (Argo CD, GitOps, Service Mesh)
* K8s praticamente consegue gerenciar toda a sua infraestrutura
* Mercado de Kubernetes muito aquecido, com abertura até para especialistas em Kubernetes
* Ele configura toda a comunicação dos serviços, uma complexidade que existia antes e agora é gerenciada pelo k8s

## Historia básica do Kubernetes
* Começou no Google como Borg, e foi doado para a CNCF
* Faz parte da CNCF, software aberto da comunidade

## Conceitos básicos

* O que é um container?
  * Uma forma de fazer Isolamento de recursos
  * Não é tipo uma VM
* O que é um orquestrador de containers?
  * Replicação de containers para alta disponibilidade, evita que o serviço caia
  * Vai organizar os containers por serviços, e vai espalhar os containers no nós
  * k8s, nomad, swarm

* Nodes -> Instância
  * Control plane
    * Gerenciam a saúde do cluster
    * API server
  * Workers
* Kubernetes gerenciados
  * GKE
  * EKS
  * AKS
* Cluster
* Pods
  * Menor unidade do Kubernetes
* Services
* Deployments
* ReplicaSets

## Subindo um cluster 