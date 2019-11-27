# Eight One (Backend)

## Instalação

Para executar a aplicação localmente é necessário ter instalado na máquina o **Node.js** (os exemplos abaixo serão utilizando **Yarn**).

1. Clone o projeto em sua máquina

2. Execute o comando `yarn install` para instalar as dependências do projeto

3. É necessário criar um arquivo .env na raiz do projeto contendo as variáveis necessárias para configuração do ambiente. Para isso utilize o arquivo .env.example disponbilizado no projeto como base para criação do mesmo.

4. Execute o comando `yarn dev` para subir o projeto localmente, ele está configurando para abrir em http://localhost:3333

5. É necessário possuir um banco de dados postgres para executar as migrations da API.

6. Para executar as migrations, execute o comando `yarn sequelize db:migration`
