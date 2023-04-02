FROM node:13-alpine

RUN mkdir /app

WORKDIR /app

COPY package.json /app/
COPY package-lock.json /app/
COPY server.js /app/

RUN npm install

COPY . /app/

CMD [ "npm", "start" ]