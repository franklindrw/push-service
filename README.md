
![notifications-banner](https://user-images.githubusercontent.com/81038899/215006381-aac563f2-3323-49bf-9ce1-00c8de0994ec.jpg#vitrinedev)
<h1 align="center"> API REST - Notifications </h1>
<div id="statusProject" align="center">
  <img src="https://img.shields.io/github/license/franklindrw/push-service.svg?style=for-the-badge" />
  <img src="https://img.shields.io/github/stars/franklindrw/push-service.svg?style=for-the-badge" />
  <img src="https://img.shields.io/github/forks/franklindrw/push-service.svg?style=for-the-badge" />
  <img src="https://img.shields.io/github/issues/franklindrw/push-service.svg?style=for-the-badge" />
  <img src="http://img.shields.io/static/v1?label=STATUS&message=CONCLUIDO&color=green&style=for-the-badge"/>
</div>

<br />

| :placard: Vitrine.Dev | https://cursos.alura.com.br/vitrinedev/franklindrw |
| -------------  | --- |
| :sparkles: Nome        |  API REST - Notifications
| :label: Tecnologias | Node, NestJs, Typescript, Prisma, mySql, Jest
| :rocket: URL         | 
| :fire: Desafio     | Microserviço Node feito com arquitetura API REST, usando framework NestJS e Typescript.

<br /><br />

## 🧭 Índice
* [Sobre o Projeto](#-sobre-o-projeto)
  * [Arquitetura](#arquitetura)
  * [Prisma](#prisma)
  * [Jest](#jest)
  * [Linguagens Usadas](#-construído-com)
* [Instalação](#-instalação)
  * [Requisitos](#requisitos)
  * [API](#api)
* [Autor](#-autor)
* [Licença](#-licença)

<br /><br />

## 🔎 Sobre o Projeto
O Microserviço Notifications tem como objetivo servir aplicativos com requisições HTTP para enviar e atualizar os status das mensagens criadas pelo próprio sistema, assim mantendo um histórico de cada notificação enviada para os usuários.

### Arquitetura
Sua arquitetura foi seguindo o framework [NestJS](https://nestjs.com/), com esse framework podemos criar uma API Rest de forma rápida pois ao iniciar o projeto com NestJs, o mesmo já nos fornece um ambiente pré-montado para trabalhar, assim se preocupando em apenas criar as classes da aplicação e suas funções.

![image](https://user-images.githubusercontent.com/81038899/215008369-c20ee346-bf78-43d1-8516-4291c34efd09.png)

O framework já trás como padrão uma main já configurada, os Modulos e o Controle com uma rota de exemplo, com o mesmo também é possível criar novas rotas com poucos comandos no cli, já que o framework é baseado no Angular

### Prisma
Com o [ORM Prisma](https://www.prisma.io/) conseguimos criar, editar tabelas no banco de dados sem precisar escrever SQL diretamente no banco, a ideia do ORM é facilitar na hora do desenvolvimento, onde podemos configurar o arquivo de schema para criar a tabela e automaticamente criar os comando de SQL e executar no banco conectado.

![image](https://user-images.githubusercontent.com/81038899/215009517-0062def2-16e2-4a7b-b525-1594ebbac5b3.png)

E nos Models da aplicação conseguimos tratar os dados de forma simples usando um json e funções do próprio Prisma para inserir e/ou alterar os dados

![image](https://user-images.githubusercontent.com/81038899/215010010-ef02d6a9-9e27-47b9-9633-0a002d09a40f.png)

### Jest
Já o [Jest](https://jestjs.io/pt-BR/) é um framework voltado para testes unitários, com ele é possível criar testes da aplicação enquanto é desenvolvida, assim evitando que conforme o crescimento do projeto algum componente fique para trás com algum bug, pois o framework quando iniciado faz o teste de todos os specs criados durante a aplicação de forma rápida, poupando tempo do desenvolvedor testar todos os componentes ao criar novas funções.

![image](https://user-images.githubusercontent.com/81038899/215010627-36b56859-77c2-4666-ae11-7349d707ee01.png)
![image](https://user-images.githubusercontent.com/81038899/215011082-2fc4578a-7a40-4956-8a47-7c95e6b14d3c.png)

![image](https://user-images.githubusercontent.com/81038899/215011381-7986524d-047c-4c29-9ae0-90f7f8803214.png)

### 🔨 Construído com
<div id="statusProject" align="left">
 <img src="https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white" />
 <img src="https://img.shields.io/badge/Prisma-3982CE?style=for-the-badge&logo=Prisma&logoColor=white" />
 <img src="https://img.shields.io/badge/nestjs-%23E0234E.svg?style=for-the-badge&logo=nestjs&logoColor=white" />
 <img src="https://img.shields.io/badge/-jest-%23C21325?style=for-the-badge&logo=jest&logoColor=white" />
</div>

<br />

## 📥 Instalação

### Requisitos
É necessário ter instalado Node.js, caso não tenha pode baixar <a href="https://nodejs.org/pt-br/">Clicando aqui!</a>

### API

1. Dentro da pasta do projeto use o comando abaixo:
    ```
      npm i
    ```
    e aguarde instalar todas as bibliotecas necessárias para rodar o projeto.
    
2. Após gerar os arquivos você pode testar a aplicação na máquina usando o comando:
    ```
      npm run start:dev
    ```
    em seguida irá iniciar o projeto no endereço: http://localhost:3000

3. Caso queira instalar em um servidor de produção pode compilar a aplicação usando o comando:
    ```
      npm run build
    ```
    em seguida copie a pasta dist gerada dentro da aplicação para o servidor desejado, navegue até dentro da pasta onde está a pasta build, e com Node instalado e use o comando abaixo para rodar o build:
    ```
      node ./dist/src/main.js
    ```

### 🖊 Autor

<a href="https://github.com/franklindrw">
<img style="border-radius: 50%; width: 100px" src="https://github.com/franklindrw.png" alt="Foto do Autor"/>
<br />
<sub><b>Franklin Campos </b></sub>
</a>
</br>
<p>Feito por <strong>Franklin Campos</strong> 👋🏻 </br>
Entre em contato!</p>
<div>
<a href="https://www.linkedin.com/in/franklindrw" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>
<a href="mailto:franklindrw@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>
<a href="https://www.instagram.com/franklindrw" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
</div>

## 📋 Licença
<p> Copyright 2023 © Franklin Campos </br>
This project is MIT licensed.</p>
