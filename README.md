# Abaya Store

An open-source e-commerce platform focused on selling beautiful Abayas. Built with Laravel, this project is part of our Open Source Software Development initiative.

## Features
- User registration & login
- Product listing
- Cart and Checkout system
- Admin dashboard (coming soon)
- Mobile-friendly design

## Tech Stack
- PHP (Laravel Framework)
- MySQL
- Blade Templates
- Bootstrap / Tailwind CSS
- Git & GitHub

## Getting Started

### Prerequisites
- PHP >= 8.0
- Composer
- MySQL
- Git
- Node.js & npm

### Installation Steps
```bash
git clone https://github.com/your-username/abaya_store.git
cd abaya_store
cp .env.example .env
composer install
php artisan key:generate
php artisan migrate
php artisan serve