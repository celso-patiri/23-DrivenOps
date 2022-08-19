FROM node:16

WORKDIR /app

COPY . /app

EXPOSE 3000

RUN yarn install

RUN yarn build

CMD yarn start
