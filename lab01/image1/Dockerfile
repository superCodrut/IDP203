FROM node:latest

COPY package.json ./

RUN npm install package.json

COPY server.js /usr/src/app/

EXPOSE 8080 

CMD ["/usr/src/app/server.js", "node"]

