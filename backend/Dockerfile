FROM node:13-alpine

RUN mkdir /app

WORKDIR /app

COPY . /app/


RUN npm install

COPY . /app/

CMD [ "npm", "start" ]