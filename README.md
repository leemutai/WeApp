# 🌤️ Weather App — Next.js + Laravel + OpenWeatherMap API

A decoupled weather app built with **Next.js** (frontend) and **Laravel** (API backend). It uses the OpenWeatherMap API to fetch current weather and a 3-day forecast based on the user's city input.

---
🔧 Tech Stack

- **Frontend:** Next.js, TypeScript, Tailwind CSS (RippleUI)
- **Backend:** Laravel 11, RESTful API
- **Weather Provider:** OpenWeatherMap (Geocoding + One Call API)

---

📦 Installation

1. Backend (Laravel)
```bash
cd weather-api
composer install
cp .env.example .env
php artisan key:generate

# Add to .env
OPENWEATHER_API_KEY=your_api_key_here

php artisan serve
