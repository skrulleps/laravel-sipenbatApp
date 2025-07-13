# Laravel Penjualan Obat (sipenbat-app)

This is a Laravel 12 application with a Vue 3 frontend using Inertia.js. The project is a skeleton starter kit for building modern single-page applications (SPA) with Laravel as the backend API and Vue 3 as the frontend framework. It includes authentication, user settings, and a dashboard.

## Features

- Laravel 12 backend with PHP 8.2
- Vue 3 frontend with Inertia.js and Vite
- Tailwind CSS for styling
- Authentication system with registration, login, password reset, and email verification
- User settings management (profile, password, appearance)
- Dashboard and welcome pages
- Testing with Pest PHP

## Requirements

- PHP 8.2 or higher
- Composer
- Node.js and npm
- MySQL or other supported database

## Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd sipenbat-app
   ```

2. Install PHP dependencies:

   ```bash
   composer install
   ```

3. Install Node.js dependencies:

   ```bash
   npm install
   ```

4. Copy the example environment file and configure your environment variables:

   ```bash
   cp .env.example .env
   ```

5. Generate the application key:

   ```bash
   php artisan key:generate
   ```

6. Run database migrations:

   ```bash
   php artisan migrate
   ```

7. (Optional) Seed the database:

   ```bash
   php artisan db:seed
   ```

## Running the Application

### Development Server

To start the Laravel development server, queue listener, and Vite development server concurrently, run:

```bash
composer run dev
```

This will start:

- Laravel backend server at http://localhost:8000
- Queue listener for background jobs
- Vite development server for frontend assets

### Production Build

To build the frontend assets for production, run:

```bash
npm run build
```

## Testing

Run the automated tests using Pest:

```bash
composer test
```

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## License

This project is open source and available under the MIT License.
