# Awesome Go

> My handpicked collection of Go libraries, frameworks, and tools — only the coolest, most useful, and most delightful.  
> I include libraries I’ve actually used, love, or wish I wrote. Maintained and updated as I discover new gems!

---
## Table of Contents

- [SOLID](#solid)
- [Command Line](#command-line)
  - [Standard CLI](#standard-cli)
  - [Console UI](#console-ui)
- [Configuration](#configuration)
- [Date & Time](#date--time)
- [Distributed Systems](#distributed-systems)
- [Goroutines](#goroutines)
- [Networking](#networking)
  - [Web Framework](#web-framework)
  - [HTTP Client](#http-client)
  - [Websocket](#websocket)
- [Crawler](#crawler)
  - [Framework](#framework)
  - [Browser Automation](#browser-automation)
- [Testing](#testing)
  - [Framework](#framework-1)
  - [Integration](#integration)
  - [Mocking](#mocking)
- [Job Scheduler](#job-scheduler)
- [ORM](#orm)
- [Messaging](#messaging)
- [Logging](#logging)
- [Financial](#financial)
- [OAuth2](#oauth2)
- [Idiomatic Go](#idiomatic-go)

## SOLID
- [wire](https://github.com/google/wire) – Compile-time Dependency Injection for Go.

## Command Line

### Standard CLI
- [cobra](https://github.com/spf13/cobra) – A Commander for modern Go CLI interactions.
- [pflag](https://github.com/spf13/pflag) – Drop-in replacement for Go's flag package, POSIX/GNU-style.

### Console UI
- [bubbletea](https://github.com/charmbracelet/bubbletea) – A powerful little TUI framework.
- [bubbles](https://github.com/charmbracelet/bubbles) – TUI components for bubbletea.
- [lipgloss](https://github.com/charmbracelet/lipgloss) – Style definitions for nice terminal layouts.

## Configuration
- [viper](https://github.com/spf13/viper) – A complete configuration solution for Go apps. 

## Date & Time
- [carbon](https://github.com/dromara/carbon) – Simple, developer-friendly time package with 100% test coverage.

## Distributed Systems

### Microservices
- [go-kit](https://github.com/go-kit/kit) – Microservices toolkit for Go.
- [kratos](https://github.com/go-kratos/kratos) – Cloud-native microservices framework with gRPC and HTTP.
- [kratos-layout](https://github.com/elbert-chan/kratos-layout) – My kratos project template.

### Distributed Lock
- [temporal](https://github.com/temporalio/sdk-go) – Durable execution. Make your code live forever.
- [redsync](https://github.com/go-redsync/redsync) – Redis distributed lock. Hold the line!

### Distributed Transaction 
- [dtm](https://github.com/dtm-labs/dtm) – Distributed transactions. All the ACID you need, without the trip.

### Distributed ID
- [snowflake](https://github.com/bwmarrin/snowflake) – Twitter snowflake IDs. Unique as a snow day.

## Goroutines

- [ants](https://github.com/panjf2000/ants) – Goroutine pool. For those who like their concurrency crawling in formation.
- [conc](https://github.com/sourcegraph/conc) – Structured concurrency. No more goroutine spaghetti.

## Networking

### Web Framework
- [gin](https://github.com/gin-gonic/gin) – Web framework. Fast, tasty, and a little spicy.
- [kratos](https://github.com/go-kratos/kratos) – Microservices framework. Yes, it's so good it’s here twice.

### HTTP Client
- [resty](https://github.com/go-resty/resty) – HTTP/REST client. Make HTTP fun again.

### Websocket
- [gorilla/websocket](https://github.com/gorilla/websocket) – WebSocket library. King Kong of real-time.
- [gobwas/ws](https://github.com/gobwas/ws) – Lightweight WebSocket. Small but mighty.
- [melody](https://github.com/olahol/melody) – Minimalist WebSocket framework. Hum along with your data.

## Crawler

### Framework
- [colly](https://github.com/gocolly/colly) – Scraper and crawler. Spin your own web.

### Browser Automation
- [rod](https://github.com/go-rod/rod) – Web automation. Remote control for the web.
- [chromedp](https://github.com/chromedp/chromedp) – Chrome automation. Point, click, automate.

## Testing

### Framework
- [ginkgo](https://github.com/onsi/ginkgo) – Expressive BDD testing framework with Gomega matchers. 🏆
- [gomega](https://github.com/onsi/gomega) – Ginkgo's Preferred Matcher Library.
- [biloba](https://github.com/onsi/biloba) – Stable, performant, automated browser testing for Ginkgo.
- [chromedp](https://github.com/chromedp/chromedp) – Drive Chrome browsers via DevTools Protocol without dependencies.

### Integration
- [iotest](https://pkg.go.dev/testing/iotest) – Std Package iotest implements Readers and Writers useful mainly for testing.
- [httptest](https://pkg.go.dev/net/http/httptest) – Std Package httptest provides utilities for HTTP testing.
- [dockertest](https://github.com/ory/dockertest) – Run integration tests with Docker containers across all platforms.（简洁小巧）
- [testcontainers-go](https://github.com/testcontainers/testcontainers-go) – Programmatically manage Docker containers for integration tests.（体系全面）

### Mocking
- [moq](https://github.com/matryer/moq) – Generate interface mocks for testing.（gen stub）
- [mock](https://github.com/uber-go/mock) – Go **mocking framework** with code generation. (gen mock)
- [gomonkey](https://github.com/agiledragon/gomonkey) – Monkey patching library for unit testing. (monkey patch)
- [gofakeit](https://github.com/brianvoe/gofakeit) – Random fake data generator with 310+ functions. (gen fake)

## Job Scheduler
- [cron](https://github.com/robfig/cron) – Cron library.

## ORM
- [gorm](https://github.com/go-gorm/gorm) – ORM library.
- [ent](https://github.com/ent/ent) – ORM library. 🏆

## Messaging
- [segmentio/kafka-go](https://github.com/segmentio/kafka-go) – Kafka client.
- [go-queue](https://github.com/zeromicro/go-queue) – Pub/Sub framework.
- [nats-client](https://github.com/nats-io/nats.go) – NATS client.
## [Logging](lib/logging.md)
- [slog](https://pkg.go.dev/log/slog) – Std Package slog provides structured logging. 🏆
- [zap](https://github.com/uber-go/zap) – Blazing fast, structured, leveled logging in Go.
- [lumberjack](https://github.com/natefinch/lumberjack) - A log rolling package for Go. 🏆

## Financial
- [decimal](https://github.com/shopspring/decimal) – Arbitrary-precision decimal arithmetic for Go.

## OAuth2
- [oauth2](https://github.com/golang/oauth2) – OAuth2 client. Keys to the kingdom.
- [oauth2](https://github.com/go-oauth2/oauth2) – OAuth2 server. Gatekeeper mode: ON.

## Idiomatic Go
- [effective go](https://go.dev/doc/effective_go) – 👑
- [uber go guide](https://github.com/uber-go/guide) – Uber’s style guide. 🏆
- [google go styleguide](https://google.github.io/styleguide/go/) – Google’s Go wisdom. 🏆
