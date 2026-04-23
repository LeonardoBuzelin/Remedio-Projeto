# 💊 Projeto Remédio API

Este projeto é uma API desenvolvida em Node.js para gerenciamento de medicamentos, usuários e controle de acesso com autenticação segura.

---

## 📌 Tecnologias utilizadas

* Node.js
* Express
* MySQL
* JWT (JSON Web Token)
* Bcrypt
* CORS

---

## 📂 Estrutura do Projeto

```
REMEDIO PROJETO/
│── server.js               # Arquivo principal da API
│── package.json           # Dependências do projeto
│── banco_de_dados_remedio.sql  # Script do banco de dados
│── node_modules/          # Dependências instaladas
```

---

## ⚙️ Funcionalidades

* 🔐 Autenticação de usuários com JWT
* 🔑 Criptografia de senha com Bcrypt
* 👤 Controle de acesso por perfil (hierarquia de usuários)
* 📦 Conexão com banco de dados MySQL
* 🌐 API REST para gerenciamento de dados

---

## 🛠️ Como rodar o projeto

### 1. Clonar o repositório

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
```

### 2. Entrar na pasta

```bash
cd REMEDIO-PROJETO
```

### 3. Instalar dependências

```bash
npm install
```

### 4. Configurar o banco de dados

* Abra o MySQL
* Execute o arquivo:

```
banco_de_dados_remedio.sql
```

---

### 5. Configurar variáveis de ambiente (opcional)

Você pode criar um arquivo `.env`:

```env
DB_HOST=localhost
DB_USER=root
DB_PASS=1234
DB_NAME=remedio_db
JWT_SECRET=segredo_super_secreto
```

---

### 6. Rodar o servidor

```bash
npm start
```

Servidor rodando em:

```
http://localhost:3000
```

---

## 🔐 Autenticação

A API utiliza JWT para autenticação.

Envie o token no header:

```
Authorization: Bearer SEU_TOKEN
```

---

## 📊 Banco de Dados

O projeto utiliza MySQL com pool de conexões para melhor desempenho e escalabilidade.

---

## 📌 Observações

* Em produção, **NÃO use senhas padrão** no banco
* Sempre utilize variáveis de ambiente para segurança
* O `node_modules` não deve ser enviado para o GitHub (use `.gitignore`)

---

## 👨‍💻 Autor

Matheus de Souza Soares - RA: N064943
Henrique Barros - RA: r010082
Leonardo Diogo Buzelin Julio - RA: G790GB9
Luan Martiniano Rocha - RA: R029EB8

---

## 👨‍🏫 Orientação / Professor

Andre Muniz (@agdelira)

---
## 📄 Licença

Este projeto está sob a licença ISC.
