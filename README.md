<h1 align="center">
    <img alt="Happy" title="Happy" src=".github/capa_happy" />
</h1>

<p align="center">
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-layout">Layout</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-Instalação e Start">Instalação e Start</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-licença">Licença</a>
</p>

<p align="center">
  <img alt="License" src="https://img.shields.io/static/v1?label=License&message=MIT&color=db161d&labelColor=000000&">
  <img alt="Web" src="https://img.shields.io/static/v1?label=Web&message=React&color=15C3D6&labelColor=000000&logo=react">
  <img alt="Server" src="https://img.shields.io/static/v1?label=Server&message=Node.js&color=339933&labelColor=000000&logo=node.js">
  <img alt="Mobile" src="https://img.shields.io/static/v1?label=Mobile&message=React native&color=9700cf&labelColor=000000&logo=react">
  <img alt="TypeScript" src="https://img.shields.io/static/v1?label=Lang&message=TypeScript&color=007ACC&labelColor=000000&logo=typescript">
</p>

<br>

<p align="center">
  <img alt="Happy" src=".github/happy-layout.png" width="100%">
</p>

## 💻 Projeto

O objetivo do Happy é conectar as pessoas com as casas de acolhimento institucional (antigamente conhecido por Orfanatos), com isso você pode visitar as crianças para levar a elas um pouco mais de alegria :)

## 🚀 Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- [Node.js](https://nodejs.org/en/)
- [React](https://reactjs.org)
- [React Native](https://facebook.github.io/react-native/)
- [Express](https://expressjs.com/pt-br/)
- [Expo](https://expo.io/)
- [TypeScript](https://www.typescriptlang.org/)

## ⚙  Instalação e Start
Este repositório é um monorepo, portanto, manterá os fontes do projeto  **Web**,  **API**  e  **Mobile**. Cada parte do projeto tem suas dependências e é necessário instala-las individualmente antes da execução, para isso certifique-se de que tenha  [NPM](https://www.npmjs.com/)  ou  [YARN](https://yarnpkg.com/)  instalado em seu ambiente, além, é claro, o repositório clonado em seu ambiente.

Clone o repositório com:

> git clone https://github.com/Gabroiz/happy.git

As demonstrações utilizam  **YARN**  por padronização, mas, caso use  **NPM**, basta substituir onde estiver escrito  `yarn`  por  `npm`.

- **Instalando dependências do projeto web:**

> cd happy/web
> yarn install

Para executar o projeto  **web**, use no diretório correspondente:

> yarn start

Acesse:  [`http://127.0.0.1:3000/`](http://127.0.0.1:3000/)  ou [`http://localhost:3000/`](http://localhost:3333/) para visualizar.
.

- **Instalando dependências do projeto backend:**

> cd happy/backend
> yarn install

Para executar o projeto  **backend**  é necessário criar o banco de dados com todas as tabelas utilizadas, para isso, use no diretório correspondente:

> yarn typeorm migration:run
> yarn dev

Acesse:  [`http://127.0.0.1:3333/`](http://127.0.0.1:3333/) ou [`http://localhost:3333/`](http://localhost:3333/) para visualizar.

 - **Instalando dependências do projeto mobile:**

Para o projeto mobile, você precisará instalar o Expo no seu celular. Depois disso você pode executar os seguintes comandos

> cd happy/mobile
> yarn install

Para executar o projeto  **web**, use no diretório correspondente:

> yarn start

Ou você pode usar o comando para abrir diretamente no **Android**
> yarn start --android

Acesse:  [`http://127.0.0.1:3000/`](http://127.0.0.1:3000/)  ou [`http://localhost:3000/`](http://localhost:3333/) para visualizar.

## :memo: Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE.md) para mais detalhes.
