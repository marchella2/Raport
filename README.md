## Setup

1. Clone this project `https://github.com/ridwanpratama/Raport.git`
2. Go to project folder & open in code editor
3. Run `composer install`
4. Create `.env` file with command `cp .env.example .env`
5. Generate key inside `.env` file by `php artisan key:generate`
6. Start your XAMPP (Apache & Mysql) service
7. Open `.env` and edit database config
8. Run migration using `php artisan migrate` command
9. Run `npm install -g pnpm`
10. Run  `pnpm install && pnpm dev`
11. Seed database using `php artisan db:seed`
12. Run project with command `php artisan serve`
13. In production don't forget to change `APP_DEBUG` in .env to `false`
