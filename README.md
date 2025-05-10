# 💸 My Money App

Aplicação full-stack para gestão financeira pessoal, permitindo o controle de ciclos de faturamento com créditos e débitos, além de autenticação de usuários.

## 📌 Funcionalidades

* **Dashboard** com resumo financeiro em tempo real.
* **CRUD completo** de ciclos de faturamento (créditos e débitos).
* **Autenticação JWT** com login e cadastro de usuários.
* **Formulários dinâmicos** com validação e manipulação de múltiplos itens.
* **Interface responsiva** baseada no AdminLTE.

## 🧰 Tecnologias Utilizadas

### Backend (Node.js + Express)

* **MongoDB** com **Mongoose** para modelagem de dados.
* **Express** para criação de APIs RESTful.
* **JWT** para autenticação segura.
* **Middleware personalizados** para CORS, tratamento de erros e parsing de queries.

### Frontend (React + Redux)

* **React** com **Redux** e **Redux-Form** para gerenciamento de estado e formulários.
* **React-Router** para navegação SPA.
* **Webpack** para bundling e build.
* **AdminLTE** para layout e componentes visuais.

## 🚀 Como Executar o Projeto

### Pré-requisitos

* Node.js (versão 14 ou superior)
* MongoDB em execução local ou em nuvem

### Passo a passo

1. **Clone o repositório:**

   ```bash
   git clone https://github.com/gabriel-saraiva-flooxai/my-money-app.git
   cd my-money-app
   ```

2. **Instale as dependências do backend:**

   ```bash
   cd backend
   npm install
   ```

3. **Inicie o servidor backend:**

   ```bash
   npm run dev
   ```

   O backend estará disponível em `http://localhost:3003`.

4. **Instale as dependências do frontend:**

   Em outro terminal:

   ```bash
   cd frontend
   npm install
   ```

5. **Inicie o frontend:**

   ```bash
   npm run dev
   ```

   O frontend estará disponível em `http://localhost:8080`.

> ⚠️ **Importante:** Certifique-se de que o backend esteja em execução antes de iniciar o frontend, pois a aplicação depende das APIs para funcionar corretamente.

## 🛠️ Branches Disponíveis

* **main**: Versão original do projeto, conforme desenvolvido durante o curso.
* **update-dependencies**: Branch criada para atualizar bibliotecas e dependências. Pode conter melhorias e correções em relação à versão original.

Para utilizar a branch atualizada:

```bash
git checkout update-dependencies
```

## 🧪 Testando a Aplicação

1. Acesse `http://localhost:8080` no seu navegador.
2. Cadastre um novo usuário ou utilize um existente.
3. Navegue entre as abas de Dashboard e Ciclos de Pagamento.
4. Adicione, edite, clone ou remova créditos e débitos conforme necessário.
5. Observe o resumo financeiro sendo atualizado em tempo real.

---

Espero que esta documentação seja útil para você e para qualquer pessoa que deseje testar ou contribuir com o projeto. Se precisar de mais alguma coisa, estou à disposição!
