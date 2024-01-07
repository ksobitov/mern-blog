FROM node:lts-alpine

ENV CI=true
ENV WDS_SOCKET_PORT=0

WORKDIR /usr/src/app
COPY package.json .
RUN npm i
COPY . .

CMD ["npm", "start"]
