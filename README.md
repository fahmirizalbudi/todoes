<div align="center">
<a href="https://github.com/fahmirizalbudi/todoes" target="blank">
<img src="https://raw.githubusercontent.com/JjagoKoding/icon/ffdf2d7026f078d651fe76dc56b706c743b9c9e4/todoes.svg" width="300" alt="Logo" />
</a>

<br />
<br />

![](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![](https://img.shields.io/badge/Sanctum-20CDEF?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)

</div>

<br/>

## Todoes

Todoes is a simple REST API for managing todo lists. Built in Laravel and Sanctum. This project uses MySQL as the database. Key features include:

## Features

- **Unlimited Requests:** Handle unlimited API requests without restrictions.
- **CRUD Operations:** Create, Read, Update, and Delete todo items efficiently.

## Tech Stack

- **Laravel**: A PHP web application framework with expressive, elegant syntax.
- **Laravel Sanctum**: A featherweight authentication system for APIs.
- **MySQL**: Open-source relational database management system.
- **PHP**: A popular general-purpose scripting language that is especially suited to web development.

## Getting Started

To get a local copy of this project up and running, follow these steps.

### Prerequisites

- **PHP** (v8.2 or higher).
- **Composer** (Dependency Manager).
- **MySQL** (Database server).

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/fahmirizalbudi/todoes.git
   cd todoes
   ```

2. **Install dependencies:**

   ```bash
   composer install
   cp .env .env.example
   php artisan key:generate
   ```

3. **Run migration:**

   ```bash
   php artisan migrate
   ```

4. **Start the development server:**

   ```bash
   php artisan serve
   ```

## Usage

### Running the Application

- **Api development:** `php artisan serve`.

> Open [http://localhost:8000](http://localhost:8000) to test it on Postman.

## License

All rights reserved. This project is for educational purposes only and cannot be used or distributed without permission.
