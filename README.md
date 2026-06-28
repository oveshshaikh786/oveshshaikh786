<div align="center">

![Header](https://capsule-render.vercel.app/api?type=rect&color=0,10,20&height=130&text=Ovesh%20Shaikh&fontSize=54&fontColor=E6EDF3&fontAlign=50&fontAlignY=48&desc=Backend%20Software%20Engineer%20%E2%80%A2%20Java%20%E2%80%A2%20Spring%20Boot%20%E2%80%A2%20REST%20APIs&descSize=15&descAlign=50&descAlignY=72&descColor=8B949E)

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/oveshshaikh786/)
[![GitHub](https://img.shields.io/badge/GitHub-161B22?style=flat-square&logo=github&logoColor=white)](https://github.com/oveshshaikh786)
![Views](https://komarev.com/ghpvc/?username=oveshshaikh786&color=58A6FF&style=flat-square&label=Profile+Views)

</div>

---

## 👋 About Me

Backend Software Engineer with ~1 year of experience building REST APIs with Java and Spring Boot.

I care about more than just making things work — I care about *why* they work, and *why* they break. My focus is on understanding request flow end-to-end, designing APIs that hold up beyond the happy path, and debugging issues across layers: application logic, database behavior, and infrastructure configuration.

I'm equally comfortable reading logs on a production EC2 instance as I am reviewing a Spring Security filter chain or a Flyway migration script.

---

## 🧠 How I Think About Backend Systems

> *Code is the easy part. Understanding the system is the hard part.*

- **Trace first, fix second** — I follow requests from Controller → Service → Repository → DB before touching a line of code
- **Validation is a contract** — APIs should reject bad input at the boundary, not propagate it downstream
- **Real environments expose real bugs** — I test against Docker-composed services, not just local mocks
- **Maintainability > cleverness** — clear layering and explicit error handling age better than terse code

---

## ⚙️ Tech Stack

### 🧩 Backend & Languages
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/SpringBoot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![REST API](https://img.shields.io/badge/REST-API-blue?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

### 🗄️ Databases
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-00758F?style=for-the-badge&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)

### 🛠️ Tools & DevOps
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)

### 🎯 Frontend
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)

---

## 🚀 Featured Projects

### ⭐ [QuizzApp — Full-Stack OAuth2 Cloud Application](https://github.com/oveshshaikh786/fullstack-oauth2-app)

A production-ready full-stack application with secure social login, containerized services, and live AWS deployment — built to reflect how real backend systems are designed and operated.

`Spring Boot 3` `React 18` `Spring Security` `PostgreSQL` `Docker` `AWS EC2` `GitHub Actions` `JWT` `Flyway`

- Designed a Spring Boot 3 REST API with OpenAPI/Swagger documentation, securing all routes via Spring Security with role-based access (`USER` / `ADMIN`)
- Implemented OAuth2 social login (Google & GitHub) with JWT access + refresh token rotation for fully stateless session management
- Managed schema evolution with Flyway migrations on PostgreSQL; local dev stack runs entirely via Docker Compose
- Deployed containerized backend and frontend to AWS EC2 behind an Nginx reverse proxy; provisioned HTTPS via Let's Encrypt/Certbot
- Automated Docker image builds and release workflow with GitHub Actions CI/CD

---

### 🚆 [TrackNova — Train Ticket Booking System](https://github.com/oveshshaikh786/trackNova)

Backend system modelling a real-world ticket booking flow with strict layered architecture.

`Java` `Spring Boot` `REST API` `Layered Architecture`

- Implemented a clean Controller → Service → Repository separation with clear responsibility boundaries at each tier
- Designed a booking workflow covering seat availability, reservation state transitions, and ticket confirmation logic
- Structured for extensibility — adding new routes or seat classes requires no changes to existing layers

---

### 🐯 [Zoo Management System](https://github.com/oveshshaikh786/zoo-management-system-java)

Java OOP project modelling a zoo with a Swing desktop UI and a live web version — demonstrating interface design, inheritance, and serialization in practice.

`Java` `Swing` `OOP` `Interfaces` `Serialization` `HTML/CSS/JS` `GitHub Pages`

- Designed with an abstract `Animal` base class and `Walk`, `Swim`, `Eat` interfaces — each animal implements only the behaviors it's capable of, enforcing correct OOP boundaries
- Identified and resolved 6 bugs across 5 source files: missing input validation, redundant interface declarations, broken `toString()` output, and a placeholder parsing bug in the Swing UI
- Built a full Swing desktop UI: per-animal entry forms, live stat cards, a comparison table, and a timestamped activity log
- Shipped a companion web version with dynamic per-animal themes (safari amber → ocean blue → arctic ice) that transition on tab click

🌐 **[Live Demo](https://oveshshaikh786.github.io/zoo-management-system-java/)**

---

### 🎓 [University Course Management](https://github.com/oveshshaikh786/university-course-management-java)

Java project demonstrating clean architecture and GoF design patterns applied to a realistic domain.

`Java` `Clean Architecture` `Factory Pattern` `Observer Pattern` `Singleton Pattern`

- Architected a 5-layer system (Presentation → Business Logic → Service → Repository → Data) with strict separation of concerns — each layer communicates only with its immediate neighbor
- Applied three GoF patterns with clear justification: Factory for decoupling object creation, Observer for event-driven enrollment notifications, Singleton for consistent shared service lifecycle management

---

## 💼 Professional Experience

In my current backend role, I work on systems that go beyond toy examples:

- Developing and maintaining REST APIs under real usage conditions — not just greenfield features
- Tracing failures end-to-end: from HTTP response codes back through service layers, query plans, and Docker networking
- Handling database connectivity issues, migration conflicts, and environment-specific configuration in Docker-based setups
- Diagnosing backend failures in staging and production before they reach users

> *Codebases are private, but the patterns and problems I solve are reflected directly in my open-source projects.*

---

## 📊 GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=oveshshaikh786&show_icons=true&theme=github_dark&hide_border=true&bg_color=0D1117&title_color=58A6FF&icon_color=58A6FF&text_color=8B949E&count_private=true&cache_seconds=86400)
&nbsp;&nbsp;
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=oveshshaikh786&layout=compact&theme=github_dark&hide_border=true&bg_color=0D1117&title_color=58A6FF&text_color=8B949E&cache_seconds=86400)

![Streak](https://github-readme-streak-stats.herokuapp.com/?user=oveshshaikh786&theme=github-dark-blue&hide_border=true&background=0D1117&stroke=30363D&ring=58A6FF&fire=FF6B35&currStreakLabel=58A6FF)

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=oveshshaikh786&theme=github-compact&hide_border=true&bg_color=0D1117&color=58A6FF&line=58A6FF&point=FF6B35)](https://github.com/oveshshaikh786)

</div>

---

## 📫 Let's Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/oveshshaikh786/)
&nbsp;
[![GitHub](https://img.shields.io/badge/GitHub-161B22?style=for-the-badge&logo=github&logoColor=white)](https://github.com/oveshshaikh786)

<br/>

**Actively looking for backend engineering roles — open to remote or hybrid.**<br/>
*If you're building something with Java / Spring Boot, I'd love to talk.*

</div>
