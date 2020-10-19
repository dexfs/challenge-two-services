# States and Population service

## ❯ Table of contents

- [Requirements](#-requirements)
- [Libraries](#-libraries)
- [Installation](#-installation)
- [Running the app](#-running-the-app)
- [Routes and Payloads](#-routes-and-payloads)


## ❯ Requirements

- [Node.js](https://nodejs.org/en/)
- npm
- [Docker(optional)](https://docs.docker.com/get-docker/)

## ❯ Libraries
- [Nestjs](https://nestjs.com/)
- [Typescript](https://www.typescriptlang.org/)

## ❯ Installation

```bash
$ cd population 
$ npm install
$ # volte pra a pasta raiz 
$ cd states
$ npm install
```

### Docker

```bash
$ docker-compose build
```


## ❯ Running the app

```bash
# development
$ npm run start:dev
```

### With docker

```
# Running showing the logs
$ docker-compose up

# Running in background
docker-compose up -d
```

## ❯ Routes

### Estados
`http://localhost:3124/estados`

### População
`http://localhost:3124/populacao/sp`

