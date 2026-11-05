# Rares Iacob

**Software Developer | Java / Spring Boot Backend**

Timișoara, Romania · [raresiacob26@gmail.com](mailto:raresiacob26@gmail.com) · [GitHub](https://github.com/raresiacob3) · [LinkedIn](https://www.linkedin.com/in/rares-iacob-755380230/) · [PDF version](CV.pdf)

## Profile

Software developer with automotive Embedded C experience and a background in production troubleshooting, focused on Java/Spring Boot backend development. Built and published ScentVault (iOS and Android) with AI-based image recognition, cloud APIs and subscription billing, and built JobPilot, a multi-user Spring Boot/PostgreSQL application with rotating JWT refresh tokens and versioned Flyway migrations. Adding Python/FastAPI and LLM integration to my backend toolkit.

## Technical Skills

- **Backend:** Java 17/21, Spring Boot 3, Spring Security, JPA/Hibernate, REST APIs, Python, FastAPI, Node.js/Express
- **Data:** PostgreSQL, SQL, Flyway, Alembic, MongoDB, Firebase Auth/Firestore
- **Frontend & mobile:** React, TypeScript, React Native/Expo
- **DevOps & testing:** Docker, Docker Compose, GitHub Actions, Google Cloud Run, JUnit, Mockito, pytest, Git, OpenAPI
- **AI:** OpenAI API (text, vision), BM25 document retrieval, retrieval evaluation (recall@k, MRR), LLM explanations with citations; ComfyUI and LoRA training (experiments)
- **Embedded:** Embedded C, AUTOSAR, VectorCAST, Google Test, CANoe, DaVinci, Wireshark

## Selected Projects

### [JobPilot](https://github.com/raresiacob3/jobpilot) — Full-Stack Job Application Tracker

*Java 21 · Spring Boot 3 · Spring Security · PostgreSQL · Flyway · React · TypeScript · Docker*

- Built a multi-user REST API with JWT access tokens and server-side refresh token rotation with reuse detection, access roles and strict per user data isolation (another user's resources return 404).
- Enforced the application pipeline as a server-side state machine (invalid transitions return 409) and recorded activity events in the same transaction as each change.
- Versioned the schema with Flyway (Hibernate validate mode), used grouped aggregate queries instead of N+1 for analytics, and shipped multi-stage Docker builds, Docker Compose and OpenAPI docs.
- Wrote unit tests (JUnit, Mockito) for the status state machine, service rules and JWT handling.

### ScentVault — Published AI-Powered Perfume Tracking App (App Store + Google Play)

*React Native · Expo · TypeScript · Node.js · Firebase · OpenAI API · Google Cloud Run · RevenueCat*

- Built and released a mobile product on iOS and Android for fragrance recognition, collections, wishlists and statistics.
- Integrated AI-based image recognition returning structured matches with confidence signals, Firebase authentication, a cloud-hosted backend and RevenueCat subscription billing.
- Managed EAS production builds, app store submissions and review cycles.

### [Supplier Intelligence](https://github.com/raresiacob3/supplier-intelligence) — Python Backend & Applied AI

*Python · FastAPI · SQLAlchemy · PostgreSQL · Alembic · Pydantic · pytest · Docker · OpenAI Responses API*

- Built a FastAPI/PostgreSQL service that ranks suppliers with a deterministic weighted score computed in a single SQL query, with a per-criterion breakdown; CSV ingestion validates every row with Pydantic and runs off the async event loop.
- Implemented BM25 retrieval over chunked supplier documents feeding an optional LLM explanation endpoint with document citations; measured retrieval offline on a golden set (recall@1 0.9, MRR 0.9), enforced as a regression test.
- Versioned the schema with Alembic and added request-ID logging; 42 pytest tests (about 94% coverage) run in GitHub Actions on SQLite and PostgreSQL, plus a Docker Compose smoke test. AI-assisted, synthetic data, not deployed.

### Additional projects

- **[MemoryVials](https://github.com/raresiacob3/MemoryVials)** (Java 17, Spring Boot, MongoDB): perfume e-commerce backend with catalog, cart, stock checks, checkout and order tracking.
- **[Questify](https://github.com/raresiacob3/questify)** (Java, Spring Boot, React): gamified task manager with quests, XP, difficulty levels and filtering.
- **Generative AI experiments** (ComfyUI, FLUX.2 Klein, SDXL, SimpleTuner, RunPod): trained a custom LoRA on a cloud GPU and built diffusion workflows.

## Professional Experience

### Technical Consultant — The Access Group
*Jan 2024 – Present · previously Associate Technical Engineer*

- Investigate complex production incidents in ConQuest and EasyBuild: application defects, data integrity, file corruption, licensing and client environment configuration.
- Use SQL, application logs and controlled database operations to isolate root causes and validate data.
- Reproduce defects and document findings for second-line support and engineering/QA teams; deliver remote sessions and technical explanations to customers.

### Junior Software Developer — Magna Electronics
*Dec 2022 – Jan 2024*

- Developed Embedded C functionality for the Imaging22 automotive radar sensor platform, including a board heater component from detailed design through implementation and unit testing.
- Authored Detailed Design Documents, took part in engineering reviews and project audits, and documented implementation and verification decisions.
- Designed and ran unit tests with Google Test and VectorCAST; investigated failures and debugged in Visual Studio.
- Automated engineering tasks with Python scripts and contributed to internal REST APIs and tooling; worked with Git, Jira and CI/CD.

### AUTOSAR Intern — FEV ECE
*Jul 2022 – Dec 2022*

- Implemented and updated AUTOSAR application modules in Embedded C with CANoe and DaVinci.
- Built Python test and engineering utilities and analyzed Ethernet traffic with Wireshark.

## Education

**B.Sc. Computer Engineering** — Politehnica University Timișoara (2020–2024)

## Additional

- **Languages:** Romanian (native), English (advanced)
- **Volunteering:** Intel Liga AC Labs; Developer Students Club; Timișoara 2023 – European Capital of Culture
