# 🧠 Memoteca — Angular e API REST

Aplicação Web desenvolvida com **Angular** para gerenciamento de pensamentos, integrada a uma **API REST** para persistência e manipulação dos dados.

O projeto implementa operações completas de **CRUD**, permitindo cadastrar, consultar, editar e excluir pensamentos, aplicando conceitos fundamentais do desenvolvimento de aplicações Angular.

🚀 **[Acessar o projeto](https://memoteca-gamma.vercel.app/listarPensamento)**

<img width="1002" height="541" alt="Memoteca" src="https://github.com/user-attachments/assets/bdc4747d-00d8-4fe2-997b-01f3275c31d0" />

---

## 🎯 Objetivo

Desenvolver uma aplicação Web utilizando **Angular**, aplicando conceitos de:

* Componentização
* Diretivas
* Formulários
* Rotas
* Serviços
* Comunicação HTTP
* Integração com API REST
* Operações CRUD

O projeto foi desenvolvido a partir do curso **Angular 14 — Aplique os conceitos e desenvolva seu primeiro CRUD**, utilizando o Angular CLI para criação e gerenciamento da aplicação.

---

## 🧪 Funcionalidades

* ➕ **Cadastro** de pensamentos
* 🔎 **Consulta** de pensamentos
* ✏️ **Edição** de pensamentos
* 🗑️ **Exclusão** de pensamentos

---

## 🛠️ Tecnologias e ferramentas

| Tecnologia/Ferramenta | Utilização                                    |
| --------------------- | --------------------------------------------- |
| **Angular 14**        | Desenvolvimento da aplicação Web              |
| **TypeScript**        | Desenvolvimento da aplicação                  |
| **HTML5 / CSS3**      | Estrutura e estilização da interface          |
| **API REST**          | Comunicação e persistência dos dados          |
| **Node.js**           | Ambiente de execução                          |
| **npm**               | Gerenciamento de dependências                 |
| **Angular CLI**       | Criação, execução, geração e build do projeto |

---

## 🏗️ Arquitetura e organização

A aplicação utiliza a estrutura baseada em componentes do Angular, promovendo a separação das responsabilidades e facilitando a manutenção do código.

Os principais conceitos aplicados incluem:

* **Componentes** para construção da interface;
* **Serviços** para centralização da comunicação com a API;
* **Rotas** para navegação entre as funcionalidades;
* **Formulários** para entrada e validação de dados;
* **Diretivas** para controle e comportamento dos elementos da interface;
* **HTTP Client** para comunicação com a API REST.

---

## 🔗 Comunicação com a API REST

O gerenciamento dos pensamentos é realizado por meio de requisições HTTP:

| Método         | Operação                   |
| -------------- | -------------------------- |
| 🔎 **GET**     | Consulta dos pensamentos   |
| ➕ **POST**     | Cadastro de pensamentos    |
| ✏️ **PUT**     | Atualização de pensamentos |
| 🗑️ **DELETE** | Exclusão de pensamentos    |

---

## 📂 Estrutura do projeto

A estrutura segue a organização padrão de uma aplicação Angular, utilizando componentes, serviços, rotas e demais recursos disponibilizados pelo framework.

O Angular CLI permite também a criação de novos elementos utilizando comandos como:

```bash
ng generate component component-name
```

Outros elementos podem ser gerados através do comando:

```bash
ng generate directive|pipe|service|class|guard|interface|enum|module
```

* 🔨 Construir

Execute o comando ng build para compilar o projeto.

Os artefatos da compilação serão armazenados no diretório dist/.

ng build

* 🧪 Executando testes unitários

Execute o comando ng test para executar os testes unitários utilizando Karma.

ng test

Os testes unitários permitem validar o comportamento dos componentes e funcionalidades da aplicação.

* 🔄 Executando testes de ponta a ponta

Execute o comando ng e2e para realizar os testes de ponta a ponta na plataforma de sua escolha.

Para utilizar este comando, é necessário primeiro adicionar ao projeto um pacote que implemente recursos de testes de ponta a ponta.

ng e2e

---

## ▶️ Como executar o projeto

### 1. Pré-requisitos

Antes de executar o projeto, tenha instalado:

* **Node.js**
* **npm**
* **Angular CLI**
* **Visual Studio Code** ou outra IDE de sua preferência

### 2. Clonar o repositório

```bash
git clone <URL_DO_REPOSITORIO>
```

### 3. Acessar a pasta do projeto

```bash
cd memoteca
```

### 4. Instalar as dependências

```bash
npm install
```

### 5. Iniciar o servidor de desenvolvimento

```bash
ng serve
```

A aplicação ficará disponível em:

```text
http://localhost:4200/
```

O Angular atualizará automaticamente a aplicação quando alterações forem realizadas nos arquivos do projeto.

---

## 🏗️ Build

Para gerar a versão de produção:

```bash
ng build
```

Os arquivos gerados serão armazenados no diretório:

```text
dist/
```

---

## 🧪 Testes

Para executar os testes unitários:

```bash
ng test
```

Os testes são executados utilizando a estrutura de testes configurada no projeto.

Para testes **end-to-end**, o Angular permite utilizar plataformas específicas de automação. É necessário adicionar ao projeto um pacote que forneça essa capacidade antes de executar esse tipo de teste.

---

## 🎯 Competências demonstradas

* Angular 14
* TypeScript
* Desenvolvimento Web
* Componentização
* Diretivas
* Formulários
* Rotas
* Serviços
* HTTP Client
* API REST
* CRUD
* Integração Front-end / Back-end
* Node.js / npm
* Angular CLI
* Testes unitários

---

## 💼 Sobre o projeto

Projeto desenvolvido para compor meu portfólio de **Desenvolvimento de Software**, demonstrando a aplicação prática dos principais conceitos do **Angular** na construção de uma aplicação Web integrada a uma **API REST**.

A implementação contempla a criação de componentes, utilização de formulários e rotas, organização através de serviços e comunicação HTTP para realização das operações de **cadastro, consulta, atualização e exclusão de dados**.

O projeto também representa uma etapa prática de aprofundamento em **desenvolvimento Front-end com Angular**, contribuindo para a construção de aplicações estruturadas, componentizadas e integradas a serviços REST.
