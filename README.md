# Gerenciador de Usuários - Node.js

Este é um simples gerenciador de usuários desenvolvido em Node.js que permite a criação, atualização e exclusão de usuários. O projeto utiliza o framework Express e a biblioteca uuid para geração de identificadores únicos.

## Como Utilizar

### Pré-requisitos
- Node.js instalado
- Insomnia (ou outra ferramenta similar para testar requisições HTTP)

### Passos

1. **Clonar o Repositório:**
   ```bash
   git clone https://github.com/seu-usuario/nome-do-projeto.git
2. **Instalar dependências:**
   npm install
3. **Executar o Servidor:**
   node app.js
   
Utilizando o Insomnia
O projeto foi testado utilizando o Insomnia para enviar requisições HTTP para as rotas disponíveis.

GET /users: Retorna todos os usuários cadastrados.
POST /users: Cria um novo usuário. Enviar no corpo da requisição um objeto JSON com os campos "name" e "age".
PUT /users/:id: Atualiza um usuário existente com o ID especificado. Enviar no corpo da requisição um objeto JSON com os campos "name" e "age".
DELETE /users/:id: Exclui o usuário com o ID especificado.
