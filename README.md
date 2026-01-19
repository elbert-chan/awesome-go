# Awesome Go

> My handpicked collection of Go libraries, frameworks, and tools.

---
## Table of Contents

- [SOLID](#solid)
- [Utilities](#utilities)
- [Testing](#testing)
  - [Framework](#framework-1)
  - [Integration](#integration)
  - [Double](#double)
- [Terminal APP](#terminal-app)
  - [CLI Framework](#cli-framework)
  - [TUI Framework](#tui-framework)
- [Configuration](#configuration)
- [Distributed Systems](#distributed-systems)
  - [Microservice Arch](#microservices-arch)
  - [Distributed ID](#distributed-id)
  - [Distributed Lock](#distributed-lock)
  - [Distributed Transaction](#distributed-transaction)
- [Goroutines](#goroutines)
- [Networking](#networking)
  - [Web Framework](#web-framework)
  - [HTTP Client](#http-client)
  - [Websocket](#websocket)
- [Crawler](#crawler)
  - [Framework](#framework)
  - [Browser Automation](#browser-automation)
- [Job Scheduler](#job-scheduler)
- [ORM](#orm)
- [Messaging](#messaging)
- [Logging](#logging)
- [Financial](#financial)
- [OAuth2](#oauth2)
- [Idiomatic Go](#idiomatic-go)

## SOLID
- [Google AIP](https://google.aip.dev/) - AIPs are lots of documents on how Google does APIs.
- [wire](https://github.com/google/wire) – Compile-time Dependency Injection for Go.

## Utilities

### 1. data operator
- [lo](https://github.com/samber/lo) - A Lodash like Go library based on Go 1.18+ Generics (map, filter, contains, find...). 🏆
- [ro](https://github.com/samber/ro) - Streams & Reactive Programming paradigm for Go. 🏅

### 2. date & time
- [carbon](https://github.com/dromara/carbon) – Simple, developer-friendly time package with 100% test coverage.

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

### Double
- [moq](https://github.com/matryer/moq) – Generate interface mocks for testing.（gen stub）
- [gomonkey](https://github.com/agiledragon/gomonkey) – Monkey patching library for unit testing. (monkey patching)
- [mock](https://github.com/uber-go/mock) – Go **mocking framework** with code generation. (gen mock)
- [gofakeit](https://github.com/brianvoe/gofakeit) – Random fake data generator with 310+ functions. (gen fake)

## Terminal APP

### CLI Framework
- [cobra](https://github.com/spf13/cobra) – A Commander for modern Go CLI interactions.
- [pflag](https://github.com/spf13/pflag) – Drop-in replacement for Go's flag package, POSIX/GNU-style.

### TUI Framework
- [bubbletea](https://github.com/charmbracelet/bubbletea) – A powerful little TUI framework.
- [bubbles](https://github.com/charmbracelet/bubbles) – TUI components for bubbletea.
- [lipgloss](https://github.com/charmbracelet/lipgloss) – Style definitions for nice terminal layouts.

## Configuration
- [viper](https://github.com/spf13/viper) – A complete configuration solution for Go apps. 

## Distributed Systems

### Microservices Arch
- [go-kit](https://github.com/go-kit/kit) – Microservices toolkit for Go.
- [kratos](https://github.com/go-kratos/kratos) – Cloud-native microservices framework with gRPC and HTTP.
- [kratos-layout](https://github.com/elbert-chan/kratos-layout) – My kratos project template.

### Distributed ID
- [snowflake](https://github.com/bwmarrin/snowflake) – A package to generate or parse Twitter snowflake IDs.

### Distributed Lock
- [redsync](https://github.com/go-redsync/redsync) – Redis distributed lock.

### Distributed Transaction 
- [dtm](https://github.com/dtm-labs/dtm) – Distributed transactions.

## Goroutines

- [ants](https://github.com/panjf2000/ants) – Goroutine pool for efficient concurrency in Go.
- [conc](https://github.com/sourcegraph/conc) – Better structured concurrency for go.

## [Networking](./lib/networking.md)  

### Web Framework
- [gin](https://github.com/gin-gonic/gin) – Web framework.
- [hertz](https://github.com/cloudwego/hertz) - High-performance, extensible Go HTTP framework.

### HTTP Client
- [resty](https://github.com/go-resty/resty) – HTTP/REST/SSE client.

### Websocket
- [gorilla/websocket](https://github.com/gorilla/websocket) – Reliable Go WebSocket library.（更通用）
- [gobwas/ws](https://github.com/gobwas/ws) – High-performance, low-level WebSocket library.（更低层）
- [melody](https://github.com/olahol/melody) – Minimalist WebSocket framework for Go.

## Crawler

### Framework
- [colly](https://github.com/gocolly/colly) – A fast and elegant web scraping framework for Go.

### Browser Automation
- [rod](https://github.com/go-rod/rod) – Go library for web automation and scraping via DevTools Protocol.
- [chromedp](https://github.com/chromedp/chromedp) – Fast, simple Go library for driving browsers via Chrome DevTools Protocol.

## Job Scheduler
- [cron](https://github.com/robfig/cron) – Cron library.

## ORM
- [gorm](https://github.com/go-gorm/gorm) – Popular Go ORM, simple and feature-rich.
- [ent](https://github.com/ent/ent) – Schema-as-code framework, type-safe and scalable. 🏆

## [Messaging](./lib/messaging.md)
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
- [OAuth2 Client](https://github.com/golang/oauth2) – OAuth2 client.
- [OAuth2 Server](https://github.com/go-oauth2/oauth2) – OAuth2 server.

## Idiomatic Go
- [effective go](https://go.dev/doc/effective_go) – Std Effective go. 👑
- [uber go guide](https://github.com/uber-go/guide) – Uber’s style guide. 🏆
- [google go styleguide](https://google.github.io/styleguide/go/) – Google’s Go wisdom. 🏆
