FROM node:12.13
EXPOSE 50051

RUN apt-get update || : && apt-get install python -y


WORKDIR /usr/src

RUN mkdir app

COPY package*.json ./
RUN npm install -g @nestjs/cli
RUN npm install

COPY . /app
