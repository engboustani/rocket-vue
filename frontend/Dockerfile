FROM node:lts-alpine

WORKDIR /usr/src/app

COPY ./template ./

RUN npm install
RUN npm run dev

EXPOSE 8080
