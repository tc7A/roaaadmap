# Go (Golang) Learning Topics — From Basics to Advanced

## 0) Prerequisites & Setup
- Install Go (latest stable), set `GOPATH` and workspace  
- `go` tool basics: `go help`, `go version`, `go env`  
- Modules: `go mod init`, `go get`, `go mod tidy`, semantic import versions  
- Editor/IDE setup (`gopls`), formatting with `gofmt` / `go fmt`

## 1) Language Fundamentals
- Program structure: packages, `main`, `init` functions  
- Declarations: `var`, short `:=`, constants, `iota`  
- Basic types: `bool`, numeric types, strings, runes, `byte`  
- Collections: arrays, slices, maps  
- Control flow: `if`, `for` (three forms), `switch`, `defer`, `panic`/`recover` (mechanics)  
- Functions: params, variadics, multiple returns, named results  
- Pointers & value vs. reference semantics  
- Methods & receivers (value vs. pointer)  
- Structs, composition (embedding), exported vs. unexported identifiers  
- Interfaces: implicit satisfaction, interface values, nil interfaces  
- Generics (type parameters, constraints, type inference)  
- Packages & visibility rules, import cycles

## 2) Working with the Standard Library
- `fmt`, `strings`, `strconv`, `bytes`, `unicode/utf8`  
- Time & timers: `time`, tickers, deadlines  
- Files & OS: `os`, `io`, `bufio`, `path/filepath`, `embed`  
- Errors: `errors`, wrapping with `%w`, `errors.Is` / `errors.As`  
- JSON/XML/TOML/YAML: `encoding/json` (third‑party for others)  
- Logging: standard `log` and structured `log/slog`  
- Concurrency primitives: `sync`, `sync/atomic`, `context`  
- HTTP networking: `net`, `net/http`, `http/httptest`, `html/template`  
- Crypto & security basics: `crypto/*`, TLS in `net/http`

## 3) Concurrency & Parallelism (Core Strength of Go)
- Goroutines: lifecycles, leaks, stack growth  
- Channels: unbuffered vs buffered, send/receive, closing  
- `select` statements and timeouts  
- Context cancellation & timeouts (`context.Context` best practices)  
- Worker pools, pipelines, fan‑in/fan‑out patterns  
- Confinement vs. shared memory with locks  
- Go memory model (happens‑before, `atomic`)  
- Avoiding data races; race detector (`-race`)

## 4) Testing, Quality & Tooling
- Unit tests with `testing` & table‑driven tests  
- Benchmarks with `testing.B`  
- Fuzz testing (`go test -fuzz`)  
- Mocks via interfaces; golden files  
- `go vet`, `staticcheck` (3rd‑party), linters  
- Code coverage (`-cover`, `-coverprofile`)  
- Profiling & tracing: `pprof`, `trace`  
- Modules hygiene: reproducible builds, vendoring

## 5) Web, APIs & Networking
- Building HTTP servers/clients with `net/http`  
- Middleware patterns; routing (stdlib, or `chi`/`gorilla`/`gin` as options)  
- JSON APIs, validation, pagination, versioning  
- Sessions, cookies, CSRF, CORS, TLS  
- Streaming & websockets (e.g., `gorilla/websocket`)  
- gRPC & Protocol Buffers  
- Rate limiting, backoff/retries, circuit breakers

## 6) Data & Persistence
- `database/sql` core concepts: drivers, connection pools  
- Prepared statements, transactions, isolation levels  
- Migrations (e.g., `golang-migrate`)  
- Query helpers/ORMs (e.g., `sqlx`, `gorm`, `ent`) — trade‑offs  
- Caching (in‑memory, Redis), TTL strategies  
- Files, streaming large data via `io.Reader` / `io.Writer`

## 7) Architecture & Design in Go
- Package design & project layout; avoiding cyclic deps  
- Dependency injection via interfaces (not frameworks)  
- Error handling philosophy (return errors, wrap, sentinel vs. typed)  
- Configuration management (env, flags, files), `flag` / `pflag`  
- Observability: structured logging, metrics (Prometheus), tracing (OpenTelemetry)  
- Clean architecture / hexagonal patterns in Go  
- Versioning, backward compatibility, module boundaries

## 8) Performance & Reliability
- Escape analysis, allocations vs. stack, avoiding copies  
- Slices & maps performance characteristics  
- Zero‑alloc patterns, pooling (`sync.Pool`)  
- Garbage collector basics and tuning knobs  
- Hot paths: profiling CPU/heap/block/mutex  
- Concurrency pitfalls: head‑of‑line blocking, goroutine leaks  
- Backpressure, timeouts, deadlines

## 9) Advanced Language Features
- Advanced generics: constraints, type sets, iterators, generic data structures  
- Reflection (`reflect`) and when to avoid it  
- `unsafe` package: trade‑offs and risks  
- Build tags, conditional compilation  
- `go generate`, code generation tools (e.g., `stringer`)  
- CGO fundamentals & calling C; cross‑compilation  
- Writing small assembly for performance (optional/deep dive)

## 10) CLI & Tooling Ecosystem
- Build CLIs (e.g., `cobra`, `urfave/cli`)  
- Configuration files & `.env` loading  
- Packaging binaries, cross‑platform builds  
- Releasing with changelogs; `goreleaser`

## 11) Deployment & Operations
- Dockerizing Go apps (multi‑stage builds, small images, scratch/distroless)  
- Environment‑based configs and secrets  
- Graceful shutdown with `http.Server` and `Context`  
- Health checks, readiness/liveness endpoints  
- CI/CD pipelines; tests, lint, security scans  
- Cloud basics: running on Linux services, containers, serverless (Cloud Run/Lambda)

## 12) Security in Practice
- Input validation & encoding, avoiding injection  
- Managing secrets; KMS/secret stores  
- TLS config, certificate management  
- Password hashing (`bcrypt`, `scrypt`, `argon2`)  
- Signed tokens (JWT), pitfalls and safer practices  
- Dependency auditing (`govulncheck`)

## 13) Idioms & Community Conventions
- Effective Go idioms; `godoc` comments  
- Error values vs. exceptions mindset  
- Simplicity first; small interfaces; returning copies vs. pointers  
- Reading and contributing to standard library code  
- Writing clear README and examples

## 14) Capstone Projects (to consolidate learning)
- Tiny URL shortener (HTTP + storage + tests + Docker)  
- Concurrent web crawler (goroutines + channels + `context`)  
- CLI log parser with streaming I/O & benchmarks  
- REST + gRPC service with observability & CI  
- Real‑time chat with websockets, Redis pub/sub, graceful shutdown
