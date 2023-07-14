FROM node:16-alpine

WORKDIR /frontend

COPY . .

RUN yarn --registry=https://registry.npm.taobao.org install
 
CMD ["yarn", "start"]
