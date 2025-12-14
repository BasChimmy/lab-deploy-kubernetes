FROM node:current-slim

LABEL MAINTAINER=jirayu.kuv@gmail.com

COPY . /src

WORKDIR /src

RUN npm install

EXPOSE 8080

CMD ["node", "app.js"]
