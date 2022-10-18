FROM node:18-slim

RUN ls -ltrh

WORKDIR /user-app

RUN ls -ltrh

COPY package*.json ./

RUN ls -ltrh .

RUN npm install

COPY . .

CMD ["npm", "run", "start:dev"]

