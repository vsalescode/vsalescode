<div align="center">

# João Victor Sales

**Backend Developer · Java & Spring Boot · Node.js · Real-time systems**

Brazil · Open to backend roles (junior / internship), remote or hybrid

<a href="https://linkedin.com/in/vsalescode"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="https://portfolio-vsalescode.vercel.app"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" /></a>
<a href="mailto:vsalescode@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>

</div>

## About

I build backend systems: REST APIs, authentication, data pipelines and real-time features. My main stack is Java with Spring Boot, and I also work with TypeScript and Node.js.

During my internship I built a data pipeline that ingests, normalizes and validates about 2 million records into PostgreSQL, and tuned the queries behind it with indexes and caching. Outside work, I keep shipping complete projects end to end, from database design to tests and documentation.

Software Engineering student at UNINTER.

## Projects

<table>
<tr>
<td width="50%" valign="top">

### [Mini ERP](https://github.com/vsalescode/mini-erp)
Stock and sales API, built module by module (in progress).

`Java 21` `Spring Boot` `PostgreSQL` `Flyway` `Testcontainers` `Docker`

Modular hexagonal architecture documented in an ADR, versioned migrations with Flyway and integration tests running against a real PostgreSQL through Testcontainers.

</td>
<td width="50%" valign="top">

### [AppyFlow](https://github.com/vsalescode/appyflow)
Self-hosted assistant that finds job openings, scores how well they match your profile and generates tailored résumés in LaTeX/PDF.

`TypeScript` `Next.js` `Prisma` `PostgreSQL` `Zod` `Vitest` `Docker`

Résumé parsing with LLM structured output, where every extracted fact keeps a quote from the original as evidence. Argon2 auth and a search worker with pluggable providers.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Nilo](https://nilovoice.vercel.app)
Desktop app for voice chat and communities, with screen sharing.

`TypeScript` `React` `Electron` `Fastify` `Socket.IO` `WebRTC` `PostgreSQL` `Prisma`

Real-time voice and screen sharing over WebRTC, presence and channels over Socket.IO, JWT auth and a Windows installer.

</td>
<td width="50%" valign="top">

### [API Vendas BI](https://github.com/vsalescode/api-vendas-bi)
Sales API with a monthly revenue dashboard.

`Java 21` `Spring Boot` `PostgreSQL` `MapStruct` `Bean Validation`

Paginated and filtered endpoints, error handling and a dashboard that reads from a PostgreSQL view, so the aggregation lives in the database.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [netblame](https://github.com/vsalescode/netblame)
Finds where your connection is failing: your PC, the router, the ISP or the route to the server.

`Python` `Windows` `Networking`

Probes gateway, DNS, TCP and each hop of the route in parallel, then blames the failing segment by elimination. Generates a single bilingual HTML report, with no admin rights and no external dependencies.

</td>
<td width="50%" valign="top">

### [Iris](https://github.com/vsalescode/iris)
Voice assistant for Windows that handles files and Gmail and remembers past conversations.

`Python` `FastAPI` `WebSocket` `Gemini Live` `SQLite` `Three.js`

Real-time voice over WebSocket, function calling behind a permission system with confirmation for irreversible actions, long-term memory in SQLite and a WebGL interface.

</td>
</tr>
</table>

Also worth a look: [microservices with Spring Boot and OpenFeign](https://github.com/vsalescode/bff-agendador-tarefas) (BFF + user, task and notification services, PostgreSQL and MongoDB).

## Experience

**Hiwis** · Software Development & AI Intern · Mar 2026 – Aug 2026
- Built REST APIs in Node.js and Java with authentication, JWT access control, filters and pagination.
- Built a data pipeline (ingestion, transformation, normalization, validation) that loads ~2 million records into PostgreSQL, and optimized its SQL with indexes and in-memory caching.
- Automated business flows with n8n, webhooks and external APIs.
- Built React + TypeScript screens and wrote automated tests with Jest.

**Freelance developer** · Jun 2020 – Aug 2025
- Websites, landing pages, Discord bots, Lua scripts and API integrations for clients, plus bug fixing, refactoring and performance work.

## Stack

<img src="https://skillicons.dev/icons?i=java,spring,ts,nodejs,react,nextjs,python,postgres,mysql,mongodb,prisma,docker,git,postman&theme=dark" />

**Backend:** Java, Spring Boot, Node.js, Fastify, Next.js, REST, JWT, OpenFeign
**Data:** PostgreSQL, MySQL, MongoDB, Prisma, JPA, Flyway
**Real-time:** WebSocket, Socket.IO, WebRTC
**Testing & tooling:** JUnit 5, Mockito, Testcontainers, Jest, Vitest, Docker, GitHub Actions, n8n

**Languages:** Portuguese (native), English (intermediate), Spanish (basic)
