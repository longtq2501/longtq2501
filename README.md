# Hi, I'm Long 👋

**Full-Stack Developer** · Ho Chi Minh City, Vietnam 🇻🇳  
*Third-year IT student @ University of Transport Ho Chi Minh City*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/ton-quynh-long-dev)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:tonquynhlong05@gmail.com)

---

## About

I don't wait until I graduate to build real things.

Currently juggling two production-level projects simultaneously — one solo, one as Tech Lead of a 6-person team. Both solve problems I've encountered directly: managing tutoring work, and coordinating emergency rescue operations.

My focus is on systems that work at scale: real-time architecture, clean service boundaries, and performance that holds under actual load — not just in localhost.

- 🚀 **Tutor Pro** — Solo full-stack project, running in production
- 🌊 **Flood Rescue Coordination** — Tech Lead, 6-person team, active development
- 🎯 Open to **internship / fresher roles** in 2026
- 🎨 Hobby: 3D modeling with Blender

---

## Featured Projects

### [🎓 Tutor Pro](https://github.com/longtq2501/Tutor-Pro) · [Live Demo ↗](https://tutor-pro-app.vercel.app)

> A complete EdTech platform built to automate every operational burden of a working tutor — **deployed and running in production**.

Built this because I *am* the user. Every feature exists because I needed it.

| What it does | How |
|:-------------|:----|
| Generates 300+ sessions in < 800ms | Optimistic batch processing + JDBC batch inserts |
| Real-time notifications < 500ms | SSE + Spring Events + `ConcurrentHashMap` emitter pool |
| AI feedback in Vietnamese < 300ms | Groq inference API (Llama 3.3 70B) |
| VietQR invoicing with CRC-16 checksum | NAPAS-247 standard, embedded in PDF |
| WebRTC P2P live teaching room | Full-Mesh + STOMP WebSocket signaling |
| Drag-and-drop calendar at 60fps | @dnd-kit + React.memo + prefetching |

**Stack:** `Next.js 15` `React 19` `TypeScript` `Spring Boot 3.4` `Java 21` `MySQL 8` `Groq AI` `WebRTC` `SSE` `Docker` `Railway`

---

### [🌊 Flood Rescue Coordination System](https://github.com/longtq2501/Flood-Rescue-Coordination-and-Relief-Management-System) · `Active Development`

> A microservices platform for real flood emergency scenarios — from citizen rescue requests to team dispatching, live GPS tracking, and relief supply management.

**Role: Tech Lead** — responsible for architecture decisions, full infra setup, module skeleton (FE + BE), CI/CD pipeline, and sprint management via Jira.

```
CITIZEN  →  submit GPS-tagged rescue request
           ↓
COORDINATOR  →  verify → assign nearest available team via map
           ↓
RESCUE TEAM  →  GPS auto-reports every 10s → coordinator tracks live
           ↓
MANAGER  →  monitor KPIs, manage relief supply warehouse, get low-stock alerts
```

**Key decisions:**
- **Modular Monolith → Microservices** — validate business logic first, extract services after Sprint 1
- **RabbitMQ + Kafka** — task routing (exactly-once) vs. event streaming (replayable) are different problems
- **Database per Service** — strict bounded contexts from day one

**Stack:** `Spring Boot` `Java 17` `Next.js` `PostgreSQL` `RabbitMQ` `Apache Kafka` `Nginx` `Docker` `GitHub Actions` `VPS`

---

### 📦 [next-spring-skills](https://github.com/longtq2501/next-spring-skills) — #1 on npm

[![npm version](https://img.shields.io/npm/v/@longtq2501/next-spring-skills.svg?style=flat-square)](https://www.npmjs.com/package/@longtq2501/next-spring-skills)
[![npm downloads](https://img.shields.io/npm/dt/@longtq2501/next-spring-skills.svg?style=flat-square)](https://www.npmjs.com/package/@longtq2501/next-spring-skills)

> 🥇 Ranked **#1** on npm for `spring skills` among **1,000+ packages**

Modular best practices, AI agent workflow protocols, and production-ready templates for Next.js + Spring Boot projects.

```bash

npx @longtq2501/next-spring-skills

```

---

## Tech Stack

**Backend**
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

**Frontend**
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Infrastructure & Messaging**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)

---

*Year 3 student. Two production-level projects. Always building.*  
**📢 Open to fullstack internship & fresher opportunities — 2026**
