# Laravel + Vue.js App

This project was created using Laravel as the backend framework and Vue.js for the frontend. The setup includes:

- Laravel application scaffolded in the current directory
- Vue.js preset enabled via Laravel's frontend scaffolding
- Node dependencies installed and assets built using Laravel Mix

## Getting Started

1. **Start the Laravel development server:**
   ```sh
   php artisan serve
   ```
2. **(Optional) Rebuild frontend assets after changes:**
   ```sh
   npm run dev
   ```

## Project Structure
- `resources/js/components` — Vue components
- `routes/web.php` — Web routes
- `app/Http/Controllers` — Laravel controllers

## Authentication
You can enable Laravel Breeze, Jetstream, or Fortify for authentication if needed.

---

For more details, see the [Laravel documentation](https://laravel.com/docs) and [Vue.js documentation](https://vuejs.org/v2/guide/).
