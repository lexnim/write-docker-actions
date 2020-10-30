FROM node:slim

COPY package*.json ./

RUN npm install -g npm@7.0.7

RUN npm install

COPY . .

CMD [ "node", "/src/index.js" ]
