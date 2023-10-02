FROM node:16-alpine

WORKDIR /frontend
COPY ./package.json .

RUN apk add curl

RUN npm i --save-dev

ENTRYPOINT ["sh", "./dev_entry.sh"]