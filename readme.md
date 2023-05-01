# ChatGPTによるアプリケーション開発の勉強

## 概要

本記事はDeepLearning.AI提供の[ChatGPT Prompt Engineering for Developers](https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers/)の教材を日本語化(微修正も含む)したものです。

## 題目

以下の内容を含みます

1. Guidelines ChatGPTの使用方法一覧
2. Iterative プロンプトの改善
3. Inferring 文章からの推論
4. Transforming 翻訳\/スペルチェック/文法チェック
5. Expanding 文章の拡大
6. Chatbot ChatGPTを活用して作成する

## 動作の前提条件

- Docker desktopがインストールされており、動作するのが確認できていること
  インストールしていない場合は以下のリンクからダウンロード
  [https://www.docker.com/products/docker-desktop/](https://www.docker.com/products/docker-desktop/)
- ChatGPTのAPIkeyを取得していること
  APIKeyを取得出来ていない場合は、以下の方法でAPIKeyを取得する
  [APIkeyの取得方法](https://auto-worker.com/blog/?p=6988)

## 環境構築

1. notebookディレクトリ内のapikey.jsonに自身のAPIKeyを入力
2. コマンドプロンプトを起動
3. 任意のディレクトリに移動
4. git clone
5. docker-compose up -d --build(3分ぐらいかかります)
6. 任意のブラウザを開く
7. アドレスバーに「localhost:8888」を打ち込む

## 学習の進め方

特にありません。

notebookディレクトリ内にあるファイルから自分が気になる順番で学習を進めてください。
