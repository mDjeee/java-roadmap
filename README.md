# java-roadmap

### From Angular FE → Java Mid in 12 months

| Phase                              | Weeks | Key Goals                                                                                                    | Output / Checkpoint                                    |
| ---------------------------------- | ----- | ------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------ |
| **0. Setup & Mind-Shift**          | 1     | • Install JDK 21 + IntelliJ • `git init java-roadmap` repo • Read “Why Java Still Matters (2024)”            | “Hello World” pushed to GitHub + CI via GitHub Actions |
| **1. Core Java Essentials**        | 4     | • Syntax refresh (primitives, flow, scope) • OOP (classes vs records, `final`, `sealed`) • Exceptions, enums | Mini-project: CLI **BMI calculator** with unit tests   |
| **2. Collections + Generics**      | 3     | • `List`, `Set`, `Map` internals • PECS rule & wildcards                                                     | Kata: in-memory **LRU cache**                          |
| **3. Lambdas & Streams**           | 2     | • Functional interfaces • Stream pipelines & collectors • `Optional`, method refs                            | Task: **CSV parser** → aggregate stats in one stream   |
| **4. Concurrency Basics**          | 3     | • `Thread`, `ExecutorService`, `CompletableFuture` • `volatile`, atomics, locks                              | Exercise: **parallel web-scraper** (fetch page titles) |
| **5. Build, Test, Document**       | 2     | • Maven → **Gradle Kotlin DSL** • JUnit 5, Mockito • OpenAPI Generator                                       | ≥ 80 % test coverage on prior projects                 |
| **6. Spring Boot Fundamentals**    | 5     | • DI & profiles • Spring MVC REST + validation • H2 + Spring Data JPA                                        | Service 1: CRUD **“Workout” API** with Swagger UI      |
| **7. Persistence & Transactions**  | 3     | • JPA pitfalls • Flyway migrations • Query tuning                                                            | Add **PostgreSQL** (Docker) + Flyway                   |
| **8. Security & Observability**    | 3     | • Spring Security 6 (JWT, method auth) • Actuator, Micrometer, Prometheus/Grafana                            | Secure Workout API + `/actuator` health checks         |
| **9. Docker, CI/CD, Cloud**        | 4     | • Multi-stage Dockerfile • Docker Compose stack • GitHub Actions → Deploy (DigitalOcean/AWS Lightsail)       | Live API at **api.yourdomain.dev**                     |
| **10. Micro-Patterns & Messaging** | 4     | • Kafka basics + Spring for Kafka • Resilience4j (circuit breaker) • Idempotency & retries                   | Service 2: Event-driven **“Workout Completed” feed**   |
| **11. Capstone Full-Stack**        | 4     | Combine your Angular chops: build dashboard consuming both services                                          | Deployed demo + README + architecture diagram          |


