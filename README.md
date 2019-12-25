# README

# ハットリ(服部)

## 概要
画像と文章を投稿するサービス
お気に入りとコメントを入れることができます。

## コンセプト
服のこだわり投稿

## バージョン
Ruby 2.5.1
Rails 5.2.1

## 機能一覧
- [ ] ログイン機能
- [ ] ユーザー登録機能
  - [ ] メールアドレス、名前、パスワードは必須
- [ ] パスワード再設定機能
- [ ] 投稿一覧表示機能
  - [ ] コメント数を表示
  - [ ] お気に入り数を表示
- [ ] 画像投稿機能
  - [ ] タイトルと画像は必須
- [ ] 画像編集機能
- [ ] 画像削除機能
  - [ ] 画像編集と画像削除は投稿者のみ実行可能
- [ ] 画像お気に入り機能
  - [ ] 画像のお気に入りについては1つの画像に対して1人1回しかできない
- [ ] コメント投稿機能
- [ ] コメント削除機能
- [ ] コメント編集機能
  - [ ] コメント編集とコメント削除はコメントした本人のみ可能
- [ ] コメント機能とお気に入り機能についてはページ遷移なしで実行できる

## カタログ設計
https://docs.google.com/spreadsheets/d/11yeZE9p2WrfmoOQvF2kd0SxwdWTexdMxNjUP5ParX70/edit#gid=0

## テーブル定義
https://docs.google.com/spreadsheets/d/1KkQf2l4ky6N0pIOu1htf4Zld8IJmiFoC3MOc5lzhtqg/edit#gid=0

## 画面遷移図
https://www.lucidchart.com/documents/edit/dcc0746d-d903-4bf3-b90f-6328bf1944c9/0_0?beaconFlowId=8BA3E60C8C2C631C

## ER図
https://www.lucidchart.com/documents/edit/bf847913-c823-4568-84a1-33f07732d166/0_0?beaconFlowId=7ECECB558420DE4B

## 画面ワイヤーフレーム
https://cacoo.com/diagrams/0MyG8hDx6wAXAm19/F65C6?reload_rt=1577276222533_0

## 使用予定Gem
* carrier wave
* ransack
* rspec-rails
* factory_bot_rails
* kaminari
* ransack
* devise