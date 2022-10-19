FROM node:19-alpine

WORKDIR /app

COPY package.json package-lock.json ./

RUN npm install

COPY . .