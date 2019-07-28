# koa-helloworld

Demo of koa.

[![license](https://img.shields.io/badge/license-MIT-FF2281.svg?style=flat-square&labelColor=black)](./LICENSE)
[![test](https://img.shields.io/badge/test-jest-001437.svg?style=flat-square&labelColor=black)]()
[![code_style:airbnb](https://img.shields.io/badge/code_style-airbnb-F5D300.svg?style=flat-square&labelColor=black)](https://github.com/airbnb/javascript)
[![code_style:prettier](https://img.shields.io/badge/code_style-prettier-FFACFC.svg?style=flat-square&labelColor=black)](https://prettier.io/)
[![.nvmrc](https://img.shields.io/badge/.nvmrc-12-09FF33.svg?style=flat-square&labelColor=black)]()
[![yarn:required](https://img.shields.io/badge/yarn-required-00207F.svg?style=flat-square&labelColor=black)](https://yarnpkg.com/en/)
[![Commitizen friendly](https://img.shields.io/badge/commitizen-cz_conventional_changelog-brightgreen.svg?style=flat-square&labelColor=black)](http://commitizen.github.io/cz-cli/)
[![pr_welcome](https://img.shields.io/badge/PRs-welcome-08F7FE.svg?style=flat-square&labelColor=black)]()

[![CircleCI](https://circleci.com/gh/jjangga0214/koa-helloworld.svg?style=svg)](https://circleci.com/gh/jjangga0214/koa-helloworld)
[![codecov](https://codecov.io/gh/jjangga0214/koa-helloworld/branch/master/graph/badge.svg?style=flat-square&labelColor=black)](https://codecov.io/gh/jjangga0214/koa-helloworld)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/9f602a8d2d2a4ba3bb9bab0695247ac6)](https://app.codacy.com/app/jjangga0214/koa-helloworld?utm_source=github.com&utm_medium=referral&utm_content=jjangga0214/koa-helloworld&utm_campaign=Badge_Grade_Dashboard)
[![codebeat badge](https://codebeat.co/badges/e8c4d4c3-8c45-4a6b-83b4-457007ac6bf0)](https://codebeat.co/projects/github-com-jjangga0214-koa-helloworld-master)
[![DeepScan grade](https://deepscan.io/api/teams/4834/projects/6595/branches/55635/badge/grade.svg)](https://deepscan.io/dashboard#view=project&tid=4834&pid=6595&bid=55635)
[![CodeFactor](https://www.codefactor.io/repository/github/jjangga0214/koa-helloworld/badge)](https://www.codefactor.io/repository/github/jjangga0214/koa-helloworld)
[![Greenkeeper badge](https://badges.greenkeeper.io/jjangga0214/koa-helloworld.svg)](https://greenkeeper.io/)

## Note

Please read [NOTE.md](./NOTE.md), before getting started.

## Getting started

Install dependencies.

```bash
yarn install
```

Copy and edit **.env** file as you want. Note that the server requires **.env** file, as it does not have any "default" values.

```bash
cp .env.example .env
```

Run the server. There is no command dedicated to local development environment (e.g. `yarn dev`). Both production and development use the same command.

```bash
yarn start
```

## Yarn scripts

```bash
yarn test # runs all tests (runs `jest` against "*.test.js")
yarn test:unit # runs unit tests
yarn test:integration # runs integration tests
yarn test:coverage # runs all tests and measures coverage
yarn test:coverage:unit # runs unit tests and measures coverage
yarn test:coverage:integration # runs integration tests and measures coverage

yarn lint # lints and formats with eslint and prettier
yarn lint:ci # only checks lint rules without formatting. Then make report
```

## License

[MIT License](./LICENSE). Copyright &copy; 2019, Gil B. Chan <<bnbcmindnpass@gmail.com>> ([@jjangga0214](https://github.com/jjangga0214))
