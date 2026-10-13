<h1 align="center">Andrés Prada Rodríguez</h1>

<p align="center">
  <b>Full-Stack Developer</b><br>
  C# · .NET · Java · Spring Boot · Python
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/TU-USUARIO-LINKEDIN">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="mailto:andres123prada123@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email">
  </a>
  <img src="https://img.shields.io/badge/Colombia-FCD116?style=flat-square&logoColor=black" alt="Colombia">
</p>

---

## About

Full-stack developer working on financial management and investment control
systems. I build REST APIs with C#/.NET and Java/Spring Boot, automate data
processing and validation pipelines in Python, and ship containerized services
to Azure and AWS.

I care about the parts that are easy to skip: unit tests that actually cover the
failure paths, configuration that makes implementations swappable without a
rebuild, and writing down *why* a design decision was made.

Client work lives in private repositories, so what you'll find here is built
from scratch — including a deployed API you can call right now.

---

## Tech Stack

**Backend**

![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=csharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-5C2D91?style=flat-square&logo=dotnet&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![WebFlux](https://img.shields.io/badge/Spring_WebFlux-6DB33F?style=flat-square&logo=spring&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![REST](https://img.shields.io/badge/REST_APIs-005571?style=flat-square)

**Frontend**

<!-- AGREGA AQUI tus tecnologias de frontend reales y borra las que no uses.
     Ejemplos de badges listos para usar: -->
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

**Testing &amp; API Docs**

![xUnit](https://img.shields.io/badge/xUnit-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![OpenAPI](https://img.shields.io/badge/OpenAPI-6BA539?style=flat-square&logo=openapiinitiative&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=flat-square&logo=swagger&logoColor=black)

**Data**

![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![OpenPyXL](https://img.shields.io/badge/OpenPyXL-217346?style=flat-square&logo=microsoftexcel&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)

**Databases**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

**DevOps &amp; Cloud**

<!-- Si un badge aparece sin icono, el slug del logo cambio en simple-icons.
     Alternativas: amazonwebservices -> amazonaws | microsoftazure -> azure
     Lista oficial de slugs: https://simpleicons.org -->

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Azure DevOps](https://img.shields.io/badge/Azure_DevOps-0078D7?style=flat-square&logo=azuredevops&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## Experience

**Full-Stack Developer** · Valor+ — IDEA (IT) · *2026 – Present*

Developing a financial management and strategic investment control system.
Backend services in Java and Spring Boot, relational data modeling, and
integration work across the platform.

**Data Processing &amp; Automation** · XM

Processed and validated business-critical information and automated recurring
tasks with Python, SQL, and Excel. Built reports and validation routines that
replaced manual review steps.

---

## Projects

### [User API](https://github.com/Pradita777/users-magnament) · C# / .NET 10

[![Live demo](https://img.shields.io/badge/Live_demo-Swagger_UI-85EA2D?style=flat-square&logo=swagger&logoColor=black)](http://20.246.43.9:8080/swagger/index.html)
[![Docker Hub](https://img.shields.io/badge/Docker_Hub-pradita777%2Fusers-2496ED?style=flat-square&logo=docker&logoColor=white)](https://hub.docker.com/r/pradita777/users)
[![Tests](https://img.shields.io/badge/tests-121_passing-brightgreen?style=flat-square)](https://github.com/Pradita777/users-magnament#pruebas)

REST API that generates users from an external provider, persists them with
PBKDF2-hashed passwords, and validates credentials. **Deployed on an Azure VM —
you can call it without cloning anything.**

- **Swappable persistence.** In-memory and file-based stores coexist in the code;
  which one runs is decided at startup from configuration, environment variable,
  or CLI argument — no rebuild.
- **121 unit tests (xUnit)** covering duplicate usernames, path traversal,
  corrupted files, case-insensitive lookups, and every endpoint's status codes.
  External HTTP calls are faked, so failure modes that can't be forced in real
  life are reproducible.
- **PBKDF2-SHA256, 100 000 iterations**, per-user salt. Passwords are hashed in
  exactly one place; responses never expose them, not even hashed.
- **Multi-stage Dockerfile**, 95 MB runtime image, non-root user, published to
  Docker Hub.

The repo documents its design decisions and its deliberate limitations — why
`ControllerBase` over `Controller`, why `Problem(403)` over `Forbid()`, and what
was consciously left out.

<!-- Agrega aqui tus otros proyectos cuando los publiques, con el mismo formato.
     Candidatos: el test de Accenture (franchise-api) y la demo de extraccion
     de PDFs con Ollama. -->

### Other work

| Project | What it does | Stack |
|---|---|---|
| **[franchise-api](https://github.com/Pradita777/NOMBRE-DEL-REPO)** | Reactive REST API for franchise and branch management: non-blocking persistence and containerized deployment. | Java 21 · Spring WebFlux · MongoDB · Docker |

---

## Foundations

Coursework repositories from my computer engineering studies — data structures,
algorithms, computer organization, and low-level programming.

![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Assembly](https://img.shields.io/badge/Assembly-6E4C13?style=flat-square)

---

## GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=Pradita777&show_icons=true&hide_border=true&include_all_commits=true&count_private=true&theme=default" alt="GitHub stats">
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Pradita777&layout=compact&hide_border=true&langs_count=8&theme=default" alt="Top languages">
</p>

---

<p align="center">
  <i>Open to backend and full-stack opportunities.</i>
</p>
