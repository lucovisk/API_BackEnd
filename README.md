# API_BackEnd
# Backend Project

## Descrição
Este projeto é um backend desenvolvido em TypeScript, utilizando a arquitetura MVC, com um banco de dados relacional e autenticação via JWT.

## Estrutura de Pastas
- `src/controllers`: Contém os controladores responsáveis pelas requisições HTTP.
- `src/models`: Define os modelos de dados (entidades).
- `src/repositories`: Contém as funções que interagem diretamente com o banco de dados.
- `src/services`: Contém a lógica de negócios.
- `src/routes`: Define as rotas da aplicação.

## Instalação
1. Clone o repositório.
2. Instale as dependências: `npm install`.
3. Configure o arquivo `.env` com as variáveis de ambiente.
4. Inicie o servidor com `npm run dev`.

## Endpoints
- `POST /api/auth/login`: Realiza o login do usuário. Retorna um token JWT.
