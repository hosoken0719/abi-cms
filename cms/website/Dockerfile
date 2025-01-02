# ベースイメージ: Node.js（バージョンは適宜指定）
FROM node:18

# 作業ディレクトリを設定
WORKDIR /app

# パッケージファイルをコピー
COPY package.json package-lock.json ./

# 依存関係をインストール
RUN npm install


# # Next.jsの開発サーバを起動するポートを指定
# EXPOSE 3000

# # 開発サーバの起動コマンド
# CMD ["npm", "run", "dev"]