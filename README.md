<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo_text.svg" width="320" alt="Nest Logo" /></a>
</p>

## Description

Based on [Nest](https://github.com/nestjs/nest) framework TypeScript starter repository. Built while going through the Udemy course on NestJS - [NestJS Zero to Hero](https://www.udemy.com/course/nestjs-zero-to-hero/).

## Installation

```bash
$ npm install
```

## Running the app

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## Test

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```

## Lessons learned
Typescript decorators are used heavily - [docs](https://www.typescriptlang.org/docs/handbook/decorators.html) provide some explanations but they are not required to understand how NestJS works.
CLI is useful - it generates all the boilerplate and puts it at the right place.
Constructor is used for automatic dependency injection - we declare the deps there and NestJS injects them automatically.