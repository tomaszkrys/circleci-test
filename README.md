# Test of CircleCI

<!-- [![Go Report Card](https://goreportcard.com/badge/github.com/msales/streams)](https://goreportcard.com/report/github.com/msales/streams)
[![Build Status](https://travis-ci.org/msales/streams.svg?branch=master)](https://travis-ci.org/msales/streams)
[![Coverage Status](https://coveralls.io/repos/github/msales/streams/badge.svg?branch=master)](https://coveralls.io/github/msales/streams?branch=master)
[![GoDoc](https://godoc.org/github.com/msales/streams?status.svg)](https://godoc.org/github.com/msales/streams) -->
[![GitHub release](https://img.shields.io/github/release/msales/streams.svg)](https://github.com/msales/streams/releases)
[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/msales/streams/master/LICENSE)

Repo created to test CircleCI, with template of CI/CD deploy pipline.

**Note:** This is just template, no real actions are done here.

## Installation

You just need to add this repo to CircleCI panel.

## Concepts

overral overview of designe tasks:

#BUILD
# Build image/artifact pkg
## checkout
## build image
## push image

# Pre prod
## deploy on pre prod image/arifact pkg
## pre prod envs
## run on pre prod env
## pre prod DB/cache migration
## pre prod cache clear

# TDD stuff:
## unit tests
## integration tests
## functional test




# 
#coveralls
#migration
#warmup
#notification