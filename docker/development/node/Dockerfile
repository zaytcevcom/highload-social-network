FROM node:14

WORKDIR /app

COPY package*.json ./

RUN npm install

RUN npm install ws

COPY . .

CMD ["node", "server.js"]

