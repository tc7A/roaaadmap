# Rust Learning Roadmap – Topics You Must Learn

## [1. Rust Basics](#)
- [Installing Rust (rustup, cargo)](#)
- [Rust toolchain & editions](#)
- [Basic syntax](#)
- [Variables & mutability](#)
- [Data types (scalar & compound)](#)
- [Functions](#)
- [Comments](#)
- [Control flow (if, match, loops)](#)

## [2. Ownership & Memory Safety (Core of Rust)](#)
- [Ownership rules](#)
- [Borrowing (immutable & mutable)](#)
- [References](#)
- [Lifetimes (basic → advanced)](#)
- [Stack vs Heap](#)
- [Copy vs Move semantics](#)

## [3. Common Data Structures](#)
- [Strings & string slices](#)
- [Arrays](#)
- [Vectors (`Vec`)](#)
- [Tuples](#)
- [HashMaps](#)
- [Structs](#)
- [Enums](#)
- [Pattern matching](#)

## [4. Error Handling](#)
- [`panic!`](#)
- [`Result` & `Option`](#)
- [`unwrap` vs `expect`](#)
- [Error propagation (`?`)](#)
- [Custom error types](#)
- [`thiserror` & `anyhow` (ecosystem)](#)

## [5. Modules & Project Structure](#)
- [Modules (`mod`)](#)
- [Crates (binary & library)](#)
- [`use` keyword](#)
- [Visibility (`pub`)](#)
- [Workspaces](#)
- [Cargo.toml & dependency management](#)

## 6. Traits & Generics
- Defining traits
- Implementing traits
- Trait bounds
- Generic functions & structs
- Associated types
- Default trait methods
- Trait objects (`dyn Trait`)

## 7. Advanced Ownership & Lifetimes
- Explicit lifetimes
- Lifetime elision rules
- Multiple lifetimes
- `'static` lifetime
- Interior mutability
- `RefCell`, `Cell`
- `Rc` & `Arc`

## 8. Standard Library Essentials
- Iterators & iterator adapters
- Closures
- Smart pointers (`Box`, `Rc`, `Arc`)
- Collections API
- Formatting & macros (`println!`, `format!`)
- Time & date handling

## 9. Concurrency & Parallelism
- Threads
- `Send` & `Sync`
- Message passing (channels)
- Shared state concurrency
- Mutex & RwLock
- Atomic types
- Async vs threads

## [10. Async Rust](#)
- [`async` / `await`](#)
- [Futures](#)
- [Async runtimes (Tokio, async-std)](#)
- [Async I/O](#)
- [Streams](#)
- [Error handling in async](#)
- [Cancellation & timeouts](#)

## 11. Macros
- Declarative macros (`macro_rules!`)
- Procedural macros
- Custom derive macros
- Attribute macros

## 12. Unsafe Rust
- What `unsafe` means
- Raw pointers
- Unsafe functions & traits
- FFI basics
- Writing safe abstractions over unsafe code

## 13. Testing & Debugging
- Unit tests
- Integration tests
- Doc tests
- `cargo test`
- Debugging tools
- Logging & tracing

## 14. Performance & Optimization
- Zero-cost abstractions
- Profiling tools
- Benchmarking (`criterion`)
- Memory layout & alignment
- Avoiding unnecessary allocations

## 15. Rust Ecosystem & Tooling
- Cargo commands
- Clippy
- Rustfmt
- Docs (`rustdoc`)
- Crates.io
- Semantic versioning

## 16. Systems Programming
- File I/O
- Networking basics
- OS interaction
- CLI tools (`clap`)
- Embedded basics (optional)

## [17. Web & Application Development (Optional Path)](#)
- [REST APIs (Actix, Axum, Rocket)](#)
- [Web frameworks](#)
- [Database access (Diesel, SQLx)](#)
- [WebAssembly (WASM)](#)

## 18. Real-World Skills
- Reading Rust compiler errors
- Refactoring Rust code
- Designing APIs
- Writing idiomatic Rust
- Contributing to open-source Rust projects

## 19. Rust Design Philosophy
- Safety vs performance
- Fearless concurrency
- Idiomatic Rust patterns
- Common anti-patterns

## 20. Specialization Paths (Pick One)
### Systems Programming
- OS concepts
- Embedded Rust
- No-std Rust
### Web / Backend
- REST APIs
- Actix / Axum
- Database access
### Game Dev
- Bevy
- ECS concepts
### CLI Tools
- Argument parsing
- File processing
- Performance optimization
