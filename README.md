<h1 align="center">
<br>
  <img src="logo.svg" alt="ecoleta-next-level-week-01">
<br>
<br>
Ecoleta
</h1>

<p align="center">Aplicação com o propósito de cadastrar e buscar pontos de coleta de materiais recicláveis na sua região.</p>

<div>
  <img src="ecoleta-front-end.gif" alt="Ecoleta front-end" width="700">
  <img src="ecoleta-mobile.gif" alt="Ecoleta mobile" width="150">
</div>

# Índice
- [Sobre o projeto](#-Sobre-o-projeto)
- [Tecnologias utilizadas](#-Tecnologias-utilizadas)
- [Rodando o projeto](#-Rodando-o-projeto)
  - [Pré-requisitos](#-Pré-requisitos)
  - [Rodando o server](#-Rodando-o-server)
  - [Rodando a versão web](#-Rodando-a-versão-web)
  - [Rodando o aplicativo mobile](#-Rodando-o-aplicativo-mobile)

## 📃 Sobre o projeto

Projeto desenvolvido durante a primeira edição da Next Level Week da Rocketseat, onde criamos uma aplicação completa para cadastro e busca de locais que fornecem pontos de coleta de materiais recicláveis em determinada região. A aplicação foi desenvolvida utilizando backend em node, frontend em react e aplicativo mobile em react native.

## 🛠 Tecnologias utilizadas

- ⚛️ **React Js** — Front-end web
- ⚛️ **React Native** — Aplicativo mobile
- 💹 **Node Js** — Back-end
- 🎲 **Knex** — SQL query builder
- 🗺 **Leaflet** — Mapa da home no front-end
- ✅ **Celebrate** — Validações no back-end
- 📷 **Multer** — Upload de imagens no back-end
- 📩 **Multer** — Area de upload de imagens no front-end
- 🗺 **React native maps** — Mapa no filtro de pontos de coléta no mobile 
- 📋 **React native picker select** — Select de estados e cidade no mobile 

## 🚀 Rodando o projeto

A aplicação é dividida em trÊs partes, web, mobile e server, a versão web e o aplicativo mobile precisam que o server esteja sendo executado para funcionar.

### Pré-requisitos

- Git
- NodeJS
- Expo

### 💻 Rodando o server

Clone o repositório

```bash

# Clona o repositório
git clone https://github.com/thiagosprestes/Ecoleta-next-level-week.git

```

Navegue até a pasta do projeto clonado e execute os comandos abaixo

```bash

# Entra na pasta do server
cd server

# Inicia o server
npm run dev

# Acesse http://localhost:3333 para acessar o servidor caso deseje

```

### 🖥 Rodando a versão web

Caso já tenha clonado o repositório basta pular a primeira etapa

```bash

# Clona o repositório
git clone https://github.com/thiagosprestes/Ecoleta-next-level-week.git

```

Navegue até a pasta do projeto clonado e execute os comandos abaixo

```bash

# Entra na pasta da versão web
cd web

# Instala as dependências
npm install

```
Após concluir a instalação das dependências execute o comando

```bash

# Inicia a versão web
npm start

# Acesse http://localhost:3000 para utilizar a aplicação

```

Com seu smartphone escaneie o QR code que aparece no terminal utilizando o Expo, app que está disponivel na App store e na Play store para iniciar o aplicativo.

### 📱 Rodando o aplicativo mobile

Caso já tenha clonado o repositório basta pular a primeira etapa

```bash

# Clona o repositório
git clone https://github.com/thiagosprestes/Ecoleta-next-level-week.git

```

Navegue até a pasta do projeto clonado e execute os comandos abaixo

```bash

# Entra na pasta do aplicativo
cd mobile

# Instala as dependências
npm install

```

Após isso, no terminal da pasta mobile execute o comando abaixo

```bash

# Inicia o aplicativo
expo start

```

Com seu smartphone escaneie o QR code que aparece no terminal utilizando o Expo, app que está disponivel na App store e na Play store para iniciar o aplicativo.
