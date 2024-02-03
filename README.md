# Laravel + Vue.js 3 + Vite Starter Kit

This is a starter kit that combines Laravel, Vue.js 3, and Vite for a modern web development stack.

## Features

- Laravel as the backend framework.
- Vue.js 3 for building reactive user interfaces.
- Vite for fast and efficient frontend development.
- Easily customizable and extendable structure.

### Prerequisites

Make sure you have the following installed on your machine:

- [PHP](https://www.php.net/downloads.php)
- [Composer](https://getcomposer.org/download/)
- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/get-npm)

### Installation

1. Clone the repository:

  
   ## git clone https://github.com/your-username/laravel-vue-vite-starter.git
  

2. Change into the project directory:

  
   ## cd laravel-vue-vite-starter
  

3. Install PHP dependencies:
   
   ## composer install

5. Install Node.js dependencies:

  
   ## npm install
 

6. Copy the \`.env.example\` file to \`.env\` and configure your database settings.

7. Generate the Laravel application key:

   ## php artisan key:generate
 

8. Run migrations to create the database tables:

   ## php artisan migrate


9. Start the Laravel development server:
 
   ## php artisan serve

10. In a separate terminal, start the Vite development server:

   ## npm run dev


11. Visit \`http://localhost:8000\` in your browser to see the application.

## Usage

- Update the Vue components in the \`resources/js/components\` directory.
- Add new routes in the \`routes/web.php\` file for Laravel.
- Customize the styles in the \`resources/css\` directory.
- Extend and modify the project structure to fit your needs.


