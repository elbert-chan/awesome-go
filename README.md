# Awesome Go

> My handpicked collection of Go libraries, frameworks, and tools.

---
## Table of Contents

- [Design](#design)
- [SOLID](#solid)
- [Utilities](#utilities)
- [Testing](#testing)
- [Terminal APP](#terminal-app)
- [Distributed Systems](#distributed-systems)
- [Goroutines](#goroutines)
- [Networking](#networking)
- [Crawler](#crawler)
- [Job Scheduler](#job-scheduler)
- [ORM](#orm)
- [Messaging](#messaging)
- [Logging](#logging)
- [OAuth2](#oauth2)


## Design

### 1. Style Guide
- [effective go](https://go.dev/doc/effective_go) – Std effective Go.
- [uber go guide](https://github.com/uber-go/guide) – Uber’s style guide.
- [google go styleguide](https://google.github.io/styleguide/go/) – Google’s style guide.

### 2. Code Review
- [go code review comments](https://go.dev/wiki/CodeReviewComments) - Go code review comments.
- [google code review std](https://google.github.io/eng-practices/review/reviewer/standard.html) - Google code review std.

### 3. API Design
- [Google API](https://google.aip.dev/) - How Google does APIs.


## SOLID

- [wire](https://github.com/google/wire) – Compile-time Dependency Injection for Go.

## Utilities

### 1. Data Operator
- [lo](https://github.com/samber/lo) - A Lodash like Go library based on Go 1.18+ Generics (map, filter, contains, find...).
- [ro](https://github.com/samber/ro) - Streams & Reactive Programming paradigm for Go.

### 2. Configuration
- [viper](https://github.com/spf13/viper) – A complete configuration solution for Go apps. 

### 3. Date Time
- [carbon](https://github.com/dromara/carbon) – Simple, developer-friendly time package with 100% test coverage.

### 4. Financial
- [decimal](https://github.com/shopspring/decimal) – Arbitrary-precision decimal arithmetic for Go.

## Testing

### 1. Framework
- [ginkgo](https://github.com/onsi/ginkgo) – Expressive BDD testing framework with Gomega matchers. 🏆
- [gomega](https://github.com/onsi/gomega) – Ginkgo's Preferred Matcher Library.
- [playwrite](https://github.com/microsoft/playwright) - A framework for Web Testing and Automation. TS 🏆
- [chromedp](https://github.com/chromedp/chromedp) – Drive Chrome browsers via DevTools Protocol without dependencies.

### 2. Integration
- [iotest](https://pkg.go.dev/testing/iotest) – Std Package iotest implements Readers and Writers useful mainly for testing.
- [httptest](https://pkg.go.dev/net/http/httptest) – Std Package httptest provides utilities for HTTP testing.
- [dockertest](https://github.com/ory/dockertest) – Run integration tests with Docker containers across all platforms.（简洁小巧）
- [testcontainers-go](https://github.com/testcontainers/testcontainers-go) – Programmatically manage Docker containers for integration tests.（体系全面）

### 3. Double
- [moq](https://github.com/matryer/moq) – Generate interface mocks for testing.（gen stub）
- [gomonkey](https://github.com/agiledragon/gomonkey) – Monkey patching library for unit testing. (monkey patching)
- [mock](https://github.com/uber-go/mock) – Go **mocking framework** with code generation. (gen mock)
- [gofakeit](https://github.com/brianvoe/gofakeit) – Random fake data generator with 310+ functions. (gen fake)

## [Terminal APP](./lib/terminal-app.md)

### 1. CLI Framework
- [cobra](https://github.com/spf13/cobra) – A Commander for modern Go CLI interactions.
- [pflag](https://github.com/spf13/pflag) – Drop-in replacement for Go's flag package, POSIX/GNU-style.

### 2. TUI Framework
- [bubbletea](https://github.com/charmbracelet/bubbletea) – A powerful little TUI framework.
- [bubbles](https://github.com/charmbracelet/bubbles) – TUI components for bubbletea.
- [lipgloss](https://github.com/charmbracelet/lipgloss) – Style definitions for nice terminal layouts.

### 3. Release Engineer
- [goreleaser](https://github.com/goreleaser/goreleaser) - Release engineering, simplified.

## Distributed Systems

### 1. Microservices Arch
- [go-kit](https://github.com/go-kit/kit) – Microservices toolkit for Go.
- [kratos](https://github.com/go-kratos/kratos) – Cloud-native microservices framework with gRPC and HTTP.
- [kratos-layout](https://github.com/elbert-chan/kratos-layout) – My kratos project template.

### 2. Distributed ID
- [snowflake](https://github.com/bwmarrin/snowflake) – A package to generate or parse Twitter snowflake IDs.

### 3. Distributed Lock
- [redsync](https://github.com/go-redsync/redsync) – Redis distributed lock.

### 4. Distributed Transaction 
- [dtm](https://github.com/dtm-labs/dtm) – Distributed transactions.

## Goroutines

- [ants](https://github.com/panjf2000/ants) – Goroutine pool for efficient concurrency in Go.
- [conc](https://github.com/sourcegraph/conc) – Better structured concurrency for go.

## [Networking](./lib/networking.md)  

### 1. Web Framework
- [gin](https://github.com/gin-gonic/gin) – Web framework.
- [hertz](https://github.com/cloudwego/hertz) - High-performance, extensible Go HTTP framework.

### 2. HTTP Client
- [resty](https://github.com/go-resty/resty) – HTTP/REST/SSE client.

### 3. Websocket
- [gorilla/websocket](https://github.com/gorilla/websocket) – Reliable Go WebSocket library.（更通用）
- [gobwas/ws](https://github.com/gobwas/ws) – High-performance, low-level WebSocket library.（更低层）
- [melody](https://github.com/olahol/melody) – Minimalist WebSocket framework for Go.

## Crawler

### 1. Framework
- [colly](https://github.com/gocolly/colly) – A fast and elegant web scraping framework for Go.

### 2. Browser Automation
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

## OAuth2
- [OAuth2 Client](https://github.com/golang/oauth2) – OAuth2 client.
- [OAuth2 Server](https://github.com/go-oauth2/oauth2) – OAuth2 server.
