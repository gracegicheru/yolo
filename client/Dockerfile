FROM node:13.12-alpine AS builder

RUN mkdir client

WORKDIR /client
COPY package.json /client/
COPY package-lock.json /client/

COPY . /client/

RUN chmod +x /client/

RUN npm install


CMD [ "npm", "start" ]