FROM node:10

WORKDIR /usr/app
COPY . .

RUN npm install && npm install -g serve && npm run build

CMD serve build/
