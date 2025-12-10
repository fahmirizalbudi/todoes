<p align="center">
  <img src="https://github.com/fahmirizalbudi/todoes/blob/main/todoes_logo_compress.png" alt="Todoes Logo" width="300"/>
</p>

<br/>

# ✅ Todoes

Todoes – A simple REST API for managing todo lists.

---

## 🛠️ Tech Stack

- Laravel
- MySQL

---

## ⚙️ Instalation

1. Clone repository:
   ```bash
   git clone https://github.com/fahmirizalbudi/todoes.git
   cd todoes
   ```

3. Install dependency:
   ```bash
   composer install
   cp .env.example .env
   php artisan key:generate
   ```

4. Migrate DB & Run API:
   ```bash
   php artisan migrate
   php artisan serve
   ```

---

## 🔗 Endpoint

| Method | Endpoint                    | Description             |
|--------|-----------------------------|-------------------------|
| GET    | `/api/v1/todoes`                | Get all todo items       |
| GET    | `/api/v1/todoes/{id}`                | Get a single todo item by ID       |
| POST    | `/api/v1/todoes`                | Create a new todo item       |
| PUT    | `/api/v1/todoes/{id}`                | Update an existing todo item (replace all fields)      |
| DELETE    | `/api/v1/todoes/{id}`                | Delete a todo item by ID       |
| PATCH    | `/api/v1/todoes/mark-is-complete/{id}`                | Mark a todo item as complete       |
| PATCH    | `/api/v1/todoes/mark-is-uncompleted/{id}`                | Mark a todo item as uncompleted       |
| SEARCH    | `/api/v1/todoes/search/{params}`                | Search todo items based on parameters       |

---

## 🎯 Purpose

This project was built to practice building RESTful APIs using Laravel, and MySQL.
