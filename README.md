# Todo List em Clojure – Atividade da Unidade 2

**Aluno(a): Edna Cristina Durans Santos**

Este repositório contém o projeto desenvolvido para a Unidade 2 da disciplina, seguindo o tutorial **"Clojure/ClojureScript: Construindo uma Aplicação Persistente e Reativa"**.
O objetivo foi reproduzir passo a passo a construção do Todo List completo, incluindo backend, frontend, integração e persistência em SQLite.

📌 **Links principais dos Tutoriais Utilizados:**

* Tutorial geral:
  [https://www.notion.so/2a5cce975093807aa9f0f0cb0cf69645?pvs=21](https://www.notion.so/2a5cce975093807aa9f0f0cb0cf69645?pvs=21)

---

## 📌 Sobre o Histórico de Commits

O projeto original foi apagado acidentalmente durante o desenvolvimento.
Para manter a autenticidade do processo de construção incremental, **o histórico foi restaurado manualmente do que tinha na máquina, de ontem**, seguindo as etapas do tutorial.

---

## 📘 Descrição do Projeto

Este projeto é um Todo List full-stack desenvolvido em Clojure e ClojureScript, incluindo:

* Backend com **Jetty**, **Reitit** e **next.jdbc**
* Frontend reativo com **Reagent**
* Persistência em **SQLite**
* Build/Hot reload com **Shadow-CLJS**
* CRUD completo (Create, Read, Update, Delete)
* Funcionalidades bônus: toggle e delete

---

## ▶ Como Rodar o Projeto

### 📦 Pré-requisitos

* Java JDK 17+
* Clojure CLI
* Node.js + npm
* SQLite3

---

## 🛠 Instalação

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

## 🚀 Execução

### **Terminal 1 – Backend**

```bash
clj -M:run
```

Servidor: [http://localhost:3000](http://localhost:3000)

---

### **Terminal 2 – Frontend**

```bash
npx shadow-cljs watch app
```

Interface: [http://localhost:8020](http://localhost:8020)

---

## 🧪 Funcionalidades

* Criar tarefas
* Listar tarefas
* Alterar status (toggle)
* Deletar tarefas
* Persistência em SQLite
* Comunicação frontend ↔ backend

---

## 🗃 Estrutura dos Commits (com links das etapas)

1. **feat: setup inicial do projeto com .gitignore**
   Tutorial base:
   [https://www.notion.so/2a5cce975093807aa9f0f0cb0cf69645?pvs=21](https://www.notion.so/2a5cce975093807aa9f0f0cb0cf69645?pvs=21)

2. **feat: implementa servidor 'Hello World' com Jetty e Reitit**
   Etapa correspondente no tutorial:
   [https://www.notion.so/2a5cce975093807aa9f0f0cb0cf69645?pvs=21#ee21a4fa7a28424fa1c45ffb391d4bdf](https://www.notion.so/2a5cce975093807aa9f0f0cb0cf69645?pvs=21#ee21a4fa7a28424fa1c45ffb391d4bdf)

3. **feat: implementa API REST de 'todos' com banco em memória**
   Parte referente à API e handlers:
   [https://www.notion.so/2a5cce975093807aa9f0f0cb0cf69645?pvs=21#1f2edfcb56d44c199adf63ab768c132d](https://www.notion.so/2a5cce975093807aa9f0f0cb0cf69645?pvs=21#1f2edfcb56d44c199adf63ab768c132d)

4. **feat: implementa UI do frontend com estado local (sem API)**
   Construção de UI com Reagent:
   [https://www.notion.so/2a5cce975093807aa9f0f0cb0cf69645?pvs=21#4b964f97fd1342428f3abf3508f2cc5e](https://www.notion.so/2a5cce975093807aa9f0f0cb0cf69645?pvs=21#4b964f97fd1342428f3abf3508f2cc5e)

5. **feat: conecta frontend com API do backend (CORS corrigido)**
   Tutorial da Fase 4:
   [https://profsergiocosta.notion.site/Fase-4-Conectando-o-Frontend-ao-Backend-2a5cce97509380a5a5e2e54246ed0125?pvs=25](https://profsergiocosta.notion.site/Fase-4-Conectando-o-Frontend-ao-Backend-2a5cce97509380a5a5e2e54246ed0125?pvs=25)

6. **refactor(db): substitui banco em memória por persistência SQLite**
   Etapa de persistência:
   [https://www.notion.so/2a5cce975093807aa9f0f0cb0cf69645?pvs=21#614fa91e813b4c3d99e36fcff7bcac28](https://www.notion.so/2a5cce975093807aa9f0f0cb0cf69645?pvs=21#614fa91e813b4c3d99e36fcff7bcac28)

7. **feat(crud): implementa funcionalidades de toggle e delete**
   Fase bônus do tutorial:
   [https://www.notion.so/2a5cce975093807aa9f0f0cb0cf69645?pvs=21#b842d1e6c7aa4c88a9c75b2f4ebda9e1](https://www.notion.so/2a5cce975093807aa9f0f0cb0cf69645?pvs=21#b842d1e6c7aa4c88a9c75b2f4ebda9e1)



---
