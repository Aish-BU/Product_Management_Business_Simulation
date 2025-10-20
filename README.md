# 🧭 AD 715 Business Simulation (Web Migration & AI-Assisted Decision Tool)

> **Transforming a legacy Excel simulation into an interactive, cloud-based, AI-enhanced decision-making platform for Boston University MET students.**

---

## 🎯 Vision
To migrate the traditional Excel-based *AD 715 Business Simulation* into a modern, cloud-hosted web platform that promotes **data-driven learning**, **team collaboration**, and **AI-assisted decision support** — helping students experience the challenges of running a business through real-world scenarios.

---

## 💡 Problem Statement
The legacy Excel simulation posed significant constraints:
- ❌ Limited collaboration across student teams  
- ❌ Manual version control and data corruption risks  
- ❌ Performance lag with large datasets  
- ❌ Lack of integration with Power BI or learning systems  
- ❌ Minimal onboarding or self-learning support  

Faculty and students needed a **scalable, interactive, and AI-ready** solution to modernize simulation-based learning:contentReference[oaicite:0]{index=0}:contentReference[oaicite:1]{index=1}.

---

## 🚀 Solution Overview
The new **web-based B-Sim** was built using the **Django framework** and deployed on **Azure Virtual Machines**, introducing:
- 🌐 Full web accessibility (HTML / CSS / Bootstrap / JavaScript)
- 💾 PostgreSQL backend with JSON → Excel / PDF exports  
- 🤖 Bing Copilot prompt dialogs for AI-assisted analytics  
- 📊 Power BI integration for dashboards and performance metrics  
- 🎮 Gamified tutorials for self-paced onboarding:contentReference[oaicite:2]{index=2}:contentReference[oaicite:3]{index=3}

---

## 🧩 Architecture & Tech Stack

| Layer | Function | Technology |
|:------|:----------|:-----------|
| **Interface** | Input forms for Marketing, Finance, Operations, Innovation, HR | Django Views · Bootstrap |
| **Data Access** | Simulation logic + DB operations | Python Packages · PostgreSQL |
| **Output Delivery** | Reports, Financial Planner, D-Analysis | JSON · Excel · PDF |
| **Infrastructure** | Scalable deployment + Monitoring | Azure VM · Python Env |
| **Visualization** | BI dashboards + Performance metrics | Power BI · Solver |
| **AI Assist** | Generative prompt dialogs | Microsoft Copilot:contentReference[oaicite:4]{index=4} |

---

## 👥 Stakeholders & Personas

| Persona | Pain Point | Product Value |
|----------|-------------|---------------|
| 🎓 **Student** | Complex Excel workflows | Web UI + auto-generated outputs |
| 🧑‍🏫 **Instructor** | Hard to track team progress | JSON-based traceability |
| 🧑‍💻 **Teaching Assistant** | Time-consuming onboarding | Gamified help + FAQs |
| 🏢 **Admin / IT** | VM maintenance & security | Scalable Azure VM setup |

---

## 📊 Product Requirements & KPIs

| Objective | KPI | Target |
|------------|-----|--------|
| Accessibility | Uptime | > 99 % |
| Adoption | Simulation completion rate | ↑ 20 % |
| Performance | Load-time reduction | ↓ 50 % |
| Satisfaction | Student survey rating | ≥ 4 / 5 |
| Scalability | Concurrent users supported | 100 + |

---

## 🧭 Agile Roadmap

| Sprint | Deliverable | PM Focus |
|:-------|:-------------|:---------|
| **1** | MVP Migration from Excel | Feasibility + Stakeholder Buy-in |
| **2** | Core Simulation Flows | MoSCoW Prioritization |
| **3** | Help Center & AI Prompts | UX Enhancement |
| **4** | Testing + Launch | Feedback Loop & Adoption |

---

## ⚠️ Risk & Mitigation

| Risk | Mitigation Strategy |
|------|----------------------|
| Lack of dedicated personnel | Defined roles for Business / Dev / Testing teams:contentReference[oaicite:5]{index=5}:contentReference[oaicite:6]{index=6} |
| Azure dependency issues | Version-based VM deployments + rollback plan |
| Limited AI expertise | Faculty mentorship + documentation sessions |
| IP protection | Protocols at App / College / University / Platform levels |

---

## 🤖 Copilot Prompt Integration Framework
A **Copilot-Based Prompt Dialog System** was designed for each functional area:

| Module | Prompt Category | Use Case |
|---------|-----------------|----------|
| Marketing | Market share & Pricing | “Suggest optimal pricing to maximize ROI in Cycle 3.” |
| Finance | Cash flow forecast | “Generate 3-year projection based on Cycle 2 inputs.” |
| Operations | Capacity & Inventory | “Estimate required production capacity for next quarter.” |
| Performance | Scenario analysis | “Summarize team performance vs benchmarks.” |

> **Limitation:** Works with Bing Copilot Free version only (no offline mode).  
> **Next Step:** Integrate OpenAI API for custom prompt models and feedback tracking:contentReference[oaicite:7]{index=7}.

---

## 🎨 UX Design Highlights
Based on `Templates Sim Nav.pdf` and UI mockups:contentReference[oaicite:8]{index=8}:

- **Sim Navigation:** Decision-cycle flow diagram  
- **Functional Parameters:** Data entry for marketing, finance, ops, HR  
- **Output Analysis:** Dynamic reports + visual analytics  
- **Login Dashboard:** Role-based access for students and faculty  

Responsive design ensures cross-browser compatibility:contentReference[oaicite:9]{index=9}.

---

## 🔄 Feedback & Iteration
- Conducted beta tests in March 2024 with ~ 200 students  
- Logged user feedback via Kanban board and prioritized UX fixes  
- Released v1.1 with 30 % faster load times and reduced support queries  
- Phase 2 adds real-time Power BI dashboards and leaderboards  

---

## 💥 Business Impact
- ⏱️ **Onboarding time ↓ 40 %**
- 📈 **Simulation performance ↑**
- 🤝 **Collaboration across 200 + students and faculty**
- 🧩 **Foundation for AI-driven learning modules at BU MET**

---

## 🧠 PM Takeaways
1. Translate academic needs into scalable digital products.  
2. Leverage cross-functional coordination to deliver impact.  
3. Apply Agile roadmaps + KPI-driven tracking.  
4. Integrate AI to amplify learning without complexity.  

---

## 🖼️ Screenshots & Demos
> *(Add screenshots from Templates Sim Nav or live deployment here)*  
> Example:  
> ![Login Page](docs/login_screenshot.png)  
> ![Simulation Dashboard](docs/dashboard_preview.png)

---

## 🏁 Next Steps
- 🧠 Integrate LLM-based analytics assistant (OpenAI API)  
- 📊 Embed Power BI dashboards into the app  
- 📰 Publish as BU MET Learning Innovation case study  

---

### 👩‍💻 Project Team
**Lead:** Aishwarya Malhotra  
**Collaborators:** B-Sim Dev Team · Prof. Zlatev · BU MET IT Support  

**Tech Stack:** Python (Django) · PostgreSQL · Bootstrap · Azure VM · Power BI · Copilot Prompts  
**Tags:** Product Management · EdTech · AI Integration · UX Design · Cloud Deployment

---
