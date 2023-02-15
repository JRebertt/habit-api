### ⚠ Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Git](https://git-scm.com), [Node.js](https://nodejs.org/en/).
Além disto é bom ter um editor para trabalhar com o código como [VSCode](https://code.visualstudio.com/)

### 🎲 Rodando o Back End (servidor)

```bash
# Clone este repositório
$ git clone <https://github.com/JRebertt/habit-api.git>

# Acesse a pasta do projeto no terminal/cmd
$ cd habit-api

# Instale as dependências
$ npm install

# Execute a aplicação em modo de desenvolvimento
$ npm run dev

# O servidor inciará na porta:3333 - Url do Servidor <http://localhost:3333>

# Quando a menssagem "Server is Running!" for apresentadado no terminal, seu servidor estará ligado e rodando localmente!

```

### 👾 Possiveis Erros

- Certifique de que o arquivo `.env` foi adiacionado corretamente!

- Caso não esteja encontrando, basta criar um arquivo com o nome acima, inserir esse codigo

```javascript
DATABASE_URL = "file:./dev.db";
```

- Em seguida execute esse comando, isso restabelecerá o link entre o `schema.prisma` e o arquivo `.env`

```node
npx prisma generate
```

### ◭ Prisma studio

- Para uma melhor experiencia com o DB do prisma, use o comando:

```node
npx prisma studio
```

Caso queira fazer algum teste no servidor recomendo usar a o [Insomnia](https://insomnia.rest/download)

### 🛠 Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

- [TypeScript](https://www.typescriptlang.org/)
- [Node.js](https://nodejs.org/en/)
- [Prisma](https://www.prisma.io/)
