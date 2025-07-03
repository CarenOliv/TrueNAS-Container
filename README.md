# TrueNAS SCALE Container Demo

Este repositório contém os arquivos e passos usados para criar e configurar um contêiner Docker no TrueNAS SCALE, utilizando o servidor nginx.

## Etapas:
- Instalação da máquina virtual (VirtualBox)
- Instalação do sistema operacional Linux Mint
- Instalação do TrueNAS SCALE
- Configuração do Docker
- Criação do contêiner nginx
- Teste de funcionamento

## Comandos usados
service docker start
docker pull nginx
docker run -d -p 8080:80 --name meu_nginx nginx
docker ps

##Autoria

-Alanny Barbosa Cavalcante
-Caren Beatriz Silva Oliveira
