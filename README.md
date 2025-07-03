# TrueNAS SCALE Container Demo

Este repositório contém os arquivos e passos usados para criar e configurar um contêiner Docker no TrueNAS SCALE, utilizando nginx como exemplo.

## Passos principais
- Instalação da máquina virtual (VirtualBox)
- Instalação do TrueNAS SCALE
- Configuração do Docker
- Criação do contêiner nginx
- Teste de funcionamento

## Comandos usados
```bash
service docker start
docker pull nginx
docker run -d -p 8080:80 --name meu_nginx nginx
docker ps

##Autoria

-Alanny Barbosa Cavalcante
-Caren Beatriz Silva Oliveira
