# Test of CircleCI

<!-- [![Go Report Card](https://goreportcard.com/badge/github.com/msales/streams)](https://goreportcard.com/report/github.com/msales/streams)
[![Build Status](https://travis-ci.org/msales/streams.svg?branch=master)](https://travis-ci.org/msales/streams)
[![Coverage Status](https://coveralls.io/repos/github/msales/streams/badge.svg?branch=master)](https://coveralls.io/github/msales/streams?branch=master)
[![GoDoc](https://godoc.org/github.com/msales/streams?status.svg)](https://godoc.org/github.com/msales/streams) -->
[![GitHub release](https://img.shields.io/github/release/msales/streams.svg)](https://github.com/tomaszkrys/circleci-test/releases)
[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/msales/streams/master/LICENSE)

Repo created to test CircleCI, with template of CI/CD deploy pipline.

**Note:** This is just template, no real actions are done here.

## Installation

You just need to add this repo to CircleCI panel.

## Concepts

overral overview of designe tasks:
```
1. Build image/artifact pkg 
1.a. checkout
1.b. build image
1.c. push image
2. Pre prod
2.a. deploy on pre prod image/arifact pkg
2.b. pre prod envs
2.c. run on pre prod env
2.d. pre prod DB/cache migration
2.e. pre prod cache clear
3. TDD stuff:
3.a. unit tests
3.b. integration tests
3.c. functional test
coveralls
migration
warmup
notification
```