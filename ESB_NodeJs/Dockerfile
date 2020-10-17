FROM node:current-slim

WORKDIR /usr/src/app

COPY package.json .

RUN npm install

RUN npm install --save express

EXPOSE 3000

CMD ["npm","run","start"]
