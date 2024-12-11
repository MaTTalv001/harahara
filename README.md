# Rails Application Template

## 概要

このリポジトリは、Rails 7 系のアプリケーションテンプレートです。

以下の設定が済んだ状態で開発をスタートできます：

- Rails 7.2.1
- TailwindCSS
- DaisyUI
- Postgres
- Docker 開発環境

## 機能

- 静的なトップページ
- 共通ヘッダーのパーシャル
- TailwindCSS + DaisyUI によるスタイリング

## 開発環境のセットアップ

### 必要な環境

- Docker
- Docker Compose

### インストール手順

1. リポジトリのクローン

```bash
git clone https://github.com/MaTTalv001/Rails_DaisyUI_Postgres_Template.git
cd Rails_DaisyUI_Postgres_Template
```

2. Docker コンテナの起動

```bash
docker compose up --build
```

3. アプリケーションへのアクセス
   ブラウザで http://localhost:3000 にアクセス

## 技術スタック

- Ruby 3.2.0
- Rails 7.2.1
- PostgreSQL 15
- TailwindCSS 3.4
- DaisyUI 4.12
- esbuild
- Docker/Docker Compose

## プロジェクト構造

主要なファイルとディレクトリ：

```
.
├── app/
│   ├── views/
│   │   ├── layouts/
│   │   │   └── _header.html.erb  # 共通ヘッダー
│   │   └── static_pages/
│   │       └── top.html.erb    # トップページ
│   └── assets/
│       └── stylesheets/
│           └── application.tailwind.css
├── docker-compose.yml
├── Dockerfile
└── Procfile
```
