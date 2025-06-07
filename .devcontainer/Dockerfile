# ベースイメージ
FROM node:latest

# 作業ディレクトリ作成と所有権設定
RUN mkdir -p /workspace \
    && chown node:node /workspace

# 作業ディレクトリ設定
WORKDIR /workspace
USER node

