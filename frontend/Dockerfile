FROM node:latest AS build

WORKDIR /build

COPY package.json .

RUN npm install

COPY . .

EXPOSE 3000