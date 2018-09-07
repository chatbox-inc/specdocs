# Laravel + Nuxt.js

## セットアップ

```
$ composer install
$ npm install
```

.envの作成
```
$ cp .env.example .env
```
Application keyの作成
```
$ php artisan key:generate
```
ビルドインサーバーの起動 ( http://localhost:8000 に接続)
```
$ php artisan serve  
```

フロントエンドのコンパイル
```
$ npm run dev
```

http://localhost:3000 に接続
