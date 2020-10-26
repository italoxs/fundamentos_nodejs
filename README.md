<h1 align="center">
  <img src="https://ik.imagekit.io/h3pbjahr5l/github_explorer/bootcamp_gostack_w-mlUIi3D.png" />
</h1>

<h1 align="center">
  🚀️ Desafio 05 - Primeiro projeto Node.js
</h1>

## 📖️ Sobre o desafio
Desenvolvido durante o curso **Bootcamp Gostack** da [Rocketseat](https://rocketseat.com.br/).

Essa será uma aplicação para armazenar transações financeiras de entrada e saída, que deve permitir o cadastro e a listagem dessas transações.

---

## 💻️ Testes realizados
- **should be able to create a new transaction:** Para que esse teste passe, sua aplicação deve permitir que uma transação seja criada, e retorne um json com a transação criada.

- **should be able to list the transactions:** Para que esse teste passe, sua aplicação deve permitir que seja retornado um objeto contendo todas as transações junto ao balanço de income, outcome e total das transações que foram criadas até o momento.

- **should not be able to create outcome transaction without a valid balance:** Para que esse teste passe, sua aplicação não deve permitir que uma transação do tipo outcome extrapole o valor total que o usuário tem em caixa, retornando uma resposta com código HTTP 400 e uma mensagem de erro no seguinte formato: { error: string }
