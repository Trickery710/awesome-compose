FROM node:18.1-alpine3.14

WORKDIR /usr/src/app

COPY package.json package-lock.json ./
RUN npm ci
COPY ./server.js ./

CMD ["npm","start"]
