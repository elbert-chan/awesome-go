# Awesome-go

- [Awesome-go](#awesome-go)
  - [Command Line](#command-line)
    - [Standard CLI](#standard-cli)
  - [Configuration](#configuration)
  - [Database Drivers](#database-drivers)
    - [Relational Database Drivers](#relational-database-drivers)
    - [NoSQL Database Drivers](#nosql-database-drivers)
    - [Search and Analytic Databases](#search-and-analytic-databases)
  - [Date \& Time](#date--time)
  - [Distributed Systems](#distributed-systems)
  - [Goroutines](#goroutines)
  - [HTTP Clients](#http-clients)
  - [Web Framworks](#web-framworks)
  - [Scrapers](#scrapers)
  - [Testing](#testing)
    - [fake](#fake)
    - [framework](#framework)
  - [Job Scheduler](#job-scheduler)
  - [ORM](#orm)
  - [Messaging](#messaging)
  - [Logging](#logging)
  - [Financial](#financial)
  - [OAUTH2](#oauth2)
  - [Style Guides](#style-guides)


## Command Line

### Standard CLI

Libraries for building standard or basic Command Line applications.

- [cobra](https://github.com/spf13/cobra) - A Commander for modern Go CLI interactions.
- [pflag](https://github.com/spf13/pflag) - Drop-in replacement for Go's flag package, implementing POSIX/GNU-style --flags.

## Configuration

Libraries for configuration parsing.

- [viper](https://github.com/spf13/viper) - Go configuration with fangs.

## Database Drivers

### Relational Database Drivers

### NoSQL Database Drivers

- [mongo-go-driver](https://github.com/mongodb/mongo-go-driver) - Official MongoDB driver for the Go language.
- [qmgo](https://github.com/qiniu/qmgo) - The Go driver for MongoDB. It‘s based on official mongo-go-driver but easier to use like Mgo. 

### Search and Analytic Databases

## Date & Time

Libraries for working with dates and times.

- [carbon](https://github.com/golang-module/carbon) - A simple, semantic and developer-friendly golang package for time.

## Distributed Systems

Packages that help with building Distributed Systems.

- [go-kit](https://github.com/go-kit/kit) - A standard library for microservices.
- [go-zero](https://github.com/zeromicro/go-zero) - A cloud-native Go microservices framework with cli tool for productivity.
- [kratos](https://github.com/go-kratos/kratos) - Your ultimate Go microservices framework for the cloud-native era.
- [kratos-mono-repo](https://github.com/codingcn/kratos-mono-repo) - kratos mono repo.
- [temporal ](https://github.com/temporalio/sdk-go) - Durable execution system for making code fault-tolerant and simple. Go SDK.
- [redsync](https://github.com/go-redsync/redsync) - Distributed mutual exclusion lock using Redis for Go.
- [snowflake](https://github.com/bwmarrin/snowflake) - A simple to use Go (golang) package to generate or parse Twitter snowflake IDs.
- [dtm](https://github.com/dtm-labs/dtm) - A distributed transaction framework, supports workflow, saga, tcc, xa, 2-phase message, outbox patterns, supports many languages.

## Goroutines

Tools for managing and working with Goroutines.

- [ants](https://github.com/panjf2000/ants) - Ants is a high-performance and low-cost goroutine pool in Go.
- [conc](https://github.com/sourcegraph/conc) - Better structured concurrency for go.

## HTTP Clients

Libraries for making HTTP requests.

- [resty](https://github.com/go-resty/resty) - Simple HTTP and REST client library for Go.

## Web Framworks

- [gin](https://github.com/gin-gonic/gin) - Gin is a HTTP web framework written in Go.
- [kratos](https://github.com/go-kratos/kratos) - Your ultimate Go microservices framework for the cloud-native era.

## Scrapers

- [colly](https://github.com/gocolly/colly) - Elegant Scraper and Crawler Framework for Golang.

## Testing

### fake
- [gofakeit](https://github.com/brianvoe/gofakeit) - Random fake data generator written in go.

### framework
- [ginkgo](https://github.com/onsi/ginkgo) - A Modern Testing Framework for Go.
- [gomega](https://github.com/onsi/gomega) - Ginkgo's Preferred Matcher Library.
- [biloba](https://github.com/onsi/biloba) - Stable, performant, automated browser testing for Ginkgo.

## Job Scheduler

Libraries for scheduling jobs.

- [cron](https://github.com/robfig/cron) - A cron library for go.
- [temporal](https://github.com/temporalio/temporal) - Temporal service.

## ORM

Libraries that implement Object-Relational Mapping or datamapping techniques.

- [gorm](https://github.com/go-gorm/gorm) - The fantastic ORM library for Golang, aims to be developer friendly.
- [ent](https://github.com/ent/ent) - An entity framework for Go.

## Messaging

Libraries that implement messaging systems.

- [gorilla/websocket](https://github.com/gorilla/websocket) - A fast, well-tested and widely used WebSocket implementation for Go.
- [gobwas/ws](https://github.com/gobwas/ws) - Tiny WebSocket library for Go.
- [melody](https://github.com/olahol/melody) - Minimalist websocket framework for Go.
- [segmentio/kafka-go](https://github.com/segmentio/kafka-go) - Kafka library in Go.
- [go-queue](https://github.com/zeromicro/go-queue) - Kafka, Beanstalkd Pub/Sub framework.
- [nats](https://github.com/nats-io/nats.go) - Golang client for NATS, the cloud native messaging system.
- [nats-server](https://github.com/nats-io/nats-server) - High-Performance server for NATS.io, the cloud and edge native messaging system.

Referance
- [How to build websockets in go](https://yalantis.com/blog/how-to-build-websockets-in-go/)
（[中文版](https://tonybai.com/2019/09/28/how-to-build-websockets-in-go/)）
- [Go 社区主流 kafka 客户端简要对比](https://tonybai.com/2022/03/28/the-comparison-of-the-go-community-leading-kakfa-clients/)
- [依赖 kafka 的 Go 单元测试](https://tonybai.com/2024/01/08/go-unit-testing-deps-on-kafka/)

## Logging

- [slog](lib/slog.md) - Go 1.21 brings structured logging to the standard library.
- [zap](https://github.com/uber-go/zap) Blazing fast, structured, leveled logging in Go.

## Financial

Packages for accounting and finance.

- [decimal](https://github.com/shopspring/decimal) - Arbitrary-precision fixed-point decimal numbers in go.

## OAUTH2

- [oauth2](https://github.com/golang/oauth2) - Go OAuth2 client.
- [oauth2](https://github.com/go-oauth2/oauth2) - OAuth 2.0 server library for the Go programming language.

## Style Guides

- [uber-go/guide](https://github.com/uber-go/guide) - The Uber Go Style Guide.
- [google/styleguide](https://github.com/google/styleguide) - Style guides for Google-originated open-source projects.
