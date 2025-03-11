# 🐷 Poupig

<div align="center">
<img src="https://github.com/portfolio-projetos-dev/poupig/raw/main/.gitassets/capa.png" width="350" />

<div data-badges>
    <img src="https://img.shields.io/github/stars/portfolio-projetos-dev/poupig?style=for-the-badge" alt="GitHub stars" />
    <img src="https://img.shields.io/github/forks/portfolio-projetos-dev/poupig?style=for-the-badge" alt="GitHub forks" />
    <img src="https://img.shields.io/github/issues/portfolio-projetos-dev/poupig?style=for-the-badge" alt="GitHub issues" />
</div>

<div data-badges>
   <img src="https://img.shields.io/badge/next.js-%23000000.svg?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js" />
   <img src="https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
   <img src="https://img.shields.io/badge/firebase-%23039BE5.svg?style=for-the-badge&logo=firebase&logoColor=white" alt="Firebase" />
   <img src="https://img.shields.io/badge/firestore-%23FFCA28.svg?style=for-the-badge&logo=firebase&logoColor=white" alt="Firestore" />
   <img src="https://img.shields.io/badge/turbo%20repo-%23000000.svg?style=for-the-badge&logo=turbo&logoColor=white" alt="Turbo Repo" />
   <img src="https://img.shields.io/badge/jest-%23C21325.svg?style=for-the-badge&logo=jest&logoColor=white" alt="Jest" />
</div>
</div>

Poupig é uma aplicação fullstack desenvolvida para oferecer uma solução completa e eficiente no gerenciamento de dados financeiros. Projetada com uma interface intuitiva, a plataforma permite que os usuários organizem, analisem e acompanhem suas finanças de forma prática e segura.

Com o Poupig, é possível registrar receitas e despesas categorizando cada movimento financeiro para facilitar o controle e a visualização. Além disso, a aplicação oferece relatórios detalhados e gráficos interativos que ajudam os usuários a entenderem melhor seus hábitos financeiros, identificar padrões de consumo e tomar decisões mais informadas para alcançar seus objetivos.

## 🖥️ Como rodar o projeto 🖥️

### Requisitos:

- Node.js instalado
- Conta no Firebase

### Execução:

1. Clone o repositório:

   ```sh
   git clone https://github.com/portfolio-projetos-dev/poupig.git
   ```

2. Instale as dependências rodando o comando abaixo na pasta raiz do projeto:

   ```sh
   npm install
   ```

3. Configure um projeto no console do Firebase

4. Configure as variáveis de ambiente criando um arquivo `.env` com base no arquivo `.env.example` e preencha as variáveis de acordo com as variáveis de acesso ao seu projeto no console do Firebase.

5. Adicione no seu projeto do Firebase a autenticação via Google e com e-mail e senha

6. Habilite o uso das Cloud Functions no seu projeto no Firebase

7. Instale e faça login no CLI do firebase com os comandos:

```sh
npm i -g firebase-tools
firebase login
```

8. Liste os projetos no terminal:

```sh
firebase projects:list
```

9. Dentro da pasta `apps/backend` do projeto selecione o projeto criado no console do firebase usando o número do projeto obtido com o comando `firebase projects:list`

```sh
firebase use <numero-do-projeto>
```

Depois de executar o login é solicitado via browser para selecionar a conta

10. No console do Google Cloud, configure o Pub/Sub e crie um topic com nome de `extrato-alterado`

11. Inicie a aplicação:

```sh
npm run dev
```

12. Acesse a aplicação em [http://localhost:3000](http://localhost:3000).

## 🗒️ Features do projeto 🗒️

- Visualização de receitas, despesas e lucro
- Interface intuitiva e responsiva para monitoramento financeiro
- Exibição de dados financeiros em tempo real
- Relatórios detalhados e gráficos interativos
- Autenticação segura
- Integração com APIs de bancos para sincronização automática
- Histórico de transações e busca avançada
- Modo escuro para melhor visualização

![](https://github.com/portfolio-projetos-dev/poupig/raw/main/.gitassets/1.png)

![](https://github.com/portfolio-projetos-dev/poupig/raw/main/.gitassets/2.png)

![](https://github.com/portfolio-projetos-dev/poupig/raw/main/.gitassets/3.png)

## 💎 Links úteis 💎

- [Next.js](https://nextjs.org/)
- [Firebase](https://firebase.google.com/)
