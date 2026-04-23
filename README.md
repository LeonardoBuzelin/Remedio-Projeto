# 💊 Projeto Remédio API

Uma API robusta desenvolvida em **Node.js** para o gerenciamento centralizado de medicamentos e controle de usuários. O sistema conta com autenticação segura e diferentes níveis de acesso.

---

## 🚀 Funcionalidades

- 🔐 **Autenticação Segura**: Login com JWT (JSON Web Token)  
- 🔒 **Segurança de Dados**: Criptografia de senhas com Bcrypt  
- 👥 **Controle de Acesso**: Sistema de perfis com hierarquia  
- 🗄️ **Persistência**: Integração com MySQL usando pool de conexões  
- 🌐 **Arquitetura RESTful**: Estrutura escalável e organizada  

---

## 🛠️ Tecnologias e Ferramentas

- **Node.js**
- **Express**
- **MySQL**
- **JWT**
- **Bcrypt**
- **CORS**

---

## 📂 Estrutura do Projeto

```
REMEDIO-PROJETO/
├── server.js
├── package.json
├── banco_de_dados_remedio.sql
└── .gitignore
```

---

## ⚙️ Configuração e Instalação

### 1. Clonar e instalar dependências

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
cd REMEDIO-PROJETO
npm install
```

---

### 2. Configurar o banco de dados

- Certifique-se de que o MySQL está rodando  
- Execute o script:
```
banco_de_dados_remedio.sql
```

---

### 3. Variáveis de ambiente

Crie um arquivo `.env` na raiz:

```
DB_HOST=localhost
DB_USER=seu_usuario
DB_PASS=sua_senha
DB_NAME=remedio_db
JWT_SECRET=sua_chave_mestra
```

---

### 4. Executar o projeto

```bash
npm start
```

A API estará disponível em:  
👉 http://localhost:3000

---

## 🔐 Autenticação

Para acessar rotas protegidas, envie o token no header:

```
Authorization: Bearer SEU_TOKEN_AQUI
```

---

## 📌 Boas práticas

- ❌ Nunca exponha senhas ou JWT em repositórios públicos  
- ✅ Use variáveis de ambiente (.env)  
- ✅ Mantenha o `node_modules` no `.gitignore`  

---

## 👨‍💻 Autores

- Matheus de Souza Soares - RA: N064943  
- Henrique Barros - RA: r010082  
- Leonardo Diogo Buzelin Julio - RA: G790GB9  
- Luan Martiniano Rocha - RA: R029EB8  

---

## 👨‍🏫 Orientação

Andre Muniz (@agdelira)

---

## 📄 Licença

Este projeto está sob a licença **ISC**
