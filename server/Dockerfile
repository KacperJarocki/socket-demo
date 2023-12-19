
FROM node:16

WORKDIR /usr/src/

COPY . ./server/

WORKDIR /usr/src/server

RUN npm install 

EXPOSE 8080

CMD ["npm","start"]
