FROM node:18

# 作業ディレクトリを作成
WORKDIR /docs

# アプリケーションのソースコードをコピー
COPY /docs /docs

# CMDを無限ループでコンテナが終了しないように設定
CMD ["tail", "-f", "/dev/null"]
