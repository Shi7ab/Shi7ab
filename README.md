<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1e3a8a,100:2563eb&height=220&section=header&text=SHIHAB%20BAKRI&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Software%20Engineer%20%7C%20Backend%20 Architect%20%7C%20DevOps%20%7C%20AI&descAlignY=60&descSize=19" width="100%" />

### 🚀 Software Engineer focused on building scalable, secure, and production-ready distributed systems.

<p>
  <a href="https://github.com/Shi7ab">
    <img src="https://img.shields.io/badge/GitHub-Shi7ab-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <a href="https://linkedin.com/in/shihab-bakri-ba568a262">
    <img src="https://img.shields.io/badge/LinkedIn-Shihab%20Bakri-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
</p>

</div>

---

## 👨‍💻 About Me

I am a **Software Engineer** specialized in designing high-throughput backend services, distributed systems, and resilient microservices. With deep expertise across **Laravel, Node.js, NestJS, and DevOps**, I engineer software solutions built for performance and high availability.

I also integrate **Machine Learning & Generative AI** (LLMs, Computer Vision, NLP) into backend infrastructure to deliver intelligent, production-grade applications.

---

## 🛠️ Complete Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=php,laravel,nodejs,nestjs,js,ts,python,go,cpp,mysql,postgres,mongodb,redis,docker,kubernetes,aws,gcp,git,githubactions,nginx,linux" />
</p>

| Category | Technologies & Tools |
| :--- | :--- |
| **Languages** | `PHP` `JavaScript` `TypeScript` `Python` `Go` `C++` `SQL` |
| **Backend & Frameworks** | `Laravel` `Node.js` `NestJS` `Express.js` `REST APIs` `GraphQL` |
| **Databases & ORMs** | `MySQL` `PostgreSQL` `MongoDB` `Redis` `Eloquent` `Prisma` `TypeORM` |
| **DevOps & Cloud** | `Docker` `Kubernetes` `GitHub Actions` `AWS` `Oracle Cloud (OCI)` `Nginx` |
| **Messaging & Queues** | `RabbitMQ` `Redis Pub/Sub` `BullMQ` `Laravel Queues` |
| **AI & Machine Learning** | `TensorFlow` `Keras` `Scikit-learn` `LLMs` `NLP` `Computer Vision` |
| **Architecture & Security** | `Clean Architecture` `DDD` `Microservices` `OAuth2` `JWT` `RBAC` |

---

## 💼 Professional Experience

### 🏢 Mid-Level Laravel Developer
**7P Software & Marketing Company** · *May 2026 – Present*

* Architect enterprise Laravel applications and Learning Management Systems (LMS) with scalable, maintainable domain boundaries.
* Eliminate system bottlenecks by optimizing **MySQL indexing**, refactoring N+1 queries, and implementing **Redis caching**.
* Utilize asynchronous event-driven queues (**Laravel Jobs & Workers**) for heavy background task execution.
* Enforce **SOLID principles** and Clean Architecture while maintaining secure REST APIs with strict RBAC mechanisms.

### 🏢 Backend Software Engineer
**MNM Global Business Solutions** · *Remote (2023 – 2025)*

* Built and managed distributed **NestJS** and **Laravel** microservices with asynchronous **RabbitMQ** messaging.
* Automated build and deployment operations using **Docker**, **Kubernetes**, and **GitHub Actions CI/CD pipelines**.
* Engineered secure, token-based authentication services (JWT, OAuth2) and scalable relational/NoSQL schemas.

---

## 🏗️ Highlighted Systems Architecture

<details>
<summary><b>🎓 Enterprise & Micro-Kernel LMS Architecture</b></summary>
<br />

Designed a **plugin-driven modular monorail** for enterprise learning applications allowing context isolation without modifying core system logic:

```text
                    LMS CORE SYSTEM
                          │
         ┌────────────────┼────────────────┐
         ▼                ▼                ▼
    [ Plugin A ]     [ Plugin B ]     [ Plugin C ]
    (Examinations)    (Analytics)     (Messaging)
         │                │                │
         └────────────────┼────────────────┘
                          ▼
            Service Container & Event Bus
