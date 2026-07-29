<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:FF0080,50:7928CA,100:2AFADF&height=220&section=header&text=Ammu%20S&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Software%20Engineer%20%E2%80%A2%20AI%2FML%20Engineer&descAlignY=58&descSize=18" width="100%"/>

<br/>

<a href="#">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=22&duration=2600&pause=900&color=8A7CFF&center=true&vCenter=true&width=650&lines=I+build+production-grade+backend+%26+AI+systems;Not+tutorials.+Not+CRUD+demos.+Real+products.;API-first.+Cloud-ready.+Built+to+scale." alt="Typing SVG" />
</a>

<br/><br/>

<a href="https://linkedin.com/in/ammusabu/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="mailto:ammuttya20@gmail.com"><img src="https://img.shields.io/badge/Email-24243E?style=for-the-badge&logo=gmail&logoColor=white" /></a>


<table>
<tr>
<td align="center" width="25%">

**🚀 6+**
Production Projects

</td>
<td align="center" width="25%">

**🤖 3**
AI Applications Shipped

</td>
<td align="center" width="25%">

**🌍 5+**
Live Deployments

</td>
<td align="center" width="25%">

**💻 300+**
DSA Problems Solved

</td>
</tr>
</table>

</div>

<br/>

## About Me

I build software with a long-term engineering mindset—prioritizing modular architecture, maintainability, and reliability from the start. I enjoy turning complex ideas into production-ready applications by combining backend engineering with applied AI.

My interests lie in designing scalable APIs, integrating LLM-powered features, and building intelligent systems that remain clean, extensible, and easy to evolve. Rather than focusing only on model performance, I enjoy engineering the infrastructure that makes AI applications practical and dependable.

Currently exploring backend architecture, distributed systems, MLOps, and cloud-native development while building full-stack AI products.

<br/>

## How I Design Systems

<table>
<tr>
<td width="50%" valign="top">

**API-first thinking**
Contracts before implementation. Every service is designed to be consumed before it's designed to be built.

**Modular by default**
Boundaries drawn around business capability, not file convenience. Swappable pieces, not spaghetti.

</td>
<td width="50%" valign="top">

**Scalable from the start**
Stateless services, async workloads, caching layers — designed in, not bolted on after the first outage.

**Cloud-ready, not cloud-hopeful**
Containerized, environment-agnostic, and deployable without "it works on my machine."

</td>
</tr>
</table>

<br/>

## Featured Engineering Work

<br/>

### 01 · InsightForge AI
**AI-powered Business Intelligence Platform**

<img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/eb33d097-0a7f-4ce0-bf66-a26823e3cb02" />

Turns raw business data into forecasts, narrative reports, and a conversational interface — so stakeholders query their data in plain English instead of waiting on a dashboard request.

**Architecture Highlights**
- FastAPI backend serving async inference endpoints, containerized for horizontal scaling
- Pandas/Scikit-learn pipeline decoupled from the API layer for independent retraining
- Groq-backed LLM layer for natural-language dataset querying and auto-generated reports

| Layer | Stack |
|---|---|
| Frontend | React, TypeScript |
| Backend | FastAPI, Python |
| ML/Data | Pandas, Scikit-learn |
| AI | Groq |
| Infra | Docker |

**Key Features** · AI-generated reports · Forecasting engine · Natural-language dataset chat · Interactive dashboards · Containerized deployment

<p>
<a href="https://nsight-forge-ai.vercel.app/"><img src="https://img.shields.io/badge/Live_Demo-8A7CFF?style=for-the-badge&logo=vercel&logoColor=white"/></a>
<a href="https://github.com/Ammusabu/InsightForge-AI"><img src="https://img.shields.io/badge/GitHub-151328?style=for-the-badge&logo=github&logoColor=white"/></a>
</p>

<br/>

---

<br/>

### 02 · ZenoLearn
**Modern Learning Management System**

<img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/cbc1b1e5-88e8-476b-958d-7058e1e2f28f" />

A full LMS built around three distinct user roles — students, instructors, and admins — each with a purpose-built interface instead of one dashboard trying to serve everyone.

**Architecture Highlights**
- Django REST Framework API with JWT-based auth and role-based access control
- Normalized PostgreSQL schema supporting progress tracking and certificate issuance
- Clean separation between student, instructor, and admin experiences on a shared React frontend

| Layer | Stack |
|---|---|
| Frontend | React, Tailwind CSS |
| Backend | Django, DRF |
| Auth | JWT |
| Database | PostgreSQL |

**Key Features** · Student dashboard · Instructor portal · Admin panel · Progress tracking · Auto-generated certificates · Role-based authentication

<p>
<a href="https://zenolearn-two.vercel.app"><img src="https://img.shields.io/badge/Live_Demo-8A7CFF?style=for-the-badge&logo=vercel&logoColor=white"/></a>
<a href="https://github.com/Ammusabu/zenolearn"><img src="https://img.shields.io/badge/GitHub-151328?style=for-the-badge&logo=github&logoColor=white"/></a>
</p>

<br/>

---

<br/>

