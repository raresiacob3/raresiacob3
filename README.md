# Rares Iacob

**Software developer · Java / Spring Boot backend · Python and LLM integration**

I build backend services and ship complete products. I started in automotive embedded software (Embedded C, AUTOSAR, a radar-sensor platform at Magna), then moved into production troubleshooting with SQL and logs at The Access Group. I'm looking for a junior backend developer role.

📄 [CV (PDF)](CV.pdf) · [CV (web)](CV.md) · [LinkedIn](https://www.linkedin.com/in/rares-iacob-755380230/) · [Email](mailto:raresiacob26@gmail.com)

---

## Featured projects

### [JobPilot](https://github.com/raresiacob3/jobpilot) · Java 21 · Spring Boot 3 · PostgreSQL · React

Multi-user job application tracker.
- JWT access tokens with server-side refresh-token rotation and reuse detection
- Pipeline enforced as a server-side state machine (invalid transitions return 409)
- Per-user data isolation (another user's resources return 404), Flyway migrations, grouped analytics queries instead of N+1
- Docker Compose setup, OpenAPI docs, JUnit/Mockito tests

### ScentVault · React Native · Firebase · Cloud Run · OpenAI · published on iOS and Android

Perfume tracking app live on the App Store and Google Play: image-based fragrance recognition with confidence signals, collections, wishlists, Firebase auth and RevenueCat subscriptions. I handled the production builds and store reviews.

### [Supplier Intelligence](https://github.com/raresiacob3/supplier-intelligence) · Python · FastAPI · PostgreSQL · Alembic

Explainable supplier ranking with optional document-grounded LLM explanations.
- Deterministic weighted ranking computed in one SQL query, with a per-criterion breakdown
- BM25 retrieval over supplier documents, measured offline (recall@1 0.9, MRR 0.9) and enforced as a regression test
- 42 pytest tests run in CI on SQLite and PostgreSQL, plus a Docker Compose smoke test

---

## Also built

- [Questify](https://github.com/raresiacob3/questify): gamified task manager (Spring Boot, React)
- [MemoryVials](https://github.com/raresiacob3/MemoryVials): perfume shop backend with cart, stock checks and orders (Spring Boot, MongoDB)
- [Doc-Droid](https://github.com/raresiacob3/doc-droid): Raspberry Pi robot with gesture recognition and line following (Python, OpenCV)

## Stack

**Backend:** Java, Spring Boot, Spring Security, JPA/Hibernate, Python, FastAPI · **Data:** PostgreSQL, SQL, Flyway, Alembic, MongoDB · **Frontend:** React, TypeScript, React Native · **Delivery:** Docker, GitHub Actions, JUnit, Mockito, pytest · **Embedded:** Embedded C, AUTOSAR, VectorCAST, Google Test
