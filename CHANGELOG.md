# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

## [1.6.0](https://github.com/virtualidentityag/caritas-onlineBeratung-uploadService/compare/v1.5.0...v1.6.0) (2021-04-12)


### Features

* switched java version for docker build, github actions and maven build ([01387e8](https://github.com/virtualidentityag/caritas-onlineBeratung-uploadService/commit/01387e853e663112b83850253a0ec21a90839b0f))

## [1.5.0](https://github.com/virtualidentityag/caritas-onlineBeratung-uploadService/compare/v1.4.0...v1.5.0) (2021-03-01)


### Features

* set logging of quota reached exception to info ([2d8b20e](https://github.com/virtualidentityag/caritas-onlineBeratung-uploadService/commit/2d8b20ed4f43f7921cb66b5574e3cdfcb36be7af))


### Bug Fixes

* provide session as condition for upload limit ([9ada75c](https://github.com/virtualidentityag/caritas-onlineBeratung-uploadService/commit/9ada75cc9bb77707ec2939043ca57ff38df2487d))

## [1.4.0](https://github.com/virtualidentityag/caritas-onlineBeratung-uploadService/compare/v1.3.0...v1.4.0) (2020-12-14)


### Features

* added javadocs ([c8b11f1](https://github.com/virtualidentityag/caritas-onlineBeratung-uploadService/commit/c8b11f1f465cd41db833641bcbe0f8a81afc2258))
* create database table for uploads ([09d6460](https://github.com/virtualidentityag/caritas-onlineBeratung-uploadService/commit/09d64602baa04b2b464f893973140cc51efaedbe))
* integrate trackingservice for file uploads ([b8f2167](https://github.com/virtualidentityag/caritas-onlineBeratung-uploadService/commit/b8f2167947440a6bf35c4b04e8687db2011da2d4))
* minot optimizations ([197949a](https://github.com/virtualidentityag/caritas-onlineBeratung-uploadService/commit/197949a796200bab338caaad2e379ea3020a3ccd))
* optimize quota reached header ([6f4e05b](https://github.com/virtualidentityag/caritas-onlineBeratung-uploadService/commit/6f4e05b6a5d13709c951655ad948748c06b77021))
* provide cron for clean up of file limits ([4740ee8](https://github.com/virtualidentityag/caritas-onlineBeratung-uploadService/commit/4740ee85d7f303c2f093adcd3174afbc4d5aae80))

## [1.3.0](https://github.com/virtualidentityag/caritas-onlineBeratung-uploadService/compare/v1.2.2...v1.3.0) (2020-11-23)


### Features

* restrict release action to branches starting with release ([31fffe2](https://github.com/virtualidentityag/caritas-onlineBeratung-uploadService/commit/31fffe2ed75ee5c8f3defd5944941990a18d0b0b))
* update keycloak to version 11.0.2 ([f42dc03](https://github.com/virtualidentityag/caritas-onlineBeratung-uploadService/commit/f42dc03511a5b768ee36cc97e572cb93fe416b1f))
* update spring boot and dependencies ([a24a821](https://github.com/virtualidentityag/caritas-onlineBeratung-uploadService/commit/a24a821664a4a88085a277a2ea2137d5109b8d59))


### Bug Fixes

* update deprecated logging property ([ef328eb](https://github.com/virtualidentityag/caritas-onlineBeratung-uploadService/commit/ef328eb6bc0111af847bc4bde2f74475193f7ecf))

### [1.2.2](https://github.com/virtualidentityag/caritas-onlineBeratung-uploadService/compare/v1.2.1...v1.2.2) (2020-10-28)

### [1.1.1](https://github.com/virtualidentityag/caritas-onlineBeratung-uploadService/compare/v1.1.0...v1.1.1) (2020-10-12)

## [1.1.0](https://github.com/virtualidentityag/caritas-onlineBeratung-uploadService/compare/v1.0.1...v1.1.0) (2020-10-12)

### [1.2.1](https://github.com/virtualidentityag/caritas-onlineBeratung-uploadService/compare/v1.2.0...v1.2.1) (2020-10-28)

## [1.2.0](https://github.com/virtualidentityag/caritas-onlineBeratung-uploadService/compare/v1.0.1...v1.2.0) (2020-10-28)


### Features

* add live event trigger for new messages ([cb9ea86](https://github.com/virtualidentityag/caritas-onlineBeratung-uploadService/commit/cb9ea86600de3b042aa5a61e0dc4e2fdc07b4ee5))
* add live event trigger for new messages ([74c5a42](https://github.com/virtualidentityag/caritas-onlineBeratung-uploadService/commit/74c5a429c669b3e00ed947239e4445c642af15c5))
* minor optimizations ([37ebedb](https://github.com/virtualidentityag/caritas-onlineBeratung-uploadService/commit/37ebedbd420c5d1a52276bd331caf1d0c1c3187a))
* remove special chars except +-# from upload file name ([d52c658](https://github.com/virtualidentityag/caritas-onlineBeratung-uploadService/commit/d52c65858fe5079c24046b770da10d0311f8fc3d))
* updated swagger to openapi ([9ab4405](https://github.com/virtualidentityag/caritas-onlineBeratung-uploadService/commit/9ab44055d86a68da77b7c108eb226146ff469e33))


### Bug Fixes

* explicity set unrequired request params ([8189c09](https://github.com/virtualidentityag/caritas-onlineBeratung-uploadService/commit/8189c09d754be54dbd966a555c766d6557167488))

### [1.1.1](https://github.com/virtualidentityag/caritas-onlineBeratung-uploadService/compare/v1.1.0...v1.1.1) (2020-10-12)

## [1.1.0](https://github.com/virtualidentityag/caritas-onlineBeratung-uploadService/compare/v1.0.1...v1.1.0) (2020-10-12)


### Features

* remove special chars except +-# from upload file name ([d52c658](https://github.com/virtualidentityag/caritas-onlineBeratung-uploadService/commit/d52c65858fe5079c24046b770da10d0311f8fc3d))


### Bug Fixes

* added file name length limitation ([7b48fc1](https://github.com/virtualidentityag/caritas-onlineBeratung-uploadService/commit/7b48fc1d8b3205870da45acc19a3f7781462b1c3))
* added trim and check for whitespace only to filename validation ([092da31](https://github.com/virtualidentityag/caritas-onlineBeratung-uploadService/commit/092da31b8716a3d7c149753ea531181cd3e4da12))
* fixed version ([938f07b](https://github.com/virtualidentityag/caritas-onlineBeratung-uploadService/commit/938f07b721b0c3c620168b99b0af6c43aca1167c))
* fixed version ([5e73a76](https://github.com/virtualidentityag/caritas-onlineBeratung-uploadService/commit/5e73a768a5bfb11d719727f892647798a0d97327))
* remove obsolete logging tests ([698b7b3](https://github.com/virtualidentityag/caritas-onlineBeratung-uploadService/commit/698b7b30a9ab4167c99943a75bfd115ca0ce167f))

### 1.0.1 (2020-07-29)


### Bug Fixes

* added npm install for github release action ([f02d959](https://github.com/virtualidentityag/caritas-onlineBeratung-uploadService/commit/f02d959b36616e16faa48a104d08c7e1651098cb))
