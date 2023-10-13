FROM node:16-alpine3.11


WORKDIR /app
 
COPY package*.json ./

RUN npm ci

RUN npm install -g npm@6.14.5

COPY . .

EXPOSE 3000

CMD [ "npm", "start"]