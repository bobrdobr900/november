FROM node:alpine

WORKDIR /app

RUN npm install

COPY index.js .

ENTRYPOINT ["node", "index.js"]
