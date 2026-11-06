# Hasan Kazemi

Java backend engineer (Spring Boot) based in Deventer, Netherlands.
Master ICT: Software Engineering student at Saxion University of Applied Sciences (Sep 2026 – Jul 2027).

**Looking for a graduation internship from February 2027**, and for backend / Java roles in the Netherlands after I graduate in July 2027.

- 3 years building Java/Spring Boot systems for a regional electric utility:
  a maintenance platform for 180 high-voltage substations (~29,700 equipment records),
  a configurable test-sheet and workflow engine (148 test sheets, 860 service codes)
  and the backend of a vehicle dispatch system with live GPS tracking and routing.
- Freelance in 2026: a multi-tenant fuel-station platform (Next.js, TypeScript) and a Python/FastAPI edge gateway that streams live data from on-site devices to the cloud.

**Stack:** Java · Spring Boot · Spring Security · Spring Data JPA/Hibernate · PostgreSQL/PostGIS · Kafka · RabbitMQ · Flyway · Redis · Maven · Docker · JUnit 5 · Mockito · Testcontainers · GitHub Actions · Prometheus · Grafana · Python/FastAPI · React/Next.js · TypeScript

## Currently building: [GridWatch](https://github.com/hapiKzm/gridwatch)

An event-driven substation monitoring system that explores how the domain I worked in can be built today.

- 3 Spring Boot services: sensor readings stream through **Kafka**, out-of-limit readings become work orders in **PostgreSQL**, technicians are notified through **RabbitMQ**
- Idempotent consumers, dead-letter topic and queues, Flyway migrations
- Unit and integration tests with Testcontainers (real PostgreSQL, Kafka and RabbitMQ)
- GitHub Actions CI, Docker Compose, monitoring with Prometheus and Grafana

Work in progress: the [README](https://github.com/hapiKzm/gridwatch#readme) shows what works today and what is on the roadmap.

## Projects built with my brother ([@OhapPyO](https://github.com/OhapPyO))

We develop these together; the repositories live on his account.

| Project | What it is | Stack |
|---|---|---|
| [behtaTahvie-server](https://github.com/OhapPyO/behtaTahvie-server) | Backend API for the BehtaTahvie suite: business logic, authentication and data access. I am the main contributor to this repository. | Java, Spring Boot, Spring Security, Spring Data JPA, PostgreSQL, Redis, Thymeleaf |
| [behtaTahvie-web](https://github.com/OhapPyO/behtaTahvie-web) | User-facing web app of the same suite, built on the server API | HTML, CSS, JavaScript |
| [behtaTahvie-dashboardPanel](https://github.com/OhapPyO/behtaTahvie-dashboardPanel) | Internal admin panel for operational management | JavaScript, HTML, CSS |
| [menusaz](https://github.com/OhapPyO/menusaz) | Scraper that detects each restaurant-menu page template, routes it to the right parser and outputs clean JSON, with failed URLs logged separately | Python, Selenium |
| [Linktree](https://github.com/OhapPyO/Linktree) | Linktree-style SaaS: user profiles, drag-and-drop link management, page customisation, subscription plans and billing UI | Next.js 15, React 19, TypeScript, Convex, Clerk, Tailwind CSS |

## Contact

hapi.kzm@gmail.com · [LinkedIn](https://www.linkedin.com/in/hasan-kazemi-a0660b22a/)