### 03 · AI Interview Assistant
**LLM-powered Technical Interview Simulator**

<img width="1600" height="903" alt="image" src="https://github.com/user-attachments/assets/ca9774db-f431-4ceb-ac63-7816749f4f25" />

Runs adaptive mock interviews that generate follow-up questions based on prior answers and score responses using an LLM evaluation layer — built to handle concurrent sessions without blocking.

**Architecture Highlights**
- Celery + Redis for async question generation and evaluation, keeping the API responsive under load
- Redis caching layer for session state, cutting redundant LLM calls
- JWT-secured PostgreSQL-backed session and results storage

| Layer | Stack |
|---|---|
| Backend | FastAPI |
| Async | Celery, Redis |
| AI | Groq |
| Auth | JWT |
| Database | PostgreSQL |

**Key Features** · Adaptive AI interviewer · Dynamic question generation · LLM-based answer evaluation · Redis caching · Async worker pipeline

<p>
<a href="https://ai-interview-agent-fg1m.onrender.com/"><img src="https://img.shields.io/badge/Live_Demo-8A7CFF?style=for-the-badge&logo=vercel&logoColor=white"/></a>
<a href="https://github.com/Ammusabu/Ai-interview-agent"><img src="https://img.shields.io/badge/GitHub-151328?style=for-the-badge&logo=github&logoColor=white"/></a>
</p>

<br/>

<h2>🚀 Other Engineering Projects</h2>

<table>
<tr>

<td width="50%" valign="top">

### 📝 <a href="https://github.com/Ammusabu/Neuralexam--Bias-Free-AI-MCQ-Generator">NeuralExam</a>

AI-powered MCQ generator with balanced answer distribution.

**Stack:** FastAPI • Groq • Llama 3.1

</td>

<td width="50%" valign="top">

### 👁️ <a href="https://github.com/Ammusabu/Real-Time-Eye-Gaze-Tracking-Attention-Analysis">Eye Gaze Tracking</a>

Real-time attention monitoring using MediaPipe and OpenCV.

**Stack:** Python • OpenCV • Streamlit

</td>

</tr>

<tr>

<td width="50%" valign="top">

### 🏥 <a href="https://github.com/Ammusabu/skin-condition-prediction-tracker">Skin Disease Prediction</a>

AI-based skin condition classification with severity analysis.

**Stack:** TensorFlow • MobileNetV2 • Plotly

</td>

<td width="50%" valign="top">

### 📊 <a href="https://github.com/Ammusabu/Advanced-student-Management-System-Result-Analzser-">Student Result Analyzer</a>

Analytics dashboard with CSV import/export and performance insights.

**Stack:** JavaScript • Chart.js

</td>

</tr>
</table>

<br/>

## Engineering Skills

<table>
<tr><td><b>Languages</b></td><td>Python · TypeScript · JavaScript · SQL · C++ </td></tr>
<tr><td><b>Frontend</b></td><td>React · Tailwind CSS</td></tr>
<tr><td><b>Backend</b></td><td>FastAPI · Django · Django REST Framework</td></tr>
<tr><td><b>AI / ML</b></td><td>Scikit-learn · Pandas · Groq · LLM Integration</td></tr>
<tr><td><b>Database</b></td><td>PostgreSQL · Redis</td></tr>
<tr><td><b>Cloud</b></td><td>Docker</td></tr>
<tr><td><b>DevOps / Tools</b></td><td>Celery · JWT · Git · CI/CD</td></tr>
</table>

<br/>

## Architecture Interests

Microservices · Distributed Systems · System Design · Event-Driven Architecture · Data Engineering · MLOps

<br/>

## Currently Learning

Distributed systems patterns at scale · MLOps pipelines for model deployment and monitoring

<br/>

## Open Source Goals

Contributing to backend and AI-tooling projects where I can improve reliability, documentation, or developer experience — looking to move from user to contributor in the tools I already rely on.

<br/>


## Coding Profiles

<div align="center">

<a href="https://leetcode.com/u/Ammu0S/"><img src="https://img.shields.io/badge/LeetCode-151328?style=for-the-badge&logo=leetcode&logoColor=8A7CFF"/></a>
<a href="https://www.codechef.com/users/ammusabu"><img src="https://img.shields.io/badge/CodeChef-151328?style=for-the-badge&logo=codechef&logoColor=8A7CFF"/></a>
<a href="https://www.hackerrank.com/ammusabu"><img src="https://img.shields.io/badge/HackerRank-151328?style=for-the-badge&logo=hackerrank&logoColor=8A7CFF"/></a>

</div>

<br/>

## Connect

<div align="center">

<a href="https://www.linkedin.com/in/ammusabu/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:ammuttya20@gmail.com"><img src="https://img.shields.io/badge/Email-24243E?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://github.com/Ammusabu"><img src="https://img.shields.io/badge/GitHub-151328?style=for-the-badge&logo=github&logoColor=white"/></a>

</div>

<br/>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243E,50:302B63,100:0F0C29&height=100&section=footer" width="100%"/>

<sub>Built with intent, not templates.</sub>
</div>
