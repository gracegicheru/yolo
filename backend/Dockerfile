FROM node:13.12-alpine AS builder

RUN mkdir /app

WORKDIR /app

COPY . /app/


RUN npm install


COPY . /app/

RUN npm build

CMD [ "npm", "start" ]