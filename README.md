<!-- ========================================================= -->
<!--                    HERO / LANDING SECTION                  -->
<!-- ========================================================= -->

<p align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=180&color=0:0F172A,40:4C1D95,70:6D28D9,100:7C3AED&text=Kartik%20Chouhan&fontSize=44&fontColor=FFFFFF&fontAlignY=38&desc=Backend%20Engineer%20%E2%80%A2%20AI%20Engineer%20%E2%80%A2%20Full%20Stack%20Developer&descAlignY=58&animation=fadeIn"/>
</p>

<p align="center">
<img src="https://readme-typing-svg.demolab.com?font=Inter&weight=600&size=21&duration=3500&pause=1200&color=8B5CF6&center=true&vCenter=true&width=850&lines=Building+Intelligent+Software+Systems;Computer+Vision+%E2%80%A2+NLP+%E2%80%A2+Backend+Architecture;Turning+AI+Ideas+Into+Production+Software"/>
</p>

<p align="center">
<sub><b>Python • Django • FastAPI • React • PostgreSQL • OpenCV • YOLOv8 • DeBERTa-v3</b></sub>
</p>

<br>

<p align="center">
<a href="https://kartikchouhan.vercel.app"><img src="https://img.shields.io/badge/Portfolio-6D28D9?style=for-the-badge&logo=vercel&logoColor=white"/></a>
<a href="https://github.com/KartikChouhan03"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github"/></a>
<a href="https://www.linkedin.com/in/kartik-chouhan-255369270/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin"/></a>
<a href="mailto:chouhankartik3300@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://leetcode.com/u/Kartik_C003/"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black"/></a>
</p>

<p align="center">
<img src="https://komarev.com/ghpvc/?username=KartikChouhan03&style=flat-square&color=7C3AED"/>
</p>

---

# Engineering Snapshot

> 🎓 **Education** — B.Tech Information Technology, Manipal University Jaipur · CGPA 8.62<br>
> 🚀 **Building now** — SmartParkX, an AI-powered smart parking platform (Computer Vision + IoT + Backend)<br>
> 🧠 **Specialization** — Computer Vision · NLP · REST API Design · Software Architecture<br>
> 🌱 **Learning** — System Design · Distributed Systems · Docker · Cloud Deployment<br>
> 🤝 **Open to** — Backend Engineering & SWE Internships · AI/ML Roles · Open Source

---

# About

I build software where backend systems and applied AI meet — parking infrastructure that sees, review pipelines that reason, platforms that just work. My focus is computer vision and NLP wired into REST APIs that hold up outside a notebook.

I think in systems: how a vision model's output becomes an API contract, how a database schema survives concurrent writes, how a side project becomes something deployable. Five projects in, the throughline is the same — take a real constraint and engineer a working answer to it, not a prototype.

Right now I'm deepening system design and distributed systems fundamentals, and moving every project a step closer to how it would actually run in production.

---

# Core Technology Ecosystem

| Domain | Technologies |
|---|---|
| **Languages** | Python · JavaScript · C++ |
| **Backend** | Django · FastAPI · Node.js · Express |
| **Frontend** | React · HTML5 · CSS3 · Vite |
| **Databases** | PostgreSQL · MongoDB · MySQL |
| **AI** | PyTorch · OpenCV · YOLOv8 · DeBERTa-v3 · OCR |
| **Tools** | Git · GitHub · Docker · Linux · Postman |

<p align="center">
<img src="https://skillicons.dev/icons?i=python,cpp,javascript,django,fastapi,nodejs,react,postgres,mongodb,mysql,docker,git,github,linux,postman"/>
</p>

---

# AI & Backend Expertise

| Domain | Level | Used In |
|---|---|---|
| 🧠 Computer Vision | Advanced | SmartParkX, Live ANPR |
| 💬 Natural Language Processing | Intermediate | DeceptiScan |
| ⚙️ Backend APIs | Advanced | SmartParkX, BorrowBox, Foodify |
| 🤖 Machine Learning | Intermediate | DeceptiScan, SmartParkX |

---

<!-- ========================================================= -->
<!--                  FEATURED ENGINEERING WORK                 -->
<!-- ========================================================= -->

# Featured Projects

Five projects, one progression — from full-stack fundamentals to AI-driven systems with hardware in the loop.

<br>

## 🚗 SmartParkX — AI-Powered Smart Parking Infrastructure

> An end-to-end platform that automates vehicle entry, slot allocation, billing, and exit — combining Computer Vision, IoT, and a modular backend with minimal human intervention.

**System Workflow**

```text
Vehicle Arrival
  → ANPR Camera (ESP32-CAM)
  → YOLOv8 Plate Detection + OCR
  → Django REST Backend
  → Parking Engine / Slot Manager / Billing Engine
  → PostgreSQL
  → React Dashboard
```

**Engineering Highlights**

| Area | Implementation |
|---|---|
| Computer Vision | ANPR via YOLOv8 + OpenCV |
| Backend | Django REST Framework — sessions, vehicles, payments |
| IoT | ESP32-CAM + slot sensors for real-time monitoring |
| Billing | Automated duration-based billing engine |
| Dashboard | React interface for live slot availability |
| Security | JWT auth + role-based access control |

Each subsystem — vision, sensors, backend, billing, frontend — runs independently and communicates over REST, so the platform scales and fails gracefully one piece at a time.

<p align="center">
<img src="https://skillicons.dev/icons?i=python,django,react,postgres"/><br>
<img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv"/>
<img src="https://img.shields.io/badge/YOLOv8-6D28D9?style=for-the-badge"/>
<img src="https://img.shields.io/badge/ESP32-3C873A?style=for-the-badge"/>
</p>

