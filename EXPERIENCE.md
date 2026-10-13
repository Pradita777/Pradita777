# Andrés Prada Rodríguez

**Full-Stack Developer** · Medellín, Colombia
[LinkedIn](https://www.linkedin.com/in/TU-USUARIO-LINKEDIN) ·
[andres123prada@gmail.com](mailto:andres123prada@gmail.com) ·
[← back to profile](https://github.com/Pradita777)

---

## Experience

### Full-Stack Developer · IDEA — Instituto para el Desarrollo de Antioquia
*2026 – Present*

On-premise systems built with **.NET 10** to improve institutional processes at
a public development agency.

- Delivered the strategic investments service, now in production.
- Drive cross-cutting technical initiatives beyond assigned feature work:
  introducing Git-based version control practices to the team, and researching
  locally-hosted LLMs for document data extraction as a zero-marginal-cost
  alternative to paid APIs.

### Full-Stack Developer (Contractor) · RobotMade / Cartoro Inversiones S.A.S.
*2026 · SGDEA project*

Electronic document management system (SGDEA) for a public-sector client —
administration, storage, querying and processing of institutional documents.

- Analyzed functional and technical requirements, estimated delivery times, and
  built features across frontend and backend.
- Implemented and adjusted **REST API integrations** connecting user
  interfaces, backend services and document storage components.
- Managed and fixed **CI/CD pipelines with GitHub Actions**: dependency
  installation, code validation, builds and branch-based deployments.
- Supported containerized builds and deployments with **Docker and AWS**,
  monitoring QA and production environments.
- Diagnosed discrepancies between QA and production deployments by auditing
  workflows, branches, Docker images, environment variables and pipeline steps.
- Proposed technical improvements and reported progress, findings and blockers
  to the development team.

### Software Developer (Contractor) · XM S.A. E.S.P. — Expertos en Mercados
*2025 – 2026*

National energy market operator.

- Built **5+ custom visualization symbols in Angular** for PI Vision, rendering
  data from PI Asset Framework.
- Implemented data capture and visualization logic on the **AVEVA PI System**
  platform.
- Implemented a continuous monitoring system for alert management.
- Documented 3+ robust components and 3+ Asset Framework data models —
  structure, behavior and visualization — to make them maintainable by others.
- Used AI-assisted development tooling (Claude, Codex, ChatGPT, GitHub Copilot)
  for development, debugging, documentation and code review.

### Software Engineering Intern · XM S.A. E.S.P. — Economic Dispatch Team
*2024 – 2025*

- Migrated a complex Excel macro to a **Django** web application, cutting
  processing time from **30 minutes to 3** — an **85% improvement**.
- Guaranteed functional parity between the legacy solution and the new
  application.
- Contributed to the internal *Gerenciainador* application.

---

## Projects

<!-- VERIFICA los nombres marcados con ??? y corrige la URL.
     Borra cualquier fila cuyo repo no este publico. -->

### [User API](https://github.com/Pradita777/users-magnament) · C# / .NET 10

[Live demo](http://20.246.43.9:8080/swagger/index.html) ·
[Docker Hub](https://hub.docker.com/r/pradita777/users)

REST API that generates users from an external provider, persists them with
hashed passwords, and validates credentials.

- **Swappable persistence**: in-memory and file-based stores coexist in the
  code; the active one is chosen at startup from configuration, environment
  variable or CLI argument, with no rebuild.
- **121 unit tests (xUnit)** covering duplicate usernames, path traversal,
  corrupted files, case-insensitive lookups and every endpoint's status codes.
  External HTTP calls are faked so unforceable failure modes stay reproducible.
- **PBKDF2-SHA256, 100 000 iterations**, per-user salt. Hashing happens in one
  place; responses never expose the password, not even hashed.
- **Multi-stage Dockerfile**, 95 MB runtime image, non-root user, published to
  Docker Hub and deployed on an Azure VM.
- Documents its design decisions and its deliberate limitations.

### [Retail HyperAutomation](https://github.com/Pradita777/Retail-HyperAutomation-Solution) · Python
NLP product recommendation engine using semantic search.

- Semantic search engine over **FAISS** indexes with **SentenceTransformers**
  embeddings, processing ~10,000 characters.
- Backend in **FastAPI** exposing `POST /recommend`.
- Local LLMs served through **Ollama**.
- Embedding generation and persistence pipeline from CSV, cutting indexing time
  by **60%**.
- Web interface in HTML + JavaScript.

### [franchise-api](https://github.com/Pradita777/???) · Java 21
Reactive REST API for franchise and branch management.

- **Spring WebFlux** with non-blocking reactive persistence on **MongoDB**.
- Containerized with Docker and deployed on **GCP**.

### [Pokédex Web App](https://github.com/Pradita777/???) · Node.js
Distributed deployment exercise.

- Node.js server serving random Pokémon images.
- **4 Docker images** for redundancy, targeting 99.9% availability.
- Distributed deployment on **GCP** behind a single domain, handling **500+
  concurrent requests**.
- Configured persistence and routing rules for high availability.

### [Parallel Image Processing](https://github.com/Pradita777/???) · C++
Image processing through matrix transformations and parallelization.

- Linear-algebra transformations: translation, scaling, rotation, shearing,
  reflection.
- BMP manipulation with custom structures and manual memory management.
- Sequential, multithreaded and multiprocess execution — **3.2× speedup** over
  sequential.

### [Django5FI](https://github.com/Pradita777/Django5FI) · Python
Learning project following *Django 5 for the Impatient* — model-view-template
architecture, CRUD, authentication, permissions and ORM usage.

---

## Technical Skills

**Languages &amp; Frameworks**
C#, .NET, ASP.NET Core · Java, Spring Boot, WebFlux · Python, Django, FastAPI ·
JavaScript, TypeScript, Angular, Node.js · C++ · PHP, Laravel · SQL

**Cloud &amp; DevOps**
Azure, Azure DevOps · Google Cloud Platform · AWS (EC2, ECR, IAM) · Docker &amp;
Docker Compose · GitHub Actions · CI/CD pipeline construction · QA and
production environment management · Git, Git Flow

**Databases**
PostgreSQL · SQL Server · MongoDB · SQLite

**Data &amp; Analysis**
Pandas, NumPy, Polars · Matplotlib, Seaborn, Plotly · Power BI · Advanced SQL ·
ETL/ELT · EDA, data cleaning and transformation · Machine learning models, time
series · Jupyter, R, Matlab

**Automation**
Python scripting · Report automation · Batch processing · PowerShell, Bash ·
Power Automate · API integrations · Task scheduling

**Architecture**
REST APIs · Microservices concepts: API Gateway, service separation, Circuit
Breaker, Service Discovery, Event-Driven Architecture, Saga

**Specialized Software**
AVEVA PI System (advanced) · DIgSILENT PowerFactory (intermediate) · Unity
(intermediate)

**AI-Assisted Development**
Claude, GitHub Copilot, Codex, ChatGPT · Prompt engineering · LLM-assisted code
review and debugging · Local LLM deployment with Ollama

**Methodologies**
Scrum · Kanban · Agile development · Git Flow

---

## Education

**Universidad EAFIT** — Medellín, Colombia

**Specialization in Software Development** — in progress, completion Dec 2026

**Systems Engineering** — 2025
Relevant coursework: Operating Systems, Software Development, Data Structures
and Algorithms, Information Systems, Applied Machine Learning

---

## Languages

Spanish (native) · English (B2)
