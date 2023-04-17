FROM node:13.12-alpine 

RUN mkdir /app

WORKDIR /app

COPY . /app/


RUN npm install


COPY . /app/

RUN npm build

CMD [ "npm", "start" ]