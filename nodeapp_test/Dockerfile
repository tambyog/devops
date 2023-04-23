FROM node:latest

WORKDIR /usr/src/app

COPY nodeapp_test/package.json 

RUN npm install

COPY nodeapp_test nodeapp_test

EXPOSE 4000
CMD [ "node", "index.js" ]
