# :scroll: Cubo Challenge

<p align="center">
  <img src="https://cubo.network/assets/images/cubo.svg" width="200">
</p>

Projeto Full stack realizado como case no curso da Labenu. Esse repositório conta com a parte de front end do projeto, no qual foi implementado usando a API construída pelo back, com dois métodos integrados para criação de usuário e consulta de dados. O usuário consegue criar seu cadastro e sua participação através de um formulário, e ao mesmo tempo que insere essas informações, a tabela e gráfico do app se atualiza.

O desafio é disponibilizado acessando o seguinte link: https://github.com/cubonetwork/fullstack-challenge.

## :link: Link Surge 
- Acesse o site clicando no link http://case-cubo-pablo.surge.sh

## :link: Link Documentação
- Acesse a documentação clicando no link https://documenter.getpostman.com/view/20353382/VUqmvf1Q


## ⚙️ Funcionalidades
✅ Todos os campos do formulário são obrigatórios;

✅ Os dados enviados pelo formulário são salvos no banco de dados;

✅ APIs para enviar e receber os dados;

✅ Representar tabela por meio de um gráfico dinâmico.

## :hammer_and_wrench: Ferramentas 

### 🍮 Frontend
- [React](https://pt-br.reactjs.org/);
- [Axios](https://axios-http.com/ptbr/docs/intro/);
- [Styled-components](https://styled-components.com/docs/);
- [React Google Charts](https://www.react-google-charts.com/)
- [react-chartjs-2](https://www.npmjs.com/package/react-chartjs-2)

### 🤵 Backend
- [Node.js](https://nodejs.dev/)
- [Typescript](https://www.typescriptlang.org/docs/);
- [Express](http://expressjs.com/);
- [Knex](http://knexjs.org/guide/);
- [UUID](https://www.npmjs.com/package/uuid);
- [Dotenv](https://www.npmjs.com/package/dotenv);
- [MySQL](https://dev.mysql.com/doc/);


## :computer: Layout Desenvolvido

![screencapture-case-cubo-pablo-surge-sh-2022-08-24-16_59_39](https://user-images.githubusercontent.com/84820536/186511959-65d47b6d-4a89-46b2-a450-5ba8008e3a93.png)


## 📁 Acessar Projeto Localmente

- *Clonar o repositório:*

```
$ git clone LinkDoRepositorio
```

- *Acessar o projeto backend:*

```
$ cd back-end
```

- *Instalar dependências do backend:*

```
$ npm install
```

- *Executar projeto back-end:*

```
$ npm start
```

- *Executar o projeto back-end em ambiente de desenvolvimento:*

```
$ npm run dev
```
- *Instalar dependências do front-end:*

```
$ npm install
```

- *Muda URL base:*

Caso queira testar toda a aplicação localmente, é necessário alterar a baseURL utilizada para conectar os projetos frontend e o backend. Para isso siga o caminho

 ```src/ -> request/ -> requests.ts```
Subistitua a linha:
```
6 const baseURL = 'http://localhost:3003/'
```
por:
```
const baseURL = 'http://localhost:3003/'
```
- *Executar projeto front-end:*
```
$ npm start
```
## 👨‍💻 Desenvolvedor

<img src="https://avatars.githubusercontent.com/u/84820536?v=4" width=115> <br><sub>Pablo Gomes dos Santos</sub>
