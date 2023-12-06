FROM node:latest

COPY ./index.js .
COPY ./package.json .

RUN npm install

ENTRYPOINT ["node", "index.js"]


