FROM node:alpine

RUN npm config set https://registry.npmmirror.com; \
    npm i -g serve

WORKDIR /www

EXPOSE 3000

CMD ["serve", "-s",  "/www"]
