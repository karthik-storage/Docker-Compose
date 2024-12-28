FROM node:10-alpine

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install

COPY . .

ENV NUXT_HOST=0.0.0.0

EXPOSE 3001

CMD ["node", "server.js"]
