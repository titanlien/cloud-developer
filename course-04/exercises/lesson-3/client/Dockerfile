FROM node:13

WORKDIR /app

COPY ./ ./

RUN yarn install && yarn build

EXPOSE 3000

CMD yarn start
