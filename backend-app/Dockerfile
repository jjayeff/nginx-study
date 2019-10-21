FROM node:8-slim

RUN npm install pm2 -g

WORKDIR /usr/src/app

ADD . /usr/src/app

RUN npm install

EXPOSE 4000

CMD ["pm2-runtime", "server.js"]