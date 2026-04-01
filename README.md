# 🌐 Testes de API com Postman

Projeto desenvolvido para validar requisições HTTP utilizando o Postman, aplicando testes automatizados em uma API REST pública.

O objetivo é demonstrar conhecimentos em testes de API, validação de respostas e boas práticas de qualidade de software (QA).

---

## 🔧 Ferramentas utilizadas

* Postman

---

## 🌐 API utilizada

https://jsonplaceholder.typicode.com/

---

## 🧪 Testes realizados

### ✅ GET /posts

* Validação de status code 200
* Verificação de retorno em formato array
* Validação de lista não vazia
* Verificação de campos obrigatórios (id, title, body)

### ✅ GET /posts/1

* Validação de status code 200
* Verificação de retorno de objeto único

### ✅ POST /posts

* Validação de status code 201
* Criação de novo post
* Validação de retorno com ID

---

## 🧠 Estratégia de Testes

Os testes foram estruturados para validar:

* Status das requisições HTTP
* Estrutura dos dados retornados
* Integridade das respostas da API
* Comportamento esperado dos endpoints (CRUD)

---

## 📸 Evidências

### 🔹 GET - Listar posts

![GET posts](./evidencias/get-posts.png)

### 🔹 GET - Post por ID

![GET post ID](./evidencias/get-post-id.png)

### 🔹 POST - Criar post

![POST create](./evidencias/post-create.png)

---

## 📂 Arquivos do projeto

* Collection exportada do Postman (.json)
* Pasta de evidências com prints dos testes

---

## 🚀 Sobre mim

Cursando Tecnólogo em Análise e Desenvolvimento de Sistemas (ADS), com foco em Quality Assurance (QA) e testes de software.

Buscando oportunidade de estágio ou posição júnior na área de Tecnologia da Informação.
