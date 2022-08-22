FROM node:16

# pasta para aonde vai o build
WORKDIR /app

COPY . .
RUN yarn install
RUN yarn build

RUN mkdir -p /var/www/html
RUN mv build/* /var/www/html

WORKDIR /

RUN rm -rf /app
