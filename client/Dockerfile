FROM node:14-alpine

WORKDIR /usr/src/app

COPY package.json yarn.lock ./

RUN yarn install

COPY . .

ENV PORT 5173

CMD ["yarn", "run", "dev"]