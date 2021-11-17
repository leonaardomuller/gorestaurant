<h3 align="center">
  <img src="https://user-images.githubusercontent.com/60147880/142247817-537916c5-1b95-4aa1-abd8-84e2814b273f.png" marginTop="100px" width="400px"/>
</h3> 
<h1>Projeto GoRestaurant</h1>
 Exemplo interface admin de restaurante.

## 💻 Projeto

  <h4>Features:</h4>
  <ul>
    <li>Dashboard com listagens dos pratos</li>
    <li>Cadastro de novos pratos</li>
    <li>Atualização de pratos (preço, descrição, nome)</li>
    <li>Exclusão de pratos do cardápio</li>
    <li>Controle de disponibilidade (Toogle)</li>
  </ul>

### ♊ Clonando o Repositório

```bash

$ git clone https://github.com/leonaardomuller/gorestaurant.git

# entre na pasta do projeto

$ cd gorestaurant

```

Instale as dependências

```bash

$ yarn

# ou, caso use npm

$ npm install

```

Rode a aplicação

```bash

$ yarn start

# ou, caso use npm

$ npm start

```

### Utilizando uma fake API

Antes de tudo, para que você tenha os dados para exibir em tela, criamos um arquivo que você poderá utilizar como fake API para te prover esses dados.

Para isso, deixamos instalado no package.json uma dependência chamada `json-server`, e um arquivo chamado `server.json` que contém os dados para uma rota `/foods`. Para executar esse servidor você pode executar o seguinte comando:

```js
  yarn json-server server.json -p 3333
```

## 🔖 Layout

<table>
  <tr>
    <td><strong>Dashboard - Painel de listagem</strong></td>
  <tr>

   <tr>
    <td><img src ="https://user-images.githubusercontent.com/60147880/142249358-e54a9024-b6d0-458a-94a0-c738384bb9d4.PNG"/></td>
  <tr>
</table>