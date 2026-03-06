# SmartWallet

![Laravel](https://img.shields.io/badge/Laravel-12-red)
![PHP](https://img.shields.io/badge/PHP-8.3-blue)
![Vue](https://img.shields.io/badge/Vue-3-green)
![Inertia](https://img.shields.io/badge/Inertia.js-SPA-purple)
![License](https://img.shields.io/badge/license-MIT-lightgrey)

> Personal finance dashboard built with Laravel, Vue and Chart.js.

---

# 🇧🇷 Português

## Sobre o Projeto

**SmartWallet** é uma aplicação web de **gestão financeira pessoal** que permite aos usuários registrar receitas, despesas e visualizar sua situação financeira através de **gráficos e dashboards interativos**.

O objetivo do projeto é fornecer uma ferramenta simples para controle financeiro enquanto aplica **boas práticas de desenvolvimento full stack com PHP e também conta com consumo de API**.

---

## Preview da Aplicação

<img src="docs/dashboard.png" width="800">

*(em construção...)*

---

## Tecnologias Utilizadas

### Backend
- PHP
- Laravel

### Frontend
- Inertia.js
- Vue.js
- TailwindCSS

### Banco de Dados
- MySQL

### Visualização de Dados
- Chart.js

---

## Arquitetura da Aplicação

A aplicação segue o padrão **MVC (Model-View-Controller)** utilizando Laravel.

```
app/
 ├── Models
 ├── Http
 │   ├── Controllers
 │   └── Requests
 ├── Services
 └── Policies

resources/
 ├── js
 │   ├── Pages
 │   ├── Components
 │   └── Layouts
 └── css

routes/
 ├── web.php
 └── auth.php
```

---

## Funcionalidades

- Cadastro e autenticação de usuários
- Registro de receitas
- Registro de despesas
- Dashboard financeiro
- Visualização de gráficos
- Histórico de transações
- Filtro por datas

---

## Dashboard

O dashboard apresentará:

- Saldo atual
- Total de receitas
- Total de despesas
- Gráfico de despesas por categoria
- Evolução financeira ao longo do tempo

Os gráficos serão construídos com **Chart.js**.

---

## Instalação

Clone o repositório

```bash
git clone git@github.com:seu-usuario/smartwallet.git
```

Entre na pasta

```bash
cd smartwallet
```

Instale as dependências do backend

```bash
composer install
```

Instale as dependências do frontend

```bash
npm install
```

Crie o arquivo de ambiente

```bash
cp .env.example .env
```

Configure o banco de dados no `.env`.

Execute as migrations

```bash
php artisan migrate
```

Gere a chave da aplicação

```bash
php artisan key:generate
```

Inicie o servidor

```bash
php artisan serve
```

Execute o Vite

```bash
npm run dev
```

---

## Objetivo do Projeto

Este projeto faz parte do meu processo de evolução como **desenvolvedor backend PHP**, aplicando conceitos reais de:

- arquitetura de software
- modelagem de banco de dados
- desenvolvimento full stack
- visualização de dados
- consumo de API

---

# 🇺🇸 English

## About the Project

**SmartWallet** is a **personal finance management web application** that allows users to record income and expenses and visualize their financial situation through **interactive charts and dashboards**.

The goal of the project is to provide a simple financial management tool while applying **full stack development best practices with PHP and also integrating API consumption**.

---

## Application Preview

<img src="docs/dashboard.png" width="800">

*(under construction...)*

---

## Technologies Used

### Backend
- PHP
- Laravel

### Frontend
- Inertia.js
- Vue.js
- TailwindCSS

### Database
- MySQL

### Data Visualization
- Chart.js

---

## Application Architecture

The application follows the **MVC (Model-View-Controller)** pattern using Laravel.

```
app/
 ├── Models
 ├── Http
 │   ├── Controllers
 │   └── Requests
 ├── Services
 └── Policies

resources/
 ├── js
 │   ├── Pages
 │   ├── Components
 │   └── Layouts
 └── css

routes/
 ├── web.php
 └── auth.php
```

---

## Features

- User registration and authentication
- Income tracking
- Expense tracking
- Financial dashboard
- Chart visualization
- Transaction history
- Date filtering

---

## Dashboard

The dashboard will display:

- Current balance
- Total income
- Total expenses
- Expense chart by category
- Financial evolution over time

The charts will be built using **Chart.js**.

---

## Installation

Clone the repository

```bash
git clone git@github.com:your-username/smartwallet.git
```

Enter the project directory

```bash
cd smartwallet
```

Install backend dependencies

```bash
composer install
```

Install frontend dependencies

```bash
npm install
```

Create the environment file

```bash
cp .env.example .env
```

Configure the database in the `.env` file.

Run the migrations

```bash
php artisan migrate
```

Generate the application key

```bash
php artisan key:generate
```

Start the server

```bash
php artisan serve
```

Run Vite

```bash
npm run dev
```

---

## Project Goal

This project is part of my journey to become a **PHP backend developer**, applying real-world concepts such as:

- software architecture
- database modeling
- full stack development
- data visualization
- API consumption

---

This project is open-source and available under the **MIT License**.
