FROM node:16-alpine

WORKDIR /src

ADD package.json /src

RUN yarn install

ADD .env /src

CMD ["yarn", "start"]