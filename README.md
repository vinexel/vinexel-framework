<div align="center">

<img src="https://vinexel.com/static/vinexel/images/logo.png" alt="Vinexel Framework Logo" width="180">

# VINEXEL Framework

### Vivid Innovation for Excellence

**A science-driven PHP framework for modular, multi-project, and interconnected application ecosystems.**

<br>

> **“Think differently. Build the Vinexel way.”**
> — *Vinexel Pioneers*

<br>

![PHP](https://img.shields.io/badge/PHP-8.3%2B-777BB4?logo=php\&logoColor=white)
![Architecture](https://img.shields.io/badge/Architecture-Hybrid%20Modular%20HMVC-0A7EA4)
![Projects](https://img.shields.io/badge/Projects-Multi--Project-18A558)
![License](https://img.shields.io/badge/License-MIT-green)

</div>

<br>

---

## About Vinexel Framework

**Vinexel Framework** is a next-generation PHP framework engineered for high-performance, modular, multi-domain, and multi-project application architectures.

It combines:

* the clarity of modern PHP;
* the modularity of hierarchical MVC;
* the flexibility of domain-oriented architecture;
* the structural discipline of Clean Architecture;
* and the operational efficiency of a shared application core.

Vinexel is designed to support multiple independent projects, domains, platforms, or tenants from a single interconnected framework foundation.

Rather than treating every application as an isolated codebase, Vinexel enables related systems to share common infrastructure while preserving clear project boundaries.

It can be used as the foundation for:

* e-commerce platforms;
* software-as-a-service applications;
* single sign-on services;
* multi-domain platforms;
* internal business systems;
* modular web applications;
* and enterprise-grade ecosystems.

Vinexel is not merely a collection of framework components. It is an engineering foundation for building connected technological systems.

<br>

## Engineering Philosophy

Vinexel is developed through scientific reasoning, first-principles thinking, measurable engineering decisions, and continuous refinement.

Its architecture is guided by the principle that software should remain understandable as it grows.

| Principle                 | Application                                                                                 |
| :------------------------ | :------------------------------------------------------------------------------------------ |
| **Simplicity**            | Remove unnecessary complexity without weakening functionality.                              |
| **Clarity**               | Maintain explicit responsibilities, predictable structures, and readable execution flows.   |
| **Modularity**            | Separate systems into focused components with controlled dependencies.                      |
| **Efficiency**            | Minimize unnecessary computation, memory usage, network activity, and development overhead. |
| **Consistency**           | Apply predictable conventions across projects, domains, modules, and environments.          |
| **Scalability**           | Enable systems to expand without requiring a complete architectural rewrite.                |
| **Interconnection**       | Allow projects to share infrastructure and capabilities without losing isolation.           |
| **Reproducibility**       | Make installation, configuration, testing, and deployment processes repeatable.             |
| **Observability**         | Make system behavior easier to inspect, measure, debug, and improve.                        |
| **Continuous Refinement** | Treat every implementation as a foundation that can be tested and improved.                 |

<br>

## Scientific Development Method

Vinexel applies an iterative engineering method to framework development:

```text
Observe a real problem
        ↓
Identify its fundamental causes
        ↓
Form an architectural hypothesis
        ↓
Design a focused implementation
        ↓
Measure correctness and efficiency
        ↓
Validate through practical usage
        ↓
Document the findings
        ↓
Refine and integrate
```

Architectural decisions should not be based solely on convention or popularity.

Every significant implementation should be evaluated according to:

* correctness;
* maintainability;
* performance;
* resource consumption;
* security;
* developer experience;
* operational impact;
* and long-term scalability.

<br>

## A Pioneering Framework

Vinexel does not aim to reproduce existing PHP frameworks under a different name.

Its purpose is to explore a distinct framework model for interconnected application ecosystems.

Vinexel pioneers an approach in which:

* multiple projects can operate from one framework installation;
* domains can be resolved dynamically at runtime;
* shared infrastructure remains independent from project-specific business logic;
* applications can remain isolated while participating in the same ecosystem;
* framework capabilities can evolve without forcing every project to duplicate them;
* and architectural rules can remain consistent across an expanding platform.

Innovation within Vinexel is not pursued for novelty alone.

Every new concept must improve clarity, efficiency, accessibility, maintainability, or long-term technological value.

<br>

---

## Architectural Overview

Vinexel adopts a **Hybrid Modular HMVC Multi-Project Architecture** enriched with principles from:

* Clean Architecture;
* Domain-Oriented Design;
* layered application architecture;
* modular monolith design;
* dependency separation;
* and shared-kernel systems.

Its architecture separates the shared framework foundation from project-specific application logic.

```text
┌─────────────────────────────────────────────────────────────┐
│                     Incoming HTTP Request                    │
└─────────────────────────────┬───────────────────────────────┘
                              │
                              ▼
┌─────────────────────────────────────────────────────────────┐
│                Domain and Project Resolution                 │
│                                                             │
│   example-one.com  → ProjectOne                              │
│   example-two.com  → ProjectTwo                              │
│   example-three.com → ProjectThree                           │
└─────────────────────────────┬───────────────────────────────┘
                              │
                              ▼
┌─────────────────────────────────────────────────────────────┐
│                    Project Application Layer                 │
│                                                             │
│   Controllers · Services · Models · Routes · Views           │
└─────────────────────────────┬───────────────────────────────┘
                              │
                              ▼
┌─────────────────────────────────────────────────────────────┐
│                    Shared Vinexel Foundation                 │
│                                                             │
│ Router · Middleware · Database · Cache · Session · Security  │
│ CLI · Templates · Configuration · Runtime Infrastructure    │
└─────────────────────────────────────────────────────────────┘
```

Each project remains structurally isolated while using the same framework core and infrastructure.

This architecture is suitable for both:

### Multi-Project Systems

Several independent applications run from one Vinexel installation.

### Multi-Domain Systems

Different domains or ports are connected to different projects at runtime.

### Multi-Tenant Systems

Several tenants share infrastructure while retaining separate identity, configuration, access, and application data.

### Interconnected Platforms

Multiple applications communicate through shared authentication, services, infrastructure, or ecosystem standards.

<br>

## Architectural Objectives

Vinexel is designed to achieve the following objectives:

1. **Clear project isolation**
   Project-specific business logic should not leak into unrelated projects.

2. **Shared infrastructure**
   Routing, sessions, security, database access, caching, and other foundational capabilities can be reused.

3. **Controlled dependencies**
   Higher-level application modules should not depend unpredictably on unrelated implementation details.

4. **Replaceable components**
   Infrastructure components should be replaceable without rewriting the entire application.

5. **Predictable growth**
   Adding new projects should not require duplicating the complete framework foundation.

6. **Operational consistency**
   Development, testing, installation, and deployment should follow consistent conventions.

<br>

---

## Key Features

## Modular Multi-Project Architecture

* Hybrid HMVC and multi-project application structure.
* Independent controllers, models, services, routes, and views for each project.
* Shared framework infrastructure across multiple applications.
* Explicit project and domain boundaries.
* Modular organization for long-term maintainability.
* Support for an unlimited number of projects, subject to available infrastructure.

<br>

## Dynamic Domain Resolution

Vinexel can identify the active project from the incoming host or port.

Example development mappings:

```text
127.0.0.1:8000 → ProjectOne
127.0.0.1:8001 → ProjectTwo
127.0.0.1:8002 → ProjectThree
```

Example production mappings:

```text
platform-one.example → ProjectOne
platform-two.example → ProjectTwo
platform-three.example → ProjectThree
```

Domain resolution can be configured using project configuration, environment data, or a database-driven tenant resolver.

<br>

## Routing System

* Project-specific route definitions.
* Named routes.
* Dynamic route parameters.
* Route middleware.
* Controller and method dispatching.
* Domain-aware route loading.
* Cached or dynamically generated route definitions.
* Clear separation between routing and application execution.

Example:

```php
Router::get('/users/{id}', 'UserController@show')
    ->name('users.show')
    ->middleware('auth');
```

<br>

## Middleware Pipeline

Vinexel provides middleware support for request filtering and application access control.

Typical middleware responsibilities include:

* authentication;
* authorization;
* session initialization;
* CSRF validation;
* request sanitization;
* guest restrictions;
* administrative access;
* rate limiting;
* and project-specific policies.

Example aliases:

```php
'auth'
'guest'
'admin'
'csrf'
```

Middleware can be applied globally or to individual routes.

<br>

## Security Foundation

Vinexel provides a security-oriented request lifecycle with support for:

* CSRF protection;
* secure session handling;
* input validation;
* input sanitization;
* prepared database statements;
* password hashing;
* authentication restrictions;
* authorization middleware;
* secure recovery workflows;
* environment-based configuration;
* and structured security exceptions.

Security is treated as a system-wide architectural concern rather than an isolated utility.

<br>

## Authentication and Access Control

Vinexel includes authentication capabilities for common application workflows.

### `Protection`

Restricts protected application areas to authenticated users.

### `Restriction`

Prevents authenticated users from accessing pages intended only for guests, such as login or registration pages.

Supported authentication capabilities can include:

* session-based authentication;
* password hashing;
* account activation;
* email verification;
* activation codes;
* PIN-based account recovery;
* role-based authorization;
* and multi-application authentication.

<br>

## Single Sign-On Support

Vinexel can support Single Sign-On across interconnected applications.

A shared authentication foundation can allow users to:

* authenticate once;
* access multiple authorized applications;
* maintain consistent identity across domains;
* and preserve project-specific authorization boundaries.

SSO implementations should use secure cookie policies, controlled domain scope, token validation, session rotation, and explicit application trust relationships.

<br>

## Database Layer

Vinexel provides a PDO-based database abstraction through:

```php
Vision\Modules\Database
```

The database layer supports:

* PDO connections;
* prepared statements;
* bound parameters;
* transaction-safe operations;
* structured query execution;
* single-row retrieval;
* multiple-row retrieval;
* affected-row inspection;
* and generated identifier retrieval.

Common methods include:

```php
query()
bind()
execute()
single()
resultSet()
rowCount()
lastInsertId()
beginTransaction()
commit()
rollBack()
```

Example:

```php
$this->database->query(
    'SELECT id, name, email
     FROM users
     WHERE email = :email
     LIMIT 1'
);

$this->database->bind(':email', $email);

$user = $this->database->single();
```

Prepared statements and bound parameters should be used consistently to reduce SQL injection risks.

<br>

## Redis Integration

Vinexel includes an internal Redis integration layer:

```php
Deeper\Libraries\Redis
```

Redis can be used for:

* application caching;
* session storage;
* flash messages;
* distributed state;
* temporary data;
* authentication coordination;
* rate limiting;
* and cross-application communication.

Performance characteristics should be evaluated through reproducible benchmarks under representative workloads.

<br>

## Session and Flash Utilities

Vinexel provides integrated session and notification utilities.

### Session

Supports:

* session initialization;
* session persistence;
* user authentication state;
* project-level session data;
* and Redis-backed session storage.

### Flasher

Supports temporary notification messages such as:

* success;
* information;
* warning;
* validation error;
* and system failure.

Flash messages can be rendered using interface systems such as Bootstrap or Tailwind CSS.

<br>

## View and Templating System

Vinexel provides a flexible view layer supporting native PHP and rapid template rendering.

Supported template formats include:

```text
.php
.rapid.php
```

### Native PHP Views

Use standard PHP syntax for complete flexibility and direct language access.

### Rapid Templates

Use Vinexel's rapid templating conventions for concise and structured interface development.

### Twig-Based Capabilities

Vinexel can integrate Twig-style template capabilities for:

* template inheritance;
* reusable components;
* layouts;
* escaped output;
* loops;
* conditions;
* filters;
* and global helper functions.

Example helpers may include:

```php
asset()
route()
locale()
getUserData()
getUserEmail()
```

<br>

## Installer and Environment Bootstrapping

Vinexel includes installation and environment initialization capabilities.

The installer can:

* verify server requirements;
* initialize application configuration;
* configure database credentials;
* create initial administrative credentials;
* prepare environment files;
* validate writable directories;
* and mark the application as installed.

Configuration can use:

```text
.env
config.php
```

A fallback configuration mechanism can be used when environment-file loading is unavailable.

<br>

## CLI and Developer Tools

Vinexel includes the `vision` command-line interface for common framework operations.

Examples:

```bash
php vision serve
php vision make:controller UserController
php vision make:model User
php vision make:service UserService
php vision make:middleware Authenticate
php vision make:migration CreateUsersTable
```

The CLI is intended to reduce repetitive work while preserving explicit and readable generated code.

<br>

## Environment Management

Vinexel supports environment-specific behavior.

```text
development
testing
production
```

Environment configuration can control:

* error reporting;
* debugging;
* logging;
* cache behavior;
* database connections;
* external services;
* session policies;
* and security settings.

Production environments should disable detailed public error output and use centralized logging.

<br>

## Performance-Oriented Design

Vinexel is designed to minimize unnecessary framework overhead through:

* lightweight application bootstrapping;
* controlled service initialization;
* route caching;
* configuration caching;
* optimized autoloading;
* prepared database operations;
* Redis-backed caching;
* reusable framework infrastructure;
* and project-specific loading.

Performance claims should be validated using transparent benchmarks that measure:

* requests per second;
* response latency;
* memory consumption;
* CPU utilization;
* database query count;
* cache effectiveness;
* and application startup time.

<br>

## Observability and Reliability

A production-ready Vinexel application should support:

* structured application logs;
* request identifiers;
* error classification;
* execution timing;
* database query inspection;
* cache monitoring;
* security-event logging;
* health checks;
* and environment-aware diagnostics.

Reliable systems must be measurable.

Without observability, performance problems, security failures, and architectural regressions become difficult to identify objectively.

<br>

---

## Suggested Project Structure

```text
vinexel/
├── app/
│   ├── ProjectOne/
│   │   ├── Controllers/
│   │   ├── Models/
│   │   ├── Services/
│   │   ├── Middleware/
│   │   ├── Routes/
│   │   ├── Views/
│   │   └── Config/
│   │
│   ├── ProjectTwo/
│   │   ├── Controllers/
│   │   ├── Models/
│   │   ├── Services/
│   │   ├── Middleware/
│   │   ├── Routes/
│   │   ├── Views/
│   │   └── Config/
│   │
│   └── Shared/
│       ├── Contracts/
│       ├── Services/
│       └── Resources/
│
├── public/
│   └── index.php
│
├── system/
│   ├── framework/
│   ├── vendor/
│   └── storage/
│
├── tests/
├── .env
├── composer.json
└── vision
```

The exact structure may evolve as Vinexel continues to refine its modular architecture.

<br>

---

## Requirements

Before installing Vinexel, ensure that your environment provides:

* PHP 8.3 or later;
* Composer;
* PDO;
* required database drivers;
* JSON extension;
* Mbstring extension;
* OpenSSL extension;
* and a supported web server.

Optional infrastructure may include:

* Redis;
* MySQL or MariaDB;
* PostgreSQL;
* Nginx;
* Apache;
* and a process supervisor.

<br>

---

## Installation

### Install Composer

Download and install Composer from:

https://getcomposer.org/download/

<br>

### Create a New Vinexel Project

```bash
composer create-project vinexel/vinexel my-project
```

Enter the project directory:

```bash
cd my-project
```

<br>

### Configure the Environment

Create or update the environment configuration:

```env
APP_ENV=development
APP_DEBUG=true
APP_URL=http://127.0.0.1:8000

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=vinexel
DB_USERNAME=root
DB_PASSWORD=
```

Use secure credentials and disable debugging before deploying to production.

<br>

### Run the Development Server

Start the default project:

```bash
php vision serve
```

Start a project using a specific port:

```bash
php vision serve 8001
```

Example:

```text
http://127.0.0.1:8001
```

Additional projects can use different ports:

```bash
php vision serve 8002
php vision serve 8003
```

<br>

### Complete Installation

After starting the application, open the installation panel in your browser and complete the initial configuration.

The installer can prepare:

* application configuration;
* database connectivity;
* administrative credentials;
* environment values;
* and initial system state.

<br>

---

## Development Workflow

A typical Vinexel development workflow follows these stages:

```text
Define the project boundary
          ↓
Design routes and use cases
          ↓
Create controllers and services
          ↓
Implement domain and data logic
          ↓
Build views or API responses
          ↓
Test functionality and security
          ↓
Measure application behavior
          ↓
Document and refine
```

Controllers should coordinate requests and responses.

Business logic should be placed in focused services or domain components rather than accumulating inside controllers.

Models and repositories should manage data access without becoming responsible for unrelated presentation or request concerns.

<br>

## Architectural Discipline

Recommended dependency direction:

```text
Routes
  ↓
Controllers
  ↓
Application Services
  ↓
Domain Logic
  ↓
Repositories and Infrastructure
```

Avoid dependency flows such as:

```text
Model → Controller
Service → Controller
View → Database
Infrastructure → Application UI
```

Architectural boundaries should remain explicit, testable, and enforceable.

<br>

---

## Use Cases

Vinexel is designed for systems such as:

### Multi-Brand Platforms

Operate several related brands from one shared framework foundation.

### SaaS Applications

Serve multiple organizations or tenants while preserving data and access isolation.

### E-Commerce Ecosystems

Connect storefronts, account systems, payment services, administration, and supporting applications.

### Single Sign-On Networks

Provide shared identity across several authorized projects and domains.

### Enterprise Applications

Develop modular operational systems with centralized infrastructure and controlled project boundaries.

### Developer Platforms

Build interconnected tools, APIs, dashboards, marketplaces, and development services.

<br>

---

## Project Status

Vinexel Framework is under active development.

The architecture, APIs, internal components, and documentation may continue to evolve as the framework is tested, measured, and refined.

Production adoption should include:

* version pinning;
* automated testing;
* security review;
* database backups;
* deployment rollback procedures;
* and environment-specific validation.

<br>

## Documentation

Official documentation is currently being developed.

Planned documentation includes:

* installation;
* configuration;
* application lifecycle;
* routing;
* controllers;
* services;
* middleware;
* database access;
* authentication;
* sessions;
* caching;
* Redis;
* templating;
* CLI commands;
* testing;
* deployment;
* multi-project architecture;
* multi-domain routing;
* and tenant isolation.

<br>

## Contributing

Vinexel welcomes contributions that improve:

* correctness;
* security;
* performance;
* maintainability;
* documentation;
* testing;
* accessibility;
* and developer experience.

Contributions should follow the scientific and engineering principles of the project:

1. Clearly define the problem.
2. Explain the proposed solution.
3. Include tests where applicable.
4. Document architectural consequences.
5. Avoid unnecessary complexity.
6. Provide measurements for performance-related claims.
7. Preserve compatibility unless a breaking change is explicitly justified.

<br>

## Responsible Innovation

Vinexel encourages experimentation while maintaining engineering responsibility.

New capabilities should be assessed according to:

* practical usefulness;
* security implications;
* resource efficiency;
* maintainability;
* compatibility;
* accessibility;
* and long-term ecosystem impact.

The objective is not to add the greatest number of features.

The objective is to create the strongest coherent foundation.

<br>

---

## Official Links

| Resource             | Link                               |
| :------------------- | :--------------------------------- |
| **Website**          | [vinexel.com](https://vinexel.com) |
| **Documentation**    | Coming soon                        |
| **Framework Author** | Elwira Perdana                     |
| **Ecosystem**        | Vinexel                            |
| **License**          | MIT License                        |

<br>

## Support Vinexel

Vinexel grows through independent research, responsible engineering, documentation, experimentation, open-source collaboration, and ecosystem sponsorship.

Sponsorship helps support:

* continued framework development;
* architectural research;
* documentation;
* testing infrastructure;
* security improvement;
* developer tools;
* and long-term ecosystem sustainability.

<div align="center">

### [Support the Vinexel Ecosystem](https://vinexel.com/sponsor)

**Support the research. Advance the framework. Strengthen the ecosystem.**

</div>

<br>

---

## License

Vinexel Framework is open-source software licensed under the **MIT License**.

See the [`LICENSE`](LICENSE) file for the complete license terms.

<br>

<div align="center">

### VISION · SCIENCE · INNOVATION · EXCELLENCE

**Think differently. Engineer scientifically. Build the Vinexel way.**

<br>

© VINEXEL — **Vivid Innovation for Excellence**

</div>
