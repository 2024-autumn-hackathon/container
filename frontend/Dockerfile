# frontend/Dockerfile
FROM node:22.11.0-slim

WORKDIR /app

# Next.jsの依存関係をインストール
COPY --chown=node:node package*.json ./
# RUN npm install

# Next.jsアプリケーションをコピー
# COPY --chown=node:node . .

# 開発モードでNext.jsサーバーを起動（ポート3000）
CMD ["npm", "run", "dev"]
