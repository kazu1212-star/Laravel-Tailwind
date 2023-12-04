# laravel-tailwind-css

git clone https://github.com/kazu1212-star/laravel-tailwind-css

cd laravel-tailwind-css

cp .env{.example,}

composer install


sail up -d

sail npm install

php artisan key:generate

sail npm run build

sail npm run dev

http://localhost をリロードしてフォームが正しく表示されていれば OK
<img width="600" alt="スクリーンショット 2023-12-04 18 16 28" src="https://github.com/kazu1212-star/laravel-tailwind-css/assets/115007915/1d6a8fc2-eea4-45ae-9df2-c958ca4618a2">
tailwind cssを使いたいファイルで冒頭に
@extends('layouts.app') を記述すれば使えます。


