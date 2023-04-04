FROM node:latest

RUN mkdir /app

WORKDIR /app

COPY package.json /app

RUN npm install

COPY . /app

EXPOSE 3000

CMD bash -c "npm install && npm run start:frontend"
