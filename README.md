<h1 align="center"> RocketMovies </h1>

> Desafio do Stage 08 - Backend do Explorer da Rocketseat

<p align="center">
  <a href="#project">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#structure">Estrutura</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#details">Detalhamento</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#technologies">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#extras">Extras</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#usage">Utilização</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#license">Licença</a>
</p>

<p align="center">
  <img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT&color=49AA26&labelColor=000000">
</p>

<h2 id="project">📁 Projeto</h2>

Aplicação em Node.js onde o usuário cadastra um filme, preenche com algumas informações (nome, descrição, nota) e cria tags relacionadas a ele.

<h2 id="structure">📌 Estrutura</h2>

Abaixo, temos o diagrama utilizado como base para a criação do banco de dados:

!["Estrutura do banco de dados"](./.github/database-structure.png)

<h2 id="details">📋 Detalhamento</h2>

Explicando cada tabela e seus campos:

<p align="center">
  <img alt="Explicação do banco de dados" src="./.github/database-explanation.png">
</p>

**Valores inteiros que podem variar de 1 até o 5.* <br>
***Exemplos: ação, comedia, terror, medo...etc.*

<h2 id="technologies">💻 Tecnologias</h2>

Esse projeto foi desenvolvido com as seguintes tecnologias:

- Node.js;
- Express;
- SQLite;
- Knex.js.

<h2 id="extras">🔖 Extras</h2>

Alguns detalhes adicionados ao desafio:

- Criptografia de senhas;
- Validação de e-mail;
- Aplicação do cascade para garantir que uma tag seja excluída caso o usuário opte por excluir a nota.

<h2 id="usage">💡 Utilização</h2>

Para instalar a aplicação em sua máquina localmente, clone o projeto, acesse a pasta, instale as dependências e inicie o servidor.

```
$ git clone https://github.com/madalena-rocha/rocket-movies-api
$ cd rocket-movies-api
$ npm install
$ npm run dev
```

<h2 id="license">📝 Licença</h2>

Esse projeto está sob a licença MIT.

---

Feito com :heart: by Madalena :wave: [Me acompanhe nas redes sociais!](https://madalena-rocha.github.io/social-links/)
