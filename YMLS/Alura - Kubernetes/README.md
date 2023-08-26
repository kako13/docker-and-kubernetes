<p>
<img src="https://img.shields.io/badge/Tema-Container-darkred" alt="Orquestração" />
</p>
<p>
 <img src="https://img.shields.io/badge/Tecnologia-Docker-blue" alt="Kubernetes" />
</p>

## Conteúdo abordado
###
#####
##### 01. Conhecendo Kubernetes
* Para que serve o Kubernetes
* Como o Kubernetes funciona
* Quais são os principais componentes da ferramenta
* O que é, e para o que serve a API
* O que é, e para o que serve o kubectl
###
#####
##### 02. Criando o cluster
* Como inicializar um cluster no Windows
* Como inicializar um cluster no Linux
* Como fazer a instalação manual do kubectl
* Como inicializar no Google Cloud Platform
###
#####
##### 03. Criando e entendendo Pods
* O que é e para que serve um Pod
* Como utilizar o kubectl para criar um Pod
* Como criar um pod de maneira imperativa
* As desvantagens de criar recursos de maneira imperativa
* As vantagens de criar recursos de maneira declarativa
* Como funcionam as diferentes versões da API
###
#####
##### 04. Expondo Pods com o Service
* O que são e para que servem os Services
* Como garantir estabilidade de IP e DNS
* Como criar um Service
* Labels são responsáveis por definir a relação Service x Pod
* Um ClusterIP funciona apenas dentro do cluster
* Um NodePort expõe Pods para dentro e fora do cluster
* Um LoadBalancer também é um NodePort e ClusterIP
* Um LoadBalancer é capaz de automaticamente utilizar um balanceador de carga de um cloud provider
###
#####
##### 05. Aplicando Services ao projeto
* Como escolher o melhor tipo de Service para cada situação
* Como comunicar diversos pods através de um Service
* Devemos definir informações necessárias para inicializações de Pods
###
#####
##### 06. Aplicando Services ao projeto
* Como definir variávies de ambiente através do campo ```env```
* Como desacoplar configurações e definições com um ConfigMap
* Como criar e definir um ConfigMap
* Como importar variáveis de ambiente individualmente com um ConfigMap
* Como importar todo um ConfigMap com o campo envFrom
