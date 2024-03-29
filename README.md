# CRUD_MYSQL_NODEJS

Este projeto é um CRUD (Create, Read, Update, Delete) simples desenvolvido em Node.js com conexão ao banco de dados MySQL, permitindo a manipulação fácil e intuitiva de dados em uma tabela.

## 🚀 Tecnologias 
- Node.js
- MySQL
- Express
- Sequelize (ORM)
- Body-parser
- Nodemon (para desenvolvimento)

## 📦 Instalação 
Para instalar e executar o projeto, siga os passos abaixo:

1. **Clone o repositório:**
    ```bash
    git clone https://github.com/matheusasa/CRUD_MYSQL_NODEJS.git
    ```

2. **Entre no diretório do projeto:**
    ```bash
    cd CRUD_MYSQL_NODEJS
    ```

3. **Instale as dependências:**
    ```bash
    npm install
    ```

4. **Configure o arquivo .env com suas credenciais de banco de dados:**
    ```env
    DB_HOST=localhost
    DB_USER=root
    DB_PASSWORD=
    DB_NAME=my_database
    ```

5. **Execute as migrations para criar a tabela no banco de dados:**
    ```bash
    npx sequelize db:migrate
    ```

6. **Inicie o servidor:**
    ```bash
    npm start
    ```

7. **Teste as rotas do CRUD:**
   - **GET /users:** Lista todos os usuários
   - **GET /users/:id:** Obtém um usuário por ID
   - **POST /users:** Cria um novo usuário
   - **PUT /users/:id:** Atualiza um usuário por ID
   - **DELETE /users/:id:** Exclui um usuário por ID

## 📝 Licença 
Este projeto está licenciado sob a MIT License - consulte o arquivo [LICENSE.md](LICENSE.md) para obter detalhes.

Espero que você encontre esse projeto útil! Sinta-se à vontade para abrir uma issue ou enviar um pull request se encontrar algum problema ou tiver uma sugestão de melhoria.
