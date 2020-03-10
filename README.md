# laravel-template
Laravel開発環境をサクッと構築できます！


# 始め方
1.このリポジトリをクローンもしくはダウンロードしてください。

2.`php-sandbox`ディレクトリで以下のコマンドを入力してください。
  ```
$ docker-compose up -d
  ```
  
3.`http://localhost`を開いてLaravelのホーム画面が表示されていれば成功です！

止めたい時は以下のコマンドを入力してください。
```
$  docker stop $(docker ps -q) 
```
---
もし、`composer-setup.php`で失敗したら以下のURLページを参照し、
`Dockerfile`中の`composer-setup.php`のハッシュ値を差し替えてください。
https://getcomposer.org/download/
---