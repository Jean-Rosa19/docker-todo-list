FROM node:14-alpine

WORKDIR /usr/src/app

EXPOSE 3001

ADD ./node_modules.tar.gz ./

COPY . .

ENTRYPOINT [ "npm", "start" ]

