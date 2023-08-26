<p>
<img src="https://img.shields.io/badge/Tema-Orquestração-darkred" alt="Orquestração" />
</p>
<p>
 <img src="https://img.shields.io/badge/Tecnologia-Kubernetes-blue" alt="Kubernetes" />
</p>

## Conteúdo abordado
###
#####
##### 01. Conhecendo o Docker
* Máquinas virtuais possuem camadas adicionais de virtualização em relação a um container
* Containers funcionam como processos no host
* Containers atingem isolamento através de namespaces
* Os recursos dos containers são gerenciados através de cgroups
###
#####
##### 02. Os primeiros comandos
* O Docker Hub é um grande repositório de imagens que podemos utilizar
* A base dos containers são as imagens
* Como utilizar comandos acerca do ciclo de vida dos containers, como: ```docker start```, para iniciar um container que 
esteja parado; ```docker stop```, para parar um que esteja rodando; ```docker pause```, para pausar um container e 
```docker unpause``` para iniciar um container pausado 
* Conseguimos mapear portas de um container com as flags ```-p``` e ```-P```
###
#####
##### 03. Criando e compreendendo imagens
* Imagens são imutáveis, ou seja, depois de baixadas, múltiplos containers conseguirão reutilizar a mesma imagem
* Imagens são compostas por uma ou mais camadas. Dessa forma, diferentes imagens são capazes de reutilizar uma ou mais camadas em comum entre si
* Podemos criar nossas imagens através de Dockerfiles e do comando ```docker build```
* Para subir uma imagem no Docker Hub, utilizamos o comando ```docker push```
###
#####
##### 04. Persistindo dados
* Quando containers são removidos, nossos dados são perdidos
* Podemos persistir dados em definitivo através de volumes e bind mounts
* Bind mounts dependem da estrutura de pastas do host
* Volumes são gerenciados pelo Docker
* Tmpfs armazenam dados em memória volátil
###
#####
##### 05. Comunicação através de redes
* O docker dispõe por padrão de três redes: bridge, host e none
* A rede bridge é usada para comunicar containers em um mesmo host
* Redes bridges criadas manualmente permitem comunicação via hostname
* A rede host remove o isolamento de rede entre o container e o host
* A rede none remove a interface de rede do container
* Podemos criar redes com o comando docker network create
###
#####
##### 06. Coordenando conataineres
* O Docker Compose é uma ferramenta de coordenação de containers
* Como instalar o Docker Compose no Linux
* Como iniciar containers em conjunto com o comando docker-compose up
* Como criar um arquivo de composição e definir instruções de containers, redes e serviços
