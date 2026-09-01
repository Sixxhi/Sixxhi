# Hi 👋, I'm Siddhi Prajapati

**Computer Science Junior · University of California, Irvine · Class of 2028**

> Building AI systems that are reliable, observable, and trustworthy — from agentic AI safety platforms and NLP pipelines to full-stack products and cloud infrastructure.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue)](https://www.linkedin.com/in/siddhi-prajapati-127483268/)
[![Portfolio](https://img.shields.io/badge/Portfolio-sixxhi.github.io-navy)](https://sixxhi.github.io)
[![GitHub](https://img.shields.io/badge/GitHub-Sixxhi-black)](https://github.com/Sixxhi)
[![Email](https://img.shields.io/badge/Email-siddhi2277%40gmail.com-red)](mailto:siddhi2277@gmail.com)

---

## 👩‍💻 About Me

I am a CS Junior at UC Irvine specializing in Intelligent Systems with a Minor in Statistics (GPA 3.64, Dean's Honor List: Sep 2024, Jan 2025, Jan 2026, Apr 2026). I care about building things that work correctly under real conditions — not just things that look impressive in a demo.

My work spans AI safety and agentic systems, backend engineering, NLP pipelines, cloud infrastructure, and full-stack development. I have won the AWS Cloud Hacks 2026 AI Safety Track, participated in UC Berkeley AI Hackathon 2026, conducted research at UCI Calit2 SMART ITAC, and worked as a data science research intern building production-quality ML pipelines.

**What I am working on right now:**
- 🔬 Building an AI project at **hyrAI** reducing false positive violation flags in AI proctoring systems
- 📚 Pursuing the **Machine Learning Specialization** (Andrew Ng, Coursera)
- 🏛️ Applied to the **Anthropic Fellows Program** (AI Safety & Alignment workstream)

---

## 💼 Experience

### Undergraduate Research Assistant — VR & AI Systems
**UCI Calit2 SMART ITAC, University of California Irvine** · Apr 2026 – Jun 2026 · Irvine, CA

The SMART ITAC program at UCI Calit2 provides free energy efficiency assessments to small and medium enterprises, led by Professor GP Li and funded by the U.S. Department of Energy.

- Developed **VR training simulations** in SimInsights HyperSkill for building energy assessments and data center cooling efficiency; designed end-to-end scenario flows covering mechanical equipment, sensor systems, and operational procedures
- Developed reasoning workflows for an **AI training agent** leveraging the ITAC database, ASHRAE guidelines, California building codes, and ISO standards to deliver contextualized simulation feedback
- Built and maintained modular **backend pipelines** supporting AI agent evaluation, observability, and real-time simulation-feedback workflows

---

### AI Project — False Alarms in AI Proctoring
**hyrAI / SkillJourney** · Aug 2026 – Present · Remote

- Analyzing real exam recordings to reduce **false positive violation flags** in AI proctoring systems without sacrificing detection of real cheating
- Building a **labeled dataset of 300+ flagged violations** with ground-truth annotations distinguishing genuine violations from false alarms
- Applying **precision-recall analysis** and threshold tuning using MediaPipe and Python to improve detection accuracy

---

### Data Science Research Intern — Fake News Detection
**3E Worldwide (in partnership with CHARUSAT)** · Jun 2026 – Jul 2025 · Remote – India

- Built an end-to-end **NLP classification pipeline** in Python using TF-IDF feature extraction, n-gram modeling, Logistic Regression, and Decision Tree classifiers with scikit-learn; best-performing model achieved **~91% accuracy on a 10,000+ article dataset**
- Evaluated model reliability using **F1, precision-recall, ROC-AUC**, and stratified 5-fold cross-validation; identified and flagged a data leakage risk in the original train/test split that had inflated accuracy metrics
- Documented methodology, experiments, model comparisons, and insights in a **research-style paper and report**

---

### Software Development Intern
**SUPROS · Mentored by Ex-Microsoft / PayPal Engineer** · Jun 2023 – Jul 2023 · Remote · 4 weeks

- Built and tested software modules for community-facing applications; applied **test-driven debugging**, iterative refactoring, and modular design under structured engineering mentorship
- Translated feature requirements into modular tasks, participated in review cycles, and shipped maintainable well-tested code

---

### Open-Source Development Intern
**BizzAppDev Systems Pvt. Ltd.** · Jul 2023 – Aug 2023 · 4 weeks

- Contributed to an open-source **Python/XML codebase** backed by PostgreSQL; strengthened backend data-handling workflows and collaborative development practices

---

### Technology & Data Analytics Intern
**cult.fit / Samsonite Projects** · Jul 2023 · 2 weeks

- Prototyped a mobile wellness app in Thunkable with onboarding, goal tracking, and accessibility-first UX
- Built **Google Data Studio dashboards** with dynamic segmentation to surface business trends

---

## 🚀 Projects

### 🏆 GlassBoxAI — Agentic AI Safety Observability Platform
**Winner, AI Safety Track — AWS Cloud Hacks 2026**

`AWS Lambda` `Amazon Bedrock` `Three.js` `Figma` `Python` `JavaScript` `GitHub Actions`

A real-time AI safety observability platform for a Smart Stadium Simulator that monitors agent reasoning traces, safety scores, tool-call sequences, and critical operational alerts — built end-to-end in 24 hours.

**What I built:**
- Complete **backend**: AWS Lambda functions, Amazon Bedrock agent reasoning pipelines, safety scoring logic, alert propagation
- Complete **frontend**: interactive Three.js globe/stadium visualization, dark-mode UI designed in Figma
- **GitHub Actions CI pipeline** running automated tests against Lambda endpoints on every push
- Caught a critical **Bedrock API parsing bug** by testing Lambda functions against the real endpoint before the demo — Copilot-generated code assumed flat JSON when Bedrock nests output inside a content array

**Results:** Detected 100% of injected high-risk scenarios with zero false negatives during live judging

---

### IMMUNE — AI Agent Memory Integrity System
**UC Berkeley AI Hackathon 2026 · Participant (Cal Hacks)**

`Python` `Redis RediSearch` `Anthropic Claude Haiku 4.5` `LangGraph` `FastMCP` `Arize Phoenix` `OpenTelemetry` `Sentry` `Streamlit`

A deterministic AI agent memory integrity system addressing **OWASP ASI06 memory poisoning** — proves which memory caused a wrong answer without using another LLM as a judge.

**The core problem:** When an AI agent gives a wrong answer due to a poisoned memory, how do you prove which specific memory was responsible? My first approach (remove-one-at-a-time) failed with redundant poison. The solution was **ddmin delta debugging** — finding the minimal set of memories whose simultaneous removal corrects the answer.

**Architecture:**
- Quarantine enforced at **Redis KNN vector index level** using RediSearch FLAT index and cosine distance — poisoned memories physically cannot be retrieved
- Adaptive group testing and ddmin delta debugging to find the minimal guilty memory set
- Integrated **Arize Phoenix and OpenTelemetry** for full trace visibility, Sentry for incident reporting, LangGraph BaseStore adapter for agent memory
- **44 tests** across single-poison, redundant-poison, and staleness-rot scenarios

---

### False Alarms in AI Proctoring — hyrAI
**AI Learning Project · Aug 2026 – Present**

`Python` `MediaPipe` `Precision-Recall Analysis` `Data Labeling`

Analyzing real exam recordings to reduce false positive violation flags in AI proctoring systems. Building a labeled dataset of 300+ flagged violations and applying precision-recall analysis and threshold tuning to improve detection accuracy without sacrificing recall on real violations.

---

### Forager — Sustainable AI Fashion Assistant
**Irvine Hacks 2025**

`Vertex AI` `Flask` `React` `Depop API`

A full-stack AI fashion assistant that analyzes outfit images using Vertex AI vision models and recommends similar second-hand alternatives via the Depop API. Designed, integrated, and deployed end-to-end within 24 hours.

---

### CodeCraftHub — AI-Augmented Developer Learning Platform
`Node.js` `Express.js` `MongoDB` `Docker` `Generative AI` `GitHub Actions`

A personalized developer-learning platform with modular REST API backend, Dockerized deployment, GitHub CI/CD workflow, and generative AI tooling across the full SDLC. IBM edX capstone project.

---

### Fake News Detection — NLP Research Pipeline
`Python` `TF-IDF` `Logistic Regression` `Decision Trees` `scikit-learn` `ROC-AUC`

End-to-end NLP classification pipeline achieving ~91% accuracy on 10,000+ article dataset. Validated with F1, precision-recall curves, ROC-AUC, and stratified 5-fold cross-validation. Identified data leakage risks and delivered structured research paper.

---

### Python Systems Projects — UC Irvine
`Python` `SQLite` `Tkinter` `Event-Driven Architecture`

- Discrete-event alert propagation simulator
- SQLite-backed airport database engine with Tkinter GUI and parameterized CRUD
- Grin language interpreter with full label resolution, branching logic, and call-stack execution

---

### Data Structures & Algorithms Labs — UC Irvine
`C++` `GoogleTest` `CMake`

Implemented ArrayList, LinkedList, circular queue, QueueStack, and sorting algorithms in C++; validated correctness and edge-case behavior with GoogleTest unit test suites managed via CMake.

---

### Additional Technical Projects
`Python` `SQL` `Android` `OpenCV` `Thunkable`

- Blood Bank and Library Automation systems with SQL-driven record and transaction management
- DocTrack — Android utility app for document-expiration tracking and reminder workflows
- OpenCV edge detection prototypes, fitness and book review apps, meal plan generator
- UCI EngiTank with demo-driven iteration

---

## 🎓 Education

**University of California, Irvine — Donald Bren School of ICS**
B.S. Computer Science, Specialization in Intelligent Systems | Minor in Statistics
Sep 2024 – Jun 2028

- **GPA: 3.64 / 4.0**
- **Dean's Honor List:** Sep 2024 · Jan 2025 · Jan 2026 · Apr 2026
- **Relevant Coursework:** Artificial Intelligence (A), Information Retrieval (A+), Design & Analysis of Algorithms (B+), Data Structures (A–), Systems Programming C/C++, Linear Algebra (A+), Discrete Math (A), Statistics (A–)

---

## ⚙️ Technical Skills

| Category | Skills |
|---|---|
| **Languages** | Python · Java · C · C++ · SQL (Postgres) · JavaScript · HTML/CSS · R |
| **Frameworks & Backend** | Node.js · Express.js · Flask · FastAPI · React · REST APIs · MongoDB · PostgreSQL · SQLite · Redis |
| **AI / ML** | scikit-learn · NumPy · Pandas · Matplotlib · OpenCV · TF-IDF · Logistic Regression · Decision Trees · ROC-AUC · stratified cross-validation · LangGraph · FastMCP · Redis RediSearch · Arize Phoenix · OpenTelemetry · Sentry |
| **Cloud & Platforms** | AWS Lambda · Amazon Bedrock · Anthropic Claude API · Vertex AI · IBM Watson Studio · Docker · GitHub Actions |
| **Developer Tools** | Git · GitHub · CMake · GoogleTest · Figma · Three.js · VS Code · Cursor · GitHub Copilot · GitLab CI/CD · Salesforce CI/CD · Snyk · Dynatrace |

---

## 📜 Certifications

| Certification | Issuer | Date |
|---|---|---|
| Mastering Generative AI for Software Development | IBM edX | Mar 2026 |
| Node.js Certification (58 modules) | Scaler Topics | May 2026 |
| CI/CD for Salesforce (Official Certification) | DevOps Launchpad | Jul 2026 |
| AI Prompting for Everyone | DeepLearning.AI (Andrew Ng) | Jul 2026 |
| Introduction to Computer Science (CS50x) | HarvardX / edX (Verified) | — |
| UX Design Fundamentals | Georgia Tech | — |
| OOP in Java | Georgia Tech / Coursera | — |

---

## 🌟 Leadership & Community

- **Adobe Student Ambassador** — Adobe (2026–Present): Promoting creative AI and design tools within UCI's CS engineering community through content and peer outreach
- **Animal Care & Social Media Lead — UCI ACC**: Grew UCI ACC Instagram from baseline to **~15.3K average interactions** over 14 months through consistent content strategy and community engagement
- **Microsoft Student Ambassador** — Microsoft (2026–Present): Advocating Azure AI and GitHub tools among UCI students
- **WICS & Data@UCI — Member/Mentee**: Technical workshops, mentorship programs, and software-engineering professional development
- **Volunteer Tutor — Angel Xpress Foundation**: Weekly academic tutoring for underprivileged students

---

## 🏅 Honors & Awards

- 🏆 **Winner, AI Safety Track** — AWS Cloud Hacks 2026 (GlassBoxAI)
- **UC Berkeley AI Hackathon 2026 Participant** — Built IMMUNE (AI agent memory integrity)
- **17th Sheikh Zayed Memorial Education Award**
- **CBSE UAE Sahodaya Math Excellence**
- **Top 5 — Emirates Aviation Water Rocket Competition**
- **Guinness World Record Contributor** — Largest Water Safety Lesson, DCT Abu Dhabi

---

## 📫 Connect

🌐 **Portfolio:** [sixxhi.github.io](https://sixxhi.github.io)
💼 **LinkedIn:** [linkedin.com/in/siddhi-prajapati-127483268](https://www.linkedin.com/in/siddhi-prajapati-127483268/)
💻 **GitHub:** [github.com/Sixxhi](https://github.com/Sixxhi)
📧 **Email:** siddhi2277@gmail.com
📍 **Location:** Irvine, California, USA
