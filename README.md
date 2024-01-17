<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>


## Description

[Nest](https://github.com/nestjs/nest) framework TypeScript starter repository.

## Running the app on dev

1. Clone el repository
2. execute
```
yarn install
```
3. Have nest CLI installed
```
npm i -g @nestjs/cli
```
4. Up data base
```
docker-compose up -d
```
5. Remake bata base with seed
```
http://localhost:3000/api/v2/seed
```


## Installation

```bash
$ yarn install
```

## Running the app

```bash
# development
$ yarn run start

# watch mode
$ yarn run start:dev

# production mode
$ yarn run start:prod
```

## ENV
1. Rename __.env.template__ for __.env__
2. Fill the env
```
MONGODB=mongodb://url
PORT=3001
DEFAULT_LIMIT=5
```

## Test

```bash
# unit tests
$ yarn run test

# e2e tests
$ yarn run test:e2e

# test coverage
$ yarn run test:cov
```

## Stack
* MongoDB
* Nest

## License

Pokedex is [MIT licensed](LICENSE).
