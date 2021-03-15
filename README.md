## Setup (lisez bien)

## 1) Clone
-> Open a cmd in a folder 
-> write: git clone https://github.com/hichamlemrabet/laravel_basic_template.git folderClone (name of folder)

## 2) Setup Composer Dependencies 
-> write: cd folderClone
-> write: composer install
-> write: npm install

## 3) Create .env file
-> write: cp .env.example .env (it copies the .env.example file into .env file)

## 4) Generate app encryption key
-> write: php artisan key:generate (it creates an APP_KEY in the .env file created above)

## 5) Setup Database
-> go to the .env file and setup a database (DB_HOST, DB_PORT, DB_DATABASE, DB_USERNAME, DB_PASSWORD)
-> write: php artisan migrate
