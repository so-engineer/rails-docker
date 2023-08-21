# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

## 簡易的にタスクを管理できるWebアプリ
### 環境構築方法
1\. リポジトリrails-dockerを以下コマンドよりローカルにcloneする
- `git clone https://github.com/sousou1216/rails-docker.git`<br>
2\. 以下サイトよりDockerのインストールを行う（インストール済みの方はスキップ）
- ` https://docs.docker.com/engine/install/ `<br>
3\. 以下コマンドよりコンテナを作成・起動する
- `docker-compose up -d`<br>
4\. ブラウザ上で以下URLを打ち込みアプリが起動していることを確認する
- `http://localhost:3000/`<br>
5\. 以下コマンドよりコンテナを終了する
- `docker-compose stop`<br>
6\. コンテナを再起動する場合は3のupコマンドを実行する
7\. タスクを初期化したい場合は以下コマンドよりコンテナを削除後3のupコマンドを実行する
- `docker-compose down`<br>

### 以下参考
* Ruby version
- latest
* System dependencies
- Ruby, Rails, Postgres, Docker are interdependent.
* Configuration
- Ruby, Rails, Postgres, Docker
* Database creation
- Yes
* Database initialization
- If you delete the container, the database will be initialized.
* How to run the test suite
- N/A
* Services (job queues, cache servers, search engines, etc.)
- Web application for task management.
* Deployment instructions
- See above(環境構築方法).
