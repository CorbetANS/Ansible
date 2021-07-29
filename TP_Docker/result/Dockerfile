FROM node:14-slim

WORKDIR /apps
COPY . .
RUN npm install
EXPOSE 4000

CMD [ "node" , "server.js" ]