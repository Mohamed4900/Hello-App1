FROM node:lts-alpine

RUN mkdir /client
WORKDIR /client
COPY package*.json ./
RUN npm i
COPY src src
COPY public public

EXPOSE 3000

CMD npm start
