<h1 align="center">:file_cabinet: Customers API</h1>

## :memo: Descrição

Essa é uma API que controla clientes, contatos e usuários em um banco de dados PostgresSQL. O acesso é controlado por um middleware que verifica se o usuário está cadastrado no sistema. A verificação é feita por criptografia e os dados de senhas são armazenadas pelo Bcrypt e armazenadas no banco de dados. Todas as funcionalidades só são liberadas se o usuário estiver logado.

## :books: Funcionalidades

- <b>Create Customers</b>: Cria um novo cliente no banco de dados.
- <b>Create Contacts</b>: Cria um novo contato vinculado a um cliente previamente cadastrado.
- <b>Create Users</b>: Cria um novo usuário para ter acesso ao sistema.

## :wrench: Tecnologias utilizadas

- NodeJS, Express, PostgresSQL, Sequelize, JsonWebToken e NodeMailer;

## :rocket: Rodando o projeto

Para rodar o repositório é necessário clonar o mesmo, dar o seguinte comando para instalar as dependências do projeto:

```
yarn install
```

Para rodar o sistema é só dar o comando abaixo:

```
yarn dev
```

Executar o comando abaixo para iniciar as migrations:

```
yarn sequelize db:migrate
```

## :soon: Implementação futura

- Estou aguardando sugestões e melhorias. Fique à vontade para fazer o fork e pull requests.

## :handshake: Colaboradores

<table>
  <tr>
    <td align="center">
      <a href="https://www.linkedin.com/in/emersonbbezerra/">
        <img src="https://avatars.githubusercontent.com/u/56259137?v=4" width="100px;" alt="Imagem fictícia de Emerson no LinkedIN"/><br>
        <sub>
          <b>Eu mesmo!</b>
        </sub>
      </a>
    </td>
  </tr>
</table>

## :dart: Status do projeto

```

```
