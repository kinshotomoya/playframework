FROM node:12.4.0-alpine
WORKDIR /app
COPY ./front /app/
RUN npm init -y
RUN npm install
RUN npm run build
