# Hosting a Full-Stack Application

# Udagram

The udagram application is a simple application that aws services.

The project is available at

http://timosergioudagrambucket.s3-website-us-east-1.amazonaws.com/

Please check the documentation folder (docs, diagram and screenshots) for more informations

### Dependencies

```
- Node v14.15.1 (LTS) or more recent. While older versions can work it is advisable to keep node to latest LTS version

- npm 6.14.8 (LTS) or more recent

- AWS CLI v2

- A RDS database running Postgres.

- A S3 bucket for hosting uploaded pictures.

```

## Testing

This project contains two different test suite: unit tests and End-To-End tests(e2e). Follow these steps to run the tests.

1. `cd starter/udagram-frontend`
1. `npm run test`
1. `npm run e2e`

There are no Unit test on the back-end

### Unit Tests:

Unit tests are using the Jasmine Framework.

### End to End Tests:

The e2e tests are using Protractor and Jasmine.

## Built With

- [Angular](https://angular.io/) - Single Page Application Framework
- [Node](https://nodejs.org) - Javascript Runtime
- [Express](https://expressjs.com/) - Javascript API Framework

## CircleCI Badge

[![CircleCI](https://dl.circleci.com/status-badge/img/gh/sergiokag/udagram/tree/master.svg?style=svg)](https://dl.circleci.com/status-badge/redirect/gh/sergiokag/udagram/tree/master)

## License

[License](LICENSE.txt)
