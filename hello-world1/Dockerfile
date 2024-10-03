FROM node:18-slim

WORKDIR /usr/src/app

ADD package.json .
RUN npm install
COPY . test-ignore/
COPY index.js .

EXPOSE 3000

# CMD npm start
