FROM node:20-alpine

LABEL org.opencontainers.image.source=https://github.com/agray998/QAGITOPP_STARTER

WORKDIR /app

COPY package* .

RUN npm install

COPY server.js .

CMD ["node", "server.js"]
