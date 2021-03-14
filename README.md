# Meets Suggests & Abilities
- [Description](#description)<br>
- [Purpose](#purpose)<br>
- [Features](#features)<br>
- [Requirement](#requirement)<br>
- [Diagram](#diagram)<br>
- [URL](#url)<br>


## Description
企業のためのソーシャルワークツール

## Purpose
- 大・中小企業、個人事業主、フリーランスなどあらゆる事業形態の企業・個人が、<br>
互いの分野・スキルを生かした提案やプロジェクトを共有し自由に参加できる機会を提供する
<br>

- 複数企業がコラボレーションすることで新しいビジネスを創造する
- コロナ禍で苦境に立たされている業種を支援する
- 個人や小規模な企業が持つ技術を発信し広める機会を作る	

## Features

#### ユーザー登録

- プロフィール掲載機能 
  - プロフィール画像を登録できる
- 登録内容の編集・削除機能
- ログイン、ログアウト機能

#### 新規提案・プロジェクト
- 一覧表示機能
  - ページネーション機能
  - カテゴリ別検索機能
  - タグ検索機能
- 投稿機能
- 詳細表示機能
- 編集・削除機能
  - 管理者のみ実行可能

#### コメント機能
-  投稿・一覧表示機能
   - Ajaxを利用した非同期通信で表示される
-  編集・削除機能
   - 投稿者は編集、管理者は削除が可能

#### 企業登録
- プロフィール掲載機能 
  - 企業、個人事業のプロフィールを登録できる
  - プロフィール画像を登録できる
- プロフィール編集機能

#### メッセージ(チャット)機能
- 投稿機能
  - 提案・プロジェクトに参加中の企業担当者同士でやりとりができる
  - ActionCableを使用した非同期通信で実装

#### お問い合わせ機能
- 通知メール送信機能
  - 問い合わせをしたユーザーと管理者へ通知メールが届く


## Requirement
- Ruby 　2.6.5 <br>
- Rails 　5.2.4<br>
- Postgresql<br>
- AWS S3<br>
#### 開発環境<br>
- Docker<br>
- CircleCI<br>
- RSpec<br>
#### 本番環境<br>
- AWS VPC<br>
- AWS EC2<br>
- Unicorn<br>
- Nginx<br>

## Diagram

#### カタログ設計
https://docs.google.com/spreadsheets/d/1QarMazm0V8BS-qANOKpb1HXgNEDyPufsvOfpb9NfRE4/edit?usp=sharing

#### 画面遷移図
https://docs.google.com/spreadsheets/d/1lzj2cUPg4r8MVvH0KEybdCnciPl06OOMxmE3O4-UG28/edit?usp=sharing


## URL
[http://35.72.239.105/](http://35.72.239.105/)
## Usage

#### 利用者

- [ユーザー登録]()をする
  - ログインする
  - 提案・プロジェクトの一覧・詳細を閲覧できる
  - 提案・プロジェクトのコメントを閲覧できる
  
- [企業登録]()をする
  - 提案やプロジェクトの投稿ができる
  - 提案・プロジェクトの内容変更等、サービスの管理者に対して[問い合わせ]()が出来る
  - 他ユーザーの提案・プロジェクトに対してコメントすることが出来る
  - 提案・プロジェクト詳細画面に表示される参加ボタンから提案・プロジェクトへ参加できる
  - 参加中の提案・プロジェクト投稿者とのチャットルームを開設できる
  - 参加中のプロジェクトを一覧表示できる

## Author
