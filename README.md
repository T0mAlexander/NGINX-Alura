# Guia prático NGINX

## Descrição

Este repositório contém um tutorial abrangente sobre o uso básico do NGINX, onde todo o conhecimento e conteúdo apresentado foram aprendidos no curso da Alura que inclui os principais recursos do NGINX como configuração básica, proxy reverso, balanceamento de carga, servidor de recuperação, cache e HTTPS.

## Pré-requisitos

* **[Docker](https://www.docker.com/products/docker-desktop/)** instalado na máquina na versão mínima de 24.0.0
* Editores de texto integrados ao terminal Linux/Unix (e.g **Vim**, **Nano**, **Emacs**)
* [**Extensão do NGINX**](https://hub.docker.com/extensions/nginx/docker-extension) no instalada no Docker Desktop

## Instruções de uso

1. Clone o repositório

```bash
git clone https://github.com/T0mAlexander/NGINX-Alura
```

2. Acesse a pasta do repositório

```bash
cd NGINX-Alura
```

3. Monte e inicialize o container

```bash
docker-compose up -d
```

> **NOTA**: o container será hospedado na porta 80 que é a padrão para o [localhost](http://localhost)

4. Mova os arquivos da pasta `server` para o container do Docker

* Acesse o container no Docker Desktop
![NGINX Container Screenshot](https://raw.githubusercontent.com/T0mAlexander/NGINX-Alura/screenshots/container.png)

* Clique na aba "Files" para acessar os arquivos internos do container
![NGINX Container Files Screenshot](https://raw.githubusercontent.com/T0mAlexander/NGINX-Alura/screenshots/container%20files.png)

* Faça a importação da pasta [server](https://github.com/T0mAlexander/NGINX-Alura/tree/main/server) para os arquivos internos do container
![NGINX Container Folder Upload Screenshot](https://raw.githubusercontent.com/T0mAlexander/NGINX-Alura/screenshots/folder%20upload.png)

### Autor: Tom Alexander
