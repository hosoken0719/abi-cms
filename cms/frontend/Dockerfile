# Node.js 18を使用
FROM node:18

# 作業ディレクトリを設定
WORKDIR /app

# package.json と package-lock.json をコンテナにコピー
COPY ./package*.json ./

# 依存関係をインストール
RUN npm install

# ソースコードと public フォルダをコンテナにコピー
# COPY ./src ./src
# COPY ./public ./public
# COPY ./index.html ./

# # Viteでアプリケーションをビルド
# RUN npm run build

# # コンテナ起動時にViteの開発サーバを起動
# CMD ["npm", "run", "dev", "--", "--host"]