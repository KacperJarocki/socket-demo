FROM node:16

WORKDIR /usr/src/app

COPY . ./app/

workdir /usr/src/app/app

RUN npm -g install http-server

EXPOSE 80

CMD ["http-server","-p", "80"]

