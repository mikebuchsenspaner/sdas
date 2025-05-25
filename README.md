## 📝 Projeto Individual - Agenda de Tarefas (Node.js + Supabase)

Este projeto é uma aplicação web simples para gerenciamento de tarefas (compromissos), com backend em Node.js, banco de dados Supabase e frontend em HTML/JavaScript puro.

---

## 🚀 Como rodar o projeto localmente

### 1. **Clone o repositório**

```bash
git clone https://github.com/mikebuchsenspaner/projeto-individual.git
cd projeto-individual
```

### 2. **Instale as dependências**

Certifique-se que você tenha o Node.js instalado.

```bash
npm install
```

### 3. **Configure as variáveis de ambiente**

Crie um arquivo `.env` na raiz do projeto com o seguinte conteúdo:

```env
SUPABASE_URL=https://SEU_PROJETO.supabase.co
SUPABASE_KEY=chave-secreta-gerada-no-supabase
```

Substitua os valores com os dados reais da sua conta no [Supabase](https://supabase.com/).

### 4. **Inicie o servidor**

```bash
npm start
```

O servidor estará rodando em:

```
http://localhost:3000
```

---

## 🧠 Estrutura do Projeto

```
├── controllers         # Controladores da lógica de negócio
│   └── taskController.js
├── models              # Modelos de acesso ao Supabase
│   └── taskModel.js
├── routes              # Definição das rotas da API
│   └── taskRoutes.js
├── supabase            # Inicialização do cliente Supabase
│   └── supabase.js
├── views               # Frontend (HTML + JS)
│   ├── index.html
│   └── scripts.js
├── .env                # Variáveis de ambiente (NÃO subir para o GitHub)
├── package.json
└── server.js           # Arquivo principal que inicia o servidor
```

---

## ✨ Funcionalidades

* Adicionar tarefas com título, descrição, data e hora
* Listagem das tarefas agrupadas por data
* Integração com banco de dados Supabase

---

## 🛠 Tecnologias Usadas

* Node.js + Express
* Supabase (PostgreSQL + API)
* HTML5 + CSS3 + JavaScript vanilla

---

## 👨‍💻 Autor

**Mike Buchsenspaner**
Repositório: [github.com/mikebuchsenspaner](https://github.com/mikebuchsenspaner)

---

## ⚠️ Observação

Este é um projeto educacional e pode ser expandido com recursos como autenticação de usuário, edição e exclusão de tarefas, responsividade e deploy.
