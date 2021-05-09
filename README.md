# laravel-login2
①Docker環境の構築

├── backend # Laravelプロジェクトのルートディレクトリ
├── infra
│     └── docker
│          ├── apache
│          │   └── httpd.conf
│          ├── mysql
│          │   ├── Dockerfile
│          │   └── my.cnf
│          └── php
│              ├── Dockerfile
│              └── php.ini
├── .env.example
├── Makefile
└── docker-compose.yml

②Databaseの接続
<img width="941" alt="スクリーンショット 2021-05-09 15 54 37" src="https://user-images.githubusercontent.com/82421244/117563167-0ef40200-b0df-11eb-97af-03f4ad957fd2.png">

Dbeverでの接続
※Userの編集は後ほど行う