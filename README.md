<div align="center">

# Shawn Frost

**Backend engineering, systems curiosity, and the occasional late-night debugging session.**

Go · PostgreSQL · Redis · Rust · Distributed systems

<br />

<blockquote>
“The feelings that hurt most, the emotions that sting most, are those that are absurd;
the longing for impossible things, precisely because they are impossible; nostalgia for
what never was; the desire for what could have been; regret over not being someone else;
dissatisfaction with the world's existence. All these half-tones of the soul's
consciousness create in us a painful landscape.”
<br /><br />
— <b>Fernando Pessoa</b>, <i>The Book of Disquiet</i>
</blockquote>

</div>

---

## About

I'm a backend-focused developer working primarily with **Go**, with a growing interest in
systems programming, distributed services, and low-level runtime behavior. I like building
software that stays reliable under failure, concurrency, load, and continuous change—not
just software that works in a happy-path demo.

I'm still learning constantly, but I'm comfortable going beyond beginner CRUD applications:
I care about the trade-offs behind production-oriented design, useful tests, clear
observability, and systems that remain understandable as they grow.

I enjoy turning complex system behavior into clear mental models, and I like sharing what I
learn through projects that are practical, measurable, and built to evolve.

## Comfort zone 1

<table width="100%">
  <tr>
    <td width="50%" align="center">
      <img src="./assets/kimishinu-1.gif" width="100%" alt="Comfort zone 1, left" />
    </td>
    <td width="50%" align="center">
      <img src="./assets/kimishinu-2.gif" width="100%" alt="Comfort zone 1, right" />
    </td>
  </tr>
</table>

## What I Know

- **Go backend development:** HTTP APIs, `chi`, middleware, authentication, OAuth2,
  background workers, request lifecycles, concurrency, and error handling
- **Data systems:** PostgreSQL, `pgx/pgxpool`, Squirrel, `sqlc`, Atlas migrations,
  relational modeling, constraints, indexes, transactions, and Redis
- **Service architecture:** gRPC, Protocol Buffers, Go/Rust service boundaries,
  asynchronous jobs with River, retries, idempotency, and graceful shutdown
- **Testing and reliability:** unit and integration tests, Testcontainers, race detection,
  HTTP handler and middleware testing, failure-oriented cases, and CI-based validation
- **State and async tooling:** Redis-backed sessions with `go-redis`, scheduled/async job
  execution with River, and resilient retry/error workflows
- **Security-minded backend work:** sessions, token handling, OAuth2 flows, webhook
  verification, input validation, and defensive error handling
- **Infrastructure:** Docker Compose, GitHub Actions, Terraform/OpenTofu, Jenkins and
  GitLab CI/CD workflows, and Trivy image/filesystem scanning
- **Observability:** structured logging with zerolog, Grafana Alloy, Loki, Grafana,
  contextual errors, cardinality awareness, and continued exploration of Prometheus
  and OpenTelemetry
- **Engineering habits:** schema evolution, clean service boundaries, readable APIs,
  reproducible environments, and debugging systems under concurrency, failure, and load

I don't measure engineering by the number of tools I can list. I care about understanding
why a system behaves the way it does, choosing the simplest design that holds up under
pressure, and writing tests that catch meaningful regressions instead of inflating a
coverage percentage.

## Current Project

**Prolepsis** is a developer-data ETL and
context engine. It collects and normalizes activity from services such as GitHub, stores
structured data in PostgreSQL, and exposes it as context for future AI interactions.

The project brings together a Go API, GitHub OAuth and webhook ingestion, Redis sessions,
River jobs, Atlas and sqlc, a Rust PDF-processing gRPC sidecar, Docker Compose, integration
tests, and separate Go/Rust CI pipelines.

## Comfort zone 2

<table width="100%">
  <tr>
    <td width="50%" align="center">
      <img src="./assets/cpk-1.gif" width="100%" alt="Comfort zone 2, left" />
    </td>
    <td width="50%" align="center">
      <img src="./assets/cpk-2.gif" width="100%" alt="Comfort zone 2, right" />
    </td>
  </tr>
</table>

> Comfort-zone GIFs were made by me (inspired by <a href="https://giphy.com/channel/kattayan_46/">kattayan_46</a>).
>
> The finale GIF is from <a href="https://giphy.com/kilianimes">kilianimes on GIPHY</a>.

## What I'm Learning Next

Better test design, deeper Go runtime and concurrency knowledge, more intentional telemetry,
and practical distributed-systems design shaped by real failures rather than diagrams alone.

---

<div align="center">

## She looks so me

<img src="./assets/so-me.gif" width="360" alt="She looks so me" />

</div>
