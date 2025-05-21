# 🌐 Projeto: Site Estático com Docker e Nginx

Este repositório contém um projeto de exemplo que mostra como hospedar uma página HTML com CSS utilizando um container Docker com o servidor Nginx.
---
## 🎯 Objetivo do Projeto

- Criar um ambiente de hospedagem local com Docker
- Servir uma página estática (HTML + CSS + imagem) via Nginx
- Construir uma imagem personalizada com Dockerfile
- Versionar o projeto com Git e publicar no GitHub

---

## 📁 Estrutura do Projeto

```
meu-site-nginx/
├── Dockerfile          # Define a imagem customizada do Nginx
├── index.html          # Página HTML com conteúdo sobre Docker
├── styles.css          # Estilização básica da página
├── imagem.png          # Imagem exibida na página
├── README.md           # Instruções e documentação do projeto
```

---

## ⚙️ Comandos Utilizados

### 🔧 Construir a imagem:

```bash
docker build -t meu-site-nginx .
```

### ▶️ Executar o container:

```bash
docker run -d -p 8080:80 meu-site-nginx
```

### 🛑 Parar o container (opcional):

```bash
docker ps                      # Localizar o CONTAINER ID
docker stop <CONTAINER_ID>
```

---

## 🚀 Como Executar o Projeto

1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/meu-site-nginx.git
cd meu-site-nginx
```

2. Construa a imagem Docker:

```bash
docker build -t meu-site-nginx .
```

3. Execute o container:

```bash
docker run -d -p 8080:80 meu-site-nginx
```
4. Acesse no navegador:

```
http://localhost:8080
```
---

## 📝 Sobre a Página

A página HTML apresenta uma introdução aos recursos do Docker:

- Containers isolados
- Facilidade de deploy
- Integração com CI/CD

Inclui CSS básico e uma imagem ilustrativa.

---

## 📌 Autor

Desenvolvido por [Seu Nome]

Repositório público:  
[https://github.com/seu-usuario/meu-site-nginx](https://github.com/seu-usuario/meu-site-nginx)
