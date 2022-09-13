FROM node:18.1.0-alpine3.14

WORKDIR /usr/src/app/client

COPY package*.json ./

RUN npm install

EXPOSE 3000

CMD ["npx", "next", "dev"]