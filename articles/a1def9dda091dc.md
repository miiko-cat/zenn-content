---
title: "SupabaseEdgeFunctions CLI の使い方"
emoji: "⌨️"
type: "tech" # tech: 技術記事 / idea: アイデア
topics: ["Supabase", "EdgeFunctions", "CLI", "DB", "サーバレス関数"]
published: false
---
## なぜEdgeFunctions CLIをまとめようと思ったか
  - 開発中のアプリでSupabase Edge Functionsを使っていて、DBの差分を取ったり、デプロイしたりする方法をいちいち調べながら、実行していた
  - 記事にまとめて、自分や同じように困っている人に役に立てたかった
## CLIインストール方法
## Dockerの準備
## Edge Functionsをローカルで動かして、修正＆デプロイするケース
### Edge Functionsのダウンロードする方法
### 手元で動かす方法
#### アクセストークンが必要になる
### Edge Functionsをデプロイする方法
### --no-verify-JWTの注意点
#### フラグを付けてデプロイするか、config.tomlに設定するか
## サーバのDB定義をローカルDBに反映して、DB定義変更＆デプロイするケース
### ローカルDBに定義を反映する方法
### サーバー上のデータを取得し、ローカルに反映する方法
### DB定義やRLSを変更し、マイグレーションファイルを作成する方法
### サーバへ反映する方法
## アプリ実行時に、ローカルのSupabaseにつなげる方法