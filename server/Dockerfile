FROM node:latest

WORKDIR /app

COPY . .

RUN npm install

RUN npm run build

EXPOSE 5012
EXPOSE 80

CMD npm run prod