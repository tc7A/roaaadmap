# Laravel Learning Roadmap

## 1. Prerequisites
- PHP basics (syntax, OOP concepts)
- Composer package manager
- [Basic understanding of MVC architecture](#)
- [HTML, CSS, JavaScript basics](#)
- [Basic MySQL database knowledge](#)

## [2. Laravel Fundamentals](#)
- [Installing Laravel (via Composer / Laravel Installer)](#)
- [Laravel folder structure](#)
- [Service providers and configuration files](#)
- [Environment variables (`.env` file)](#)
- [Request lifecycle in Laravel](#)

## 3. Routing
- [Basic routes](#)
- [Route parameters](#)
- [Named routes](#)
- [Route groups & prefixes](#)
- Route model binding (implicit & explicit)
- Route caching

## 4. Controllers
- [Creating controllers](#)
- [Resource controllers](#)
- [API controllers](#)
- Dependency injection in controllers
- Single action controllers (`__invoke`)

## 5. Models & Eloquent ORM
- Creating models
- Defining relationships:
  - One-to-One
  - One-to-Many
  - Many-to-Many
  - HasManyThrough
  - Polymorphic relationships
- Mass assignment & guarded attributes
- Accessors & Mutators
- Query scopes (global & local)
- Eager loading vs Lazy loading

## 6. Migrations & Database
- Creating migrations
- Schema builder basics
- Rolling back & refreshing migrations
- Seeding data
- Using factories
- Database transactions

## 7. Blade Templating
- [Blade syntax (`@if`, `@foreach`, `@include`, `@yield`, `@section`)](#)
- [Blade layouts](#)
- Components & Slots
- Conditional & loop directives
- [Blade & Tailwind CSS integration](#)

## 8. Forms & Validation
- CSRF protection
- Form requests
- Validation rules
- Custom validation messages
- Validation with AJAX

## 9. Authentication & Authorization
- Laravel Breeze / Jetstream / Fortify
- Login, registration, password reset
- Middleware for authentication
- Gates & Policies
- Role-based access control (RBAC)

## 10. Middleware
- Creating custom middleware
- Global middleware
- Middleware parameters
- Middleware groups

## 11. File Storage & Uploads
- File upload handling
- Storage facade
- Public vs private storage
- File download
- Cloud storage (AWS S3, etc.)

## 12. API Development
- Creating API routes
- API Resource classes
- API authentication (Passport, Sanctum)
- JSON responses & status codes
- API versioning

## 13. Laravel Advanced Concepts
- Service container & service providers
- Facades
- Events & Listeners
- Queues & Jobs
- Broadcasting (Pusher, Laravel Echo)
- Task scheduling (Cron + `schedule` method)

## 14. Testing
- PHPUnit basics
- Feature tests
- Unit tests
- Database testing
- Mocking & fakes

## 15. Laravel Optimization & Deployment
- Config caching
- Route caching
- Query optimization
- Laravel Horizon (for queues)
- Deployment (Forge, Envoyer, shared hosting)

## 16. Laravel Ecosystem
- Laravel Livewire
- Laravel Inertia.js
- Laravel Scout (search)
- Laravel Telescope (debugging)
- Laravel Socialite (OAuth)
