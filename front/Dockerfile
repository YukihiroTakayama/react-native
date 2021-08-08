FROM "node:12-alpine"

RUN mkdir /app
WORKDIR /app

ADD ./yarn.lock /app/yarn.lock
RUN yarn global add expo-cli
RUN apk update && apk add bash
RUN yarn install
