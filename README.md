[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)

# StudentHub

![STDHUB](https://github.com/StudentHub-academic-project/client/blob/834a796e3949b691495a7717225aed93928c79ec/my-app/src/logo/logo.png?raw=true)

#### [Visit Documentation website ↗]https://studenthub-academic-project.github.io/docs/)

## Table of contents

* [Description](#about)
* [Getting started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
  * [Deployment](#deployment)
  * [Running tests](#running-tests)
* [Contributing](#contributing)
* [Changelog](#changelog)
* [Authors](#authors)
* [License](#license)

## About

StudentHub is an service for student, where they can share with all academic materials, such as presentations, pdf files and etc., also they can post some articles and posts.

## Getting started

### Prerequisites

* yarn `npm i -g yarn` or `corepack enable`

> [!IMPORTANT]
> **Node.js 18.x+** version must be installed in your OS.

### Installation

1. Clone the server repository

```shell
$ git clone https://github.com/StudentHub-academic-project/server
```

2. Install dependencies

```shell
$ yarn install
```

3. Clone the client repository

```shell
$ git clone https://github.com/StudentHub-academic-project/client
```

4. Install dependencies

```shell
$ yarn install
```

### Deployment

#### Server

```shell
$ yarn build
$ yarn start:prod
```
or
```shell
docker build -t stdhub .
docker run -p <port>:<9110> stdhub
```

#### Client
```shell
$ yarn start
```

### Running tests

#### Unit tests

```shell
$ yarn test
```

watch mode

```shell
$ yarn test:watch
```

#### End to end tests

This e2e tests are testing server api

```shell
$ yarn test:e2e
```

watch mode

```shell
$ yarn test:e2e:watch
```

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Changelog

We use [SemVer](https://semver.org/) for versioning.
For the versions available, see the [tags](https://github.com/stbestichhh/lcs-cloud-storage-server/tags) on this repository.

For the supported and unsupported versions, see the [SECURITY.md](SECURITY.md).

## Authors

- [@stbestichhh](https://www.github.com/stbestichhh)
- [@Cake2Rock](https://github.com/Cake2Rock)
- [@anastasia-sl](https://github.com/anastasia-sl)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE)
