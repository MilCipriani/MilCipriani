# Milena Cipriani

I'm a fullstack developer interested in backend engineering, security, and infrastructure.

I enjoy building things with full ownership in mind: from designing APIs and databases to deploying, monitoring,
and maintaining the systems behind them. Outside of client work, I run a small homelab where I experiment with self-hosting, networking, and infrastructure.

[My Portfolio](https://milena.work/) · [LinkedIn](https://www.linkedin.com/in/milena-cipriani/)


## Technologies

- **Languages:** TypeScript, JavaScript, Python, SQL
- **Frontend:** React, Vue.js
- **Backend:** Node.js, Express.js, PostgreSQL
- **Testing:** Vitest, Supertest
- **Infrastructure:** Docker, Docker Compose, NGINX, Linux, GitHub Actions


## Work

### The Left Drawer

A self-hosted cloud storage service I designed, built, and operate for my family and friends.

The production instance runs on a Raspberry Pi and is privately accessible through ZeroTier.
There's also a public demo deployed on a VPS.

Some things I focused on:
- JWT authentication with short-lived access tokens and HttpOnly refresh cookies
- SHA-256 hashing of refresh tokens before storing them
- Authenticated image delivery for private files
- PostgreSQL transactions with rollback on failure to keep file and database operations consistent
- Unit and integration tests with Vitest and Supertest
- Multi-container setup with Docker Compose, with separate dev and production configurations

**Stack**: TypeScript · React · Node.js · Express · PostgreSQL · Docker · Nginx

[Repository](https://github.com/MilCipriani/TheLeftDrawer-Demo) · [Live Demo](https://leftdrawer-demo.milena.work)

----

### Wellness Training Center Website

I migrated this site from WordPress to a React/TypeScript application and own the project from requirements through deployment and maintenance.

- Automated deployments with GitHub Actions
- Improved Lighthouse performance from 60 to 100
- Optimized bundles, lazy-loaded resources, and compressed assets

[Live site](https://inlumine.es) · [Repository](https://github.com/MilCipriani/inlumine)

----

### Monica Giglio - Personal Branding Website

A personal branding website built for a client.

I handled the project independently, from requirements and implementation through deployment.
- Vue.js + TypeScript
- Automated deployment with GitHub Actions
- 95–100 Lighthouse scores across performance, accessibility, best practices, and SEO

[Live site](https://monicagiglio.es) · [Repository](https://github.com/MilCipriani/MonicaGiglioPortfolio)


## Currently learning

I'm expanding my homelab as a way to deepen my understanding of infrastructure and systems engineering.
I'm currently exploring areas such as automated backups and disaster recovery, infrastructure as code, observability, private networking, and container orchestration. I'm particularly interested in making self-hosted systems reproducible, measurable, and resilient.

I'm documenting what I learn through the projects and experiments I build along the way.
When something is worth talking about, it ends up on [my blog](https://milena.work/blog/).
