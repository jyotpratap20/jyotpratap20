# Jyot Pratap Singh

Backend-focused engineer working on distributed systems, event-driven architectures, and real-time applications.
Experience includes building microservices, handling asynchronous workflows, and designing systems where reliability and availability are primary constraints.

<p>
  <a href="https://linkedin.com"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:jpa03182000@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=flat-square&logo=gmail&logoColor=white"/></a>
  <a href="https://leetcode.com"><img src="https://img.shields.io/badge/LeetCode-Knight_🏅_1878-FFA116?style=flat-square&logo=leetcode&logoColor=white"/></a>
  <a href="https://codechef.com"><img src="https://img.shields.io/badge/CodeChef-4★_1808-5B4638?style=flat-square&logo=codechef&logoColor=white"/></a>
  <a href="https://codeforces.com"><img src="https://img.shields.io/badge/Codeforces-Pupil_1360-1F8ACB?style=flat-square&logo=codeforces&logoColor=white"/></a>
</p>

---

## About

I work on backend systems where correctness under load, failure handling, and system behavior matter more than surface-level features.

🔭 &nbsp;Currently building event-driven workflow systems with AI-based processing at PALTECH Consulting  
🌱 &nbsp;Deepening knowledge in concurrency, backend internals, and RAG-style pipelines  
🤔 &nbsp;Thinking about: what breaks under scale · where latency accumulates · how systems recover  
💬 &nbsp;Ask me about Kafka, Spring Boot, Microservices, WebRTC, or System Design  
⚡ &nbsp;Fun fact: I approach chess and distributed systems the same way — think 5 moves ahead, plan for failure  

---

## Tech Stack

**Languages**

<p>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white"/>
</p>

**Backend & Architecture**

<p>
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white"/>
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white"/>
  <img src="https://img.shields.io/badge/REST_APIs-FF6C37?style=flat-square&logo=postman&logoColor=white"/>
  <img src="https://img.shields.io/badge/Microservices-1572B6?style=flat-square&logo=blueprint&logoColor=white"/>
</p>

**Frontend**

<p>
  <img src="https://img.shields.io/badge/React.js-61DAFB?style=flat-square&logo=react&logoColor=black"/>
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white"/>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white"/>
</p>

**Distributed Systems & Real-Time**

<p>
  <img src="https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white"/>
  <img src="https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socketdotio&logoColor=white"/>
  <img src="https://img.shields.io/badge/WebRTC-333333?style=flat-square&logo=webrtc&logoColor=white"/>
  <img src="https://img.shields.io/badge/Apache_Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white"/>
  <img src="https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white"/>
</p>

**Cloud & Infrastructure**

<p>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white"/>
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white"/>
  <img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white"/>
</p>

**Data & Storage**

<p>
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white"/>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
  <img src="https://img.shields.io/badge/DynamoDB-4053D6?style=flat-square&logo=amazondynamodb&logoColor=white"/>
  <img src="https://img.shields.io/badge/Amazon_Aurora-232F3E?style=flat-square&logo=amazonaws&logoColor=white"/>
</p>

---

## Selected Work

### ⚙️ Microservices-Based E-Commerce Backend
> `Spring Boot` `Kafka` `Docker` `Kubernetes` `Prometheus` `Grafana` `Loki` `Zipkin`

Built a backend system from scratch with a focus on service decomposition and reliability.

- Designed service boundaries for user, product, and order domains with clear ownership
- Implemented inter-service communication via API Gateway, OpenFeign, Eureka, and RestTemplate
- Introduced Kafka for asynchronous order workflows to decouple services and reduce cascading failures
- Handled failure scenarios through retries, fallback mechanisms, and decoupled processing
- Set up full observability — Prometheus, Grafana, Loki, Zipkin — for metrics, logs, and tracing
- Achieved **~99% observed availability** under active usage

**Key focus:** Service communication · failure handling · availability trade-offs · modular system design

[![Repo](https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com)

---

### 💬 MINGLE — Real-Time Communication System
> `Node.js` `Socket.IO` `WebRTC` `JWT` `Docker` `Kubernetes`

A real-time chat and calling system designed to handle concurrent users with low latency.

- Built real-time messaging via Socket.IO and peer-to-peer calling via WebRTC
- Managed **~1,000 concurrent connections** with sub-150ms average message latency
- Implemented JWT-based authentication and role-aware session handling
- Containerized and deployed with Docker + Kubernetes — horizontal scaling, rolling updates
- Achieved **~99.5% observed uptime** during active usage

**Key focus:** Concurrency · real-time systems · latency handling · connection management

[![Repo](https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com)

---

## Current Work

- 🔧 &nbsp;Deepening backend internals — concurrency, threading, async execution models
- 🤖 &nbsp;Building an event-driven workflow system with AI-based processing (RAG-style pipelines)
- 📐 &nbsp;Strengthening system design thinking — scalability, fault tolerance, observability

---

## Competitive Programming

1,200+ problems solved — focused on algorithms, data structures, and problem decomposition under constraints.

| Platform | Rating | Rank |
|---|---|---|
| ![LeetCode](https://img.shields.io/badge/-LeetCode-FFA116?style=flat-square&logo=leetcode&logoColor=white) | 1878 | Knight 🏅 |
| ![CodeChef](https://img.shields.io/badge/-CodeChef-5B4638?style=flat-square&logo=codechef&logoColor=white) | 1808 | 4 Star ★★★★ |
| ![Codeforces](https://img.shields.io/badge/-Codeforces-1F8ACB?style=flat-square&logo=codeforces&logoColor=white) | 1360 | Pupil |

---

## Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jyot-pratap-singh-489306216 )
[![Gmail](https://img.shields.io/badge/Gmail-jpa03182000@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:jpa03182000@gmail.com)


