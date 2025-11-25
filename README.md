# Todo List em Clojure – Atividade da Unidade 2

**Aluno(a): Edna Cristina Durans Santos**

Este repositório contém o projeto desenvolvido para a Unidade 2 da disciplina, seguindo o tutorial **"Clojure/ClojureScript: Construindo uma Aplicação Persistente e Reativa"**.
O objetivo foi reproduzir passo a passo a construção do Todo List completo, incluindo backend, frontend, integração e persistência em SQLite.

📌 **Link do Tutorial Original:**
[https://www.notion.so/2a5cce975093807aa9f0f0cb0cf69645?pvs=21](https://www.notion.so/2a5cce975093807aa9f0f0cb0cf69645?pvs=21)

---

## 📌 Sobre o Histórico de Commits

Durante o processo, ocorreu um problema em que o projeto original foi apagado acidentalmente.
Para não perder o progresso e manter a avaliação fiel ao desenvolvimento incremental, **o histórico foi restaurado manualmente** com base nos commits antigos e nas fases exigidas pelo tutorial.

Todos os commits foram recriados seguindo os marcos das etapas originais: setup, backend, frontend, integração, persistência e CRUD completo.

---

## 📘 Descrição do Projeto

Este projeto é um Todo List full-stack desenvolvido em Clojure e ClojureScript, incluindo:

* Backend com **Jetty**, **Reitit** e **next.jdbc**
* Frontend reativo com **Reagent**
* Persistência com **SQLite**
* Build e hot-reload com **Shadow-CLJS**
* CRUD completo (Create, Read, Update, Delete)
* Funcionalidades bônus: **toggle** e **delete**

---

## ▶ Como Rodar o Projeto

### **📦 Pré-requisitos**

Certifique-se de ter instalado:

* **Java JDK 17+**
* **Clojure CLI**
* **Node.js + npm**
* **SQLite3** (qualquer versão recente)

---

## **🛠 Instalação**

### 1. Clone o repositório:

```
git clone https://github.com/xp-ednac/Desenvolvimento-de-um-Todo-List
cd Desenvolvimento-de-um-Todo-List
```

### 2. Instale as dependências do frontend:

```
npm install
```

---

## 🚀 Como executar

### **Terminal 1 – Backend**

```bash
clj -M:run
```

O servidor API sobe em:

```
http://localhost:3000
```

---

### **Terminal 2 – Frontend**

```bash
npx shadow-cljs watch app
```

A interface estará disponível em:

```
http://localhost:8020
```

---

## 🧪 Funcionalidades

* Criar tarefas
* Listar tarefas
* Alterar status (toggle)
* Deletar tarefas
* Persistência garantida no SQLite
* Comunicação frontend ↔ backend via REST

---

## 🗃 Estrutura dos Commits

O histórico reflete as etapas do tutorial, incluindo:

1. `feat: setup inicial do projeto com .gitignore`
2. `feat: implementa servidor 'Hello World' com Jetty e Reitit`
3. `feat: implementa API REST de 'todos' com banco em memória`
4. `feat: implementa UI do frontend com estado local (sem API)`
5. `feat: conecta frontend com API do backend (CORS corrigido)`
6. `refactor(db): substitui banco em memória por persistência SQLite`
7. `feat(crud): implementa funcionalidades de toggle e delete`

*Observação:* Estes commits foram recriados manualmente devido à perda acidental do repositório original, mantendo fidelidade às fases do desenvolvimento.

---

## ✔ Entrega

Para envio pelo SIGAA:

* O link público deste repositório deve ser colado na caixa de comentários.
* O arquivo ZIP deve ser baixado em **Code → Download ZIP** e anexado na tarefa.

---

## 📚 Licença

Projeto acadêmico — uso educacional.
