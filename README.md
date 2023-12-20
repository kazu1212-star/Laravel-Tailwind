# laravel-tailwind-css

git clone https://github.com/kazu1212-star/referral-recruiting

cd referral-recruiting

git remote set-url origin 新規作成したリポジトリurl

cp .env{.example,}

composer install


sail up -d

sail npm install

php artisan key:generate

sail npm run build

sail npm run dev

http://localhost をリロードしてフォームが正しく表示されていれば OK

tailwind cssを使いたいファイルで冒頭に
@extends('layouts.app') を記述すれば使えます。

### Larastan実行
`composer larastan`

### Print実行
`composer print`
