# 🎓 Kampusyolunda | Behavioral Decision Support Platform

**Status:** 🚀 In Active Development (Beta)
**Architect:** [Dr. Bektaş Sarı](https://github.com/bektas-sari)

---

## ⚡ The Problem: Cognitive Overload
University candidates face thousands of options and millions of data points. Traditional listing sites increase **decision fatigue** rather than solving it.

## 🧠 The Solution
**Kampusyolunda** is not just a listing site; it is a **Decision Support System (DSS)** built on behavioral economics principles. It reduces friction by filtering noise and presenting data based on user intent signals.

---

## 🛠️ Technical Architecture

This project follows a **Microservices-ready** architecture ensuring scalability and high availability.

### Core Stack
| Layer | Technology | Reason |
| :--- | :--- | :--- |
| **Frontend** | **Next.js 14 (App Router)** | Server-Side Rendering (SSR) for SEO and performance. |
| **Styling** | **Tailwind CSS** | Utility-first design system for rapid UI iteration. |
| **Backend / DB** | **Supabase** | Real-time database and Auth utilizing PostgreSQL. |
| **AI Layer** | **Python (FastAPI)** | Microservice for processing recommendation algorithms. |

### 📂 Project Structure (Overview)
```bash
kampusyolunda-platform/
├── app/                  # Next.js App Router
├── components/           # Reusable UI Blocks (Atoms/Molecules)
├── lib/                  # Supabase Clients & Utils
├── public/               # Static Assets
└── services/             # API Integrations (AI & Data)
```

### 🚀 Key Features
* Dynamic Filtering: Real-time search with <100ms latency.
* Behavioral Tracking: Analyzing user clicks to refine recommendations (GDPR compliant).
* Visual Data: Interactive charts helping students compare universities instantly.

### 🔒 License
Proprietary Software. All rights reserved by Kognitect.
