FROM node:11-alpine

RUN mkdir -p /usr/app

ADD /src /usr/app

WORKDIR /usr/app/src

RUN npm install

EXPOSE 3000

CMD ["npm", "run", "dev"]