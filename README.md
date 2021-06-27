## Laravel Lumen
- This is laravel lumen simple backend Multiple migration database -/Folder

## Note Make Migrate Folder
-  php artisan migrate --path='database/migrations/cms'
-  php artisan migrate --path='database/migrations/account'
-  php artisan migrate --path='database/migrations/estore'

## Note Migrate
- php artisan migrate:fresh --path='database/migrations/cms' --database=fpurnahar_cms
- php artisan migrate:fresh --path='database/migrations/account' --database=fpurnahar_account
- php artisan migrate:fresh --path='database/migrations/estore' --database=fpurnahar_estore

## Runing
- php -S localhost:8080 -t public
