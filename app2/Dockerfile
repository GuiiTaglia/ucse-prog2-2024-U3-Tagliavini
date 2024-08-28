# syntax=docker/dockerfile:1

FROM node:14

WORKDIR /app

COPY package.json ./
RUN npm install

COPY . .

EXPOSE 4001

CMD ["npm", "start"]
