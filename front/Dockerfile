# 開発環境用のDoclerfile
FROM node:12.4.0-alpine
WORKDIR /app
COPY ./front /app/
RUN npm init -y
RUN npm install
EXPOSE 8080
CMD ["npm", "run", "dev"]
