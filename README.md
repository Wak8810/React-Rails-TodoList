# React-Rails-TodoList

React + Ruby on Railsで作成されたTodoリストアプリケーション

## プロジェクト構成

```
root/
├── backend/           # Ruby on Railsバックエンド
├── frontend/          # Reactフロントエンド
```

## ローカル環境でのセットアップ

### 1. バックエンド (Ruby on Rails)

```bash
# バックエンドのディレクトリに移動
cd backend

# 依存関係をインストール
bundle install

# データベースをセットアップ
rails db:migrate

# Railsサーバーを起動 (http://localhost:3000)
rails s
```

### 2. フロントエンド (React)

新しいターミナルを開いて、以下のコマンドを実行します。

```bash
# フロントエンドのディレクトリに移動
cd frontend

# 依存関係をインストール
npm install

# 開発サーバーを起動 (http://localhost:5173)
npm run dev
```

両方のサーバーが起動したら、ブラウザで `http://localhost:5173` にアクセスすると確認できます。