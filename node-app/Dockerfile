FROM node:alpine

WORKDIR /app

RUN npm install

COPY index.js package.json .

ENTRYPOINT ["node", "index.js"]
