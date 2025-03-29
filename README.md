# Laravel 11 + React SPA Project

A full-stack project management application built with Laravel 11 and React, designed for efficient task and project tracking.

## Features

- User authentication (Registration & Login)
- Project management (Create, Read, Update, Delete)
- Task management with sorting, filtering, and pagination
- Assign users to tasks for better collaboration
- Dashboard overview for quick insights
- Role-based access control for better security

## Installation Guide

### Prerequisites:

- PHP 8.2+
- Composer
- Node.js & npm
- A database (SQLite, MySQL, or PostgreSQL)

### Steps:

1. **Clone the repository**
   ```sh
   git clone https://github.com/your-repo.git
   cd your-repo
   ```
2. **Copy environment file**
   ```sh
   cp .env.example .env
   ```
3. **Install backend dependencies**
   ```sh
   composer install
   ```
4. **Install frontend dependencies**
   ```sh
   npm install
   ```
5. **Generate application key**
   ```sh
   php artisan key:generate --ansi
   ```
6. **Run migrations and seed data**
   ```sh
   php artisan migrate --seed
   ```
7. **Build front-end assets**
   ```sh
   npm run build
   ```
8. **Start the application**
   ```sh
   php artisan serve
   ```
   (For Vite development mode, run `npm run dev` in a separate terminal)

## Usage

Once the application is running, visit `http://127.0.0.1:8000` to access the system. Login or register to start managing projects and tasks.

## Demo

Coming soon...

## License
This project is open-source and available under the [MIT License](https://opensource.org/licenses/MIT).  
You can check the repository here: [Your Repository URL](https://github.com/chelle98327/laravel-react-inertia)

