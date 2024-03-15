# Fiap-checkpoint1

Checkpoint 1 de microsserviços docker

## Pré-requisitos

- Java 17+
- Docker 
- Acesso a internet
- Acesso ao Docker Hub

## Instalação

##### Clone do projeto
```
git clone https://github.com/enzonishi/fiap-checkpoint1.git
```

## Execução

#### Docker
###### Execução da imagem pelo docker hub
```
docker run -p 8080:8080 -e PROFILE=prd enzonishi/fiap-checkpoint1
docker run -p 8080:8080 -e PROFILE=dev enzonishi/fiap-checkpoint1
docker run -p 8080:8080 -e PROFILE=stg enzonishi/fiap-checkpoint1
```


## Contatos

- enzonishi - enzo.onishi@gmail.com