<p align="center">
<a href="https://github.com/KartikChouhan03/SmartParkX"><img src="https://img.shields.io/badge/View_Project-181717?style=for-the-badge&logo=github"/></a>
</p>

---

## 🛡️ DeceptiScan — AI-Powered Fake Review Detection

> A browser extension that pairs a fine-tuned transformer with a FastAPI inference service to flag fake and AI-generated product reviews — with an explainable trust score, not just a sentiment label.

**Inference Pipeline**

```text
Amazon Product Page
  → Browser Extension (React)
  → Review Scraper
  → Preprocessing
  → Fine-Tuned DeBERTa-v3
  → Trust Score
  → Analytics Dashboard
```

**Model Performance**

| Metric | Result |
|---|---|
| Dataset | 72,877 labeled reviews |
| Model | Fine-tuned DeBERTa-v3 |
| Accuracy | 96.8% |
| Latency | ~12 ms / batch |
| Deployment | FastAPI inference server |

<p align="center">
<img src="https://skillicons.dev/icons?i=python,react,fastapi,pytorch"/><br>
<img src="https://img.shields.io/badge/DeBERTa--v3-6D28D9?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Transformers-FFD21F?style=for-the-badge&logo=huggingface&logoColor=black"/>
</p>

<p align="center">
<a href="https://github.com/KartikChouhan03/DeceptiScan"><img src="https://img.shields.io/badge/View_Project-181717?style=for-the-badge&logo=github"/></a>
</p>

---

## Supporting Projects

<details>
<summary><b>📷 Live ANPR</b> — Real-time license plate recognition</summary>
<br>

Real-time number plate detection and logging from live camera streams using YOLOv8, OpenCV, and Tesseract OCR.

**Stack:** Python · YOLOv8 · OpenCV · Tesseract OCR
**Repo:** [github.com/KartikChouhan03](https://github.com/KartikChouhan03)
</details>

<details>
<summary><b>📦 BorrowBox</b> — Peer-to-peer campus rental platform</summary>
<br>

A modular rental platform with secure authentication, listings, and transaction management, built on Django REST Framework.

**Stack:** Django REST Framework · PostgreSQL
**Repo:** [github.com/KartikChouhan03](https://github.com/KartikChouhan03)
</details>

<details>
<summary><b>🍔 Foodify</b> — Full-stack food delivery platform</summary>
<br>

A MERN food delivery platform with JWT authentication, order management, payments, and an admin dashboard.

**Stack:** React · Node.js · Express · MongoDB
**Repo:** [github.com/KartikChouhan03](https://github.com/KartikChouhan03)
</details>

<br>

**Project progression:**
`Foodify` → `BorrowBox` → `Live ANPR` → `DeceptiScan` → `SmartParkX`

Full stack → backend architecture → computer vision → applied NLP → AI + IoT + backend, integrated.

---

<!-- ========================================================= -->
<!--            LEADERSHIP • ACHIEVEMENTS • LEARNING            -->
<!-- ========================================================= -->

# Leadership

**Senior Coordinator — LearnIT Technical Club**, Manipal University Jaipur · *Sep 2023 – May 2025*

Led technical workshops and hackathons for 200+ students, coordinating volunteers and faculty to run six major events end-to-end — from planning through execution.

---

# Engineering Highlights

- **5+ end-to-end software projects**, spanning backend systems, computer vision, and applied NLP
- **AI systems shipped to working demos** — not just notebooks: SmartParkX (CV + IoT) and DeceptiScan (NLP)
- **REST API design** across Django and FastAPI, with auth, role-based access, and structured data models
- **Technical leadership** — ran 6+ workshops/hackathons for 200+ students as Senior Coordinator

---

# Certifications

**Meta** — Backend Developer Professional Certificate · Introduction to Back-End Development · Programming in Python · Django Web Framework

**IBM** — Data Analysis with Python · Python for Data Science

**Oracle** — Database Programming with SQL

---

# Coding Profiles

<p align="center">
<a href="https://leetcode.com/u/Kartik_C003/"><img src="https://img.shields.io/badge/LeetCode-Kartik__C003-FFA116?style=for-the-badge&logo=leetcode&logoColor=black"/></a>
<a href="https://www.hackerrank.com/"><img src="https://img.shields.io/badge/HackerRank-Profile-2EC866?style=for-the-badge&logo=hackerrank&logoColor=white"/></a>
</p>

---

<!-- ========================================================= -->
<!--                   GITHUB INSIGHTS & CONNECT                -->
<!-- ========================================================= -->

# GitHub Insights

<p align="center">

<img height="165em" src="https://streak-stats.demolab.com/?user=KartikChouhan03&theme=midnight-purple&hide_border=true&cache_seconds=86400"/>
</p>

<p align="center">

</p>

<p align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=KartikChouhan03&bg_color=0F172A&color=C4B5FD&line=7C3AED&point=A78BFA&area_color=6D28D9&hide_border=true&area=true"/>
</p>

<p align="center">
<img src="https://raw.githubusercontent.com/KartikChouhan03/KartikChouhan03/output/github-contribution-grid-snake-dark.svg"/>
</p>

> Snake animation requires a GitHub Actions workflow — to be wired up once this README is finalized.

---

# Let's Connect

<p align="center">
<a href="mailto:chouhankartik3300@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/kartik-chouhan-255369270/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://github.com/KartikChouhan03"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
<a href="https://kartikchouhan.vercel.app"><img src="https://img.shields.io/badge/Portfolio-6D28D9?style=for-the-badge&logo=vercel&logoColor=white"/></a>
</p>

<p align="center">
Thanks for visiting. Let's build something meaningful together.
</p>

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&height=100&section=footer&color=0:0F172A,40:4C1D95,70:6D28D9,100:7C3AED"/>
</p>
