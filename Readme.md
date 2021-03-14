# 手順
プロジェクトの作成~起動確認までの手順です。

## 以下のコマンドを実行 
`docker-compose run nodejs npx create-next-app YourAppName`
(YourAppName: 任意の名前)
create-next-appはプロジェクト作成のため一度しか行わない。したがって、Dockerfileではなくコマンドを実行する。

## コンテナ立ち上げ、起動
`docker-compose up`