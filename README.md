<h1 align="center">
    <img alt="Happy" title="Happy" src="logo.svg" />
</h1>

<p align="center">
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#%EF%B8%8F-instalação-e-execução">Instalação e execução</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-licença">Licença</a>
</p>

<p align="center">
  <img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT&color=15C3D6&labelColor=000000">
</p>

<br>

<p align="center">
  <img alt="Happy" src="happy.png" width="100%">
</p>

## 🚀 Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- [Node.js](https://nodejs.org/en/)
- [React](https://reactjs.org)
- [React Native](https://facebook.github.io/react-native/)
- [Expo](https://expo.io/)
- [TypeScript](https://www.typescriptlang.org/)

## 💻 Projeto

O Happy é uma aplicação que conecta pessoas à casas de acolhimento institucional para fazer o dia de muitas crianças mais feliz 💜. <br>
Este projeto foi desenvolvido durante a **Next Level Week #3** da [Rocketseat](https://rocketseat.com.br) 🚀 👩🏽‍🚀

## ⚡️ Instalação e execução 

_ps: Se precisar de ajuda para fazer um clone, esse [tutorial aqui](https://help.github.com/pt/github/creating-cloning-and-archiving-repositories/cloning-a-repository) vai te ajudar 💖_

1. Abra o terminal do seu computador. Se estiver no Windows pode ser o CMD ou Powershell;
2. Altere o diretório de trabalho atual para o local em que deseja ter o código do módulo salvo no seu computador;
3. Faça um clone desse repositório rodando: <br> `git clone https://github.com/jean-ross/nlw3-happy.git`;
4. Entre na pasta do projeto rodando pelo terminal: `cd nlw3-happy`;

### Server

1. Entre na pasta rodando pelo terminal: `cd backend`;
2. Rode `yarn` para instalar as dependências do projeto;
3. Rode `yarn typeorm migration:run` para criar a base de dados;
4. Rode `yarn dev` para iniciar o servidor de desenvolvimento.

### Web

1. Entre na pasta rodando pelo terminal: `cd web`;
2. Rode `yarn` para instalar as dependências do projeto;
3. Renomeie o arquivo <b>.env.example</b> para <b>.env</b>
4. Abra o arquivo <b>.env</b> e configure a variável `REACT_APP_MAPBOX_TOKEN` com um token pessoal do [Mapbox](https://www.mapbox.com/)
5. Rode `yarn start` para iniciar a aplicação web.

### Mobile

1. Entre na pasta rodando pelo terminal: `cd mobile`;
2. Rode `yarn` para instalar as dependências do projeto;
3. Abra o arquivo <b>src/services/api.ts</b> e altere o valor do parâmetro `baseURL` para o IP da estação que está executando o projeto Server, e salve o arquivo;
4. Rode `yarn start` para iniciar a aplicação mobile.
5. Escaneie o QR Code da aplicação com a câmera do seu celular para testar a aplicação em seu dispositivo (para isso, seu dispositivo deve estar conectado à mesma rede em que a API está sendo executada), ou execute utilizando o emulador de iOS ou Android.

## :memo: Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE.md) para mais detalhes.

---

Feito com ♥ by Jean Ross :wave:
