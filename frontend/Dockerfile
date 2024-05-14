# node.jsのバージョン指定
FROM node:18.16.1-alpine
# 作業ディレクトリ変更
WORKDIR /src/app
# ホストのpackage.jsonをコンテナにコピー
COPY ./package.json ./
# コンテナに必要なパッケージをインストール
RUN npm install
