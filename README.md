[![Build Status](https://travis-ci.org/redpen-cc/redpen-js-plugin.svg?branch=master)](https://travis-ci.org/redpen-cc/redpen-js-plugin)

## Introduction

This project is a sample of RedPen JavaScript plugin. This repository includes all the resources needed for testing RedPen validator. This repository include a plain validator in js/validator.js. The tests are included in `test/validator-js-test.js`. `test/redpen.js` is a utility script used in the testing.

## Requirements

RedPen requires the following software.

- Java 1.8.40 or greater
- Node.js 6.0 or greater

## Preliminary

First, copy this repository with `git clone` command. Then you install the JavaScript libraries with `npm install`.

## Run Test

There are two way of running tests. One is test launching RedPen server. The other is running test without the servers.

### Test with RedPen Server

```
npm run test
```

### Test without RedPen Server

```
npm run test-with-cli
```
