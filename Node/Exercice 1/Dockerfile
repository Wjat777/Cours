FROM node:alpine

WORKDIR /usr/app

COPY package*.json ./

RUN yarn cache clean

COPY . .

EXPOSE 3000


