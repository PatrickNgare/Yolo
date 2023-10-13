FROM node:16-alpine3.11


WORKDIR /app

COPY package*.json ./

RUN npm ci

RUN npm install -g npm@16.0.0

COPY . .

EXPOSE 3000

CMD [ "npm", "start"]