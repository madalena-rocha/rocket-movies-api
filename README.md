#rocket-movies-api

Aplicação em Node.js onde o usuário cadastra um filme, preenche com algumas informações (nome, descrição, nota) e cria tags relacionadas a ele.
Abaixo, temos o diagrama utilizado como base para a criação do banco de dados:

!["Estrutura do banco de dados"](./.github/database-structure.png)

Explicando cada tabela e seus campos:

!["Explicação do banco de dados"](./.github/database-explanation.png)

**Valores inteiros que podem variar de 1 até o 5.*
***Exemplos: ação, comedia, terror, medo...etc.*

Alguns detalhes adicionados ao desafio:

- Criptografia de senhas;
- Validação de e-mail;
- Aplicação do cascade para garantir que uma tag seja excluída caso o usuário opte por excluir a nota.

