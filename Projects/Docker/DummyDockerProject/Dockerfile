# syntax=docker/dockerfile:1

FROM node:alpine3.14

WORKDIR /code

COPY package.json .

RUN  npm install

COPY . .

CMD ["npm", "start"]
