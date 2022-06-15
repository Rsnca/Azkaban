## Docker環境でAzkabanを起動してみる。

### 事前準備
今回は[haxqer](https://github.com/haxqer/azkaban)という方のimageを使用させてもらう。
1. ディレクトリ内にymlファイルなどを配置して、コンテナを起動する。
```
$ git clone https://github.com/haxqer/azkaban.git
$ cd azkaban
$ docker-compose up -d
```
2. Azkabanを起動する
- `http://localhost:8081`　にアクセスする。
- ログインID：azkaban
- パスワード：azkaban

<img src="../images/login.png" width="500" height="300">

- home画面にログインし、起動成功<br>

<img src="../images/home.png" width="500" height="300">