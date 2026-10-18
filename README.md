# Hi 👋, I'm Siddhi Prajapati

**Computer Science Senior · University of California, Irvine · Expected December 2027**

> Software engineer focused on AI systems that are reliable, observable and trustworthy. I build agentic AI safety platforms, evaluation workflows, backend services and full-stack products.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue)](https://www.linkedin.com/in/siddhi-prajapati-127483268/)
[![Portfolio](https://img.shields.io/badge/Portfolio-sixxhi.github.io-navy)](https://sixxhi.github.io)
[![GitHub](https://img.shields.io/badge/GitHub-Sixxhi-black)](https://github.com/Sixxhi)
[![Email](https://img.shields.io/badge/Email-siddhi2277%40gmail.com-red)](mailto:siddhi2277@gmail.com)

> **🟦 Availability:** Summer 2027 internships (CPT, June 21 to September 11, 2027) · Full-time from January 2028 (OPT)

---

## 👩‍💻 About Me

I am a CS senior at UC Irvine specializing in Intelligent Systems, with a minor in Statistics (GPA 3.663, Dean's Honor List: Fall 2024, Winter 2025, Winter 2026, Spring 2026). I care about building software that works correctly under real conditions, not only in a demo.

My work spans agentic AI safety, backend engineering, NLP pipelines, cloud services and full-stack development. I won the AI Safety Track at AWS Cloud Hacks 2026, built IMMUNE at the UC Berkeley AI Hackathon 2026, led a team at ZotHacks 2026, worked as an AI Software Engineer at hyrAI reducing false-positive flags on an AI interview platform, and did research at UCI Calit2 SMART ITAC.

**Currently:**
- 📚 Completing the **Machine Learning Specialization** (Andrew Ng, Coursera)
- 🎯 Seeking Summer 2027 software engineering and AI/ML internships
- ✍️ Writing about my work on **[dev.to](https://dev.to/siddhi_prajapati_6eb49986/immune-deterministic-memory-attribution-for-ai-agents-using-delta-debugging-lb2)**

---

## 🚀 Featured Projects

### 🏆 GlassBoxAI: Agentic AI Safety Observability Platform
**Winner, AI Safety Track, AWS Cloud Hacks 2026**

`AWS Lambda` `Amazon Bedrock` `Three.js` `Figma` `Python` `JavaScript` `GitHub Actions`

A real-time AI safety observability platform for a Smart Stadium Simulator. It monitors agent reasoning chains, safety scores, tool-call traces and critical system alerts. Built end to end in 24 hours.

**What I built:**
- The **backend**: AWS Lambda functions, Amazon Bedrock pipelines for agent reasoning and automated judging, safety scoring logic and alert propagation
- The **frontend**: an interactive Three.js globe and stadium visualization with a dark-mode UI designed in Figma
- A **GitHub Actions CI pipeline** that runs automated tests against the Lambda endpoints on every push
- Caught a critical **Bedrock API parsing bug** through live endpoint testing before the demo. The AI-generated code assumed flat JSON, but Bedrock nests its output inside a content array

**Result:** Detected 100% of injected high-risk scenarios with zero false negatives during live judging.

---

### IMMUNE: Deterministic Memory Integrity for AI Agents
**UC Berkeley AI Hackathon 2026**

`Python` `Redis RediSearch` `Claude Haiku 4.5` `LangGraph` `FastMCP` `Arize Phoenix` `OpenTelemetry` `Sentry` `Streamlit`

A deterministic memory integrity system for AI agents, addressing **OWASP ASI06 memory poisoning**. It proves which memory caused a wrong answer without using another LLM as a judge.

**The core problem:** When an agent answers wrongly because of a poisoned memory, how do you prove which memory was responsible? My first approach (remove one memory at a time) failed when the poison was redundant. The fix was **ddmin delta debugging**, which finds the minimal set of memories whose removal corrects the answer.

**Architecture:**
- Quarantine is enforced at the **Redis KNN vector index level** (RediSearch FLAT index, cosine distance), so poisoned memories cannot be retrieved
- Counterfactual replay and ddmin delta debugging to isolate the minimal guilty memory set
- **Arize Phoenix and OpenTelemetry** for trace visibility, Sentry for incident reporting and a LangGraph BaseStore adapter for agent memory
- **44 tests** across single-poison, redundant-poison and staleness-rot scenarios

📝 [Read the write-up on dev.to](https://dev.to/siddhi_prajapati_6eb49986/immune-deterministic-memory-attribution-for-ai-agents-using-delta-debugging-lb2)

---

### ZotStudy: UCI Study Session Finder (Team Lead)
**ZotHacks 2026**

`React` `Vite` `JavaScript` `Firebase Authentication` `Firestore` `Vercel`

A web app to find, create and join UCI study sessions. I led a first-time hackathon team, helped teammates resolve errors including Git merge conflicts, and deployed the app on Vercel.

---

### CodeCraftHub: AI-Augmented Developer Learning Platform
`Node.js` `Express.js` `MongoDB` `Docker` `GitHub Actions` `Generative AI`

A personalized developer-learning platform with modular REST APIs, Docker deployment and a GitHub Actions CI/CD workflow. Generative AI tooling was applied across the software development lifecycle. IBM edX capstone project.

---

### Forager: Sustainable AI Fashion Assistant
**Irvine Hacks 2025**

`Vertex AI` `Flask` `React` `Depop API`

A full-stack AI fashion assistant that analyzes outfit images with Vertex AI vision models and recommends similar second-hand items through the Depop API. Designed, integrated and deployed end to end in 24 hours.

---

### More Projects
- **Python Systems Projects** (Python, SQLite, Tkinter): a discrete-event alert propagation simulator, a SQLite-backed airport database engine with a Tkinter GUI and parameterized CRUD, and a Grin language interpreter with label resolution, branching and call-stack execution
- **Data Structures and Algorithms Labs** (C++, GoogleTest, CMake): ArrayList, LinkedList, circular queue, QueueStack and sorting algorithms using object-oriented design, tested with GoogleTest through CMake
- **Fake News Detection** (Python, scikit-learn): NLP classification pipeline with about 91% accuracy on a 10,000+ article dataset (see Experience)
- **DocTrack** (Android): a document-expiry tracker with login, local storage and alert notifications

---

## 💼 Experience

### AI Software Engineer
**hyrAI / SkillJourney** · Aug 2026 – Sep 2026 · Remote

hyrAI builds AI-powered interview and proctoring systems for hiring.

- Built a labeled dataset of **300+ flagged integrity violations** with ground-truth annotations separating genuine violations from false alarms, to reduce false-positive flags on an AI voice and video interview platform
- Applied **precision-recall analysis** and threshold tuning with Python and MediaPipe to improve detection accuracy while preserving recall on real violations

### Undergraduate Research Assistant, VR & AI Systems
**UCI Calit2 SMART ITAC, University of California, Irvine** · Apr 2026 – Jun 2026 · Irvine, CA

SMART ITAC provides free energy efficiency assessments to small and medium enterprises. It is led by Professor GP Li and funded by the U.S. Department of Energy.

- Developed **VR training simulations** in SimInsights HyperSkill for building energy assessments and data center cooling efficiency
- Built reasoning workflows for an **AI training agent** using the ITAC database, ASHRAE guidelines, California building codes and ISO standards to give contextual simulation feedback
- Applied **system design principles** to build modular backend pipelines for agent evaluation, observability and simulation feedback

### Data Science Research Intern, Fake News Detection
**3E Worldwide (in partnership with CHARUSAT)** · Jun 2025 – Jul 2025 · Remote, India

- Built an end-to-end **NLP classification pipeline** in Python with TF-IDF, n-gram modeling, Logistic Regression and Decision Tree classifiers. The best model reached **about 91% accuracy on a 10,000+ article dataset**
- Evaluated reliability with **F1, precision-recall, ROC-AUC** and 5-fold cross-validation, and flagged a data leakage risk in the original train/test split that had inflated accuracy
- Documented the methodology and results in a research-style paper

### Open-Source Development Intern
**BizzAppDev Systems Pvt. Ltd.** · Jul 2023 – Aug 2023 · Remote

- Contributed backend modules to an open-source **Python/XML codebase** (PostgreSQL), following modular design patterns and REST API conventions with a distributed team

### Software Development Intern
**SUPROS** · Jun 2023 – Jul 2023 · Remote

- Built and tested software modules for community-facing applications under mentorship, using test-driven debugging, iterative refactoring and modular design
- Translated feature requirements into engineering tasks and took part in code review cycles

---

## 🎓 Education

**University of California, Irvine, Donald Bren School of ICS**
B.S. Computer Science, Intelligent Systems specialization · Minor in Statistics · Sep 2024 – Dec 2027

- **GPA:** 3.663 / 4.0
- **Dean's Honor List:** Fall 2024 · Winter 2025 · Winter 2026 · Spring 2026
- **Coursework:** Artificial Intelligence (A), Information Retrieval (A+), Design and Analysis of Algorithms (B+), Data Structures (A-), Systems Programming in C/C++, Linear Algebra (A+), Discrete Math (A), Statistics (A-)
- **In progress:** Data Management (CS 122A), Probability in Computer Science (CS 177), Machine Learning and Data Mining (CS 178)

---

## ⚙️ Technical Skills

| Category | Skills |
|---|---|
| **Languages** | Python · Java · C · C++ · SQL (Postgres) · JavaScript · HTML/CSS · R |
| **Concepts** | Object-Oriented Programming · Data Structures · Algorithms · Unit Testing |
| **Backend and Frameworks** | Node.js · Express.js · Flask · React · REST APIs · MongoDB · PostgreSQL · SQLite · Redis |
| **AI / ML** | scikit-learn · NumPy · Pandas · OpenCV · LangGraph · FastMCP · Redis RediSearch · Arize Phoenix · OpenTelemetry · Sentry |
| **Cloud and DevOps** | AWS Lambda · Amazon Bedrock · Anthropic Claude API · Vertex AI · Docker · GitHub Actions · Salesforce CI/CD |
| **Tools** | Git · GitHub · CMake · GoogleTest · Figma · Three.js · VS Code |

---

## 📜 Certifications

- CI/CD for Salesforce (DevOps Launchpad), Jul 2026
- AI Prompting for Everyone (DeepLearning.AI), Jul 2026
- Node.js Certification, 58 modules (Scaler Topics), May 2026
- Mastering Generative AI for Software Development (IBM edX), Mar 2026
- Introduction to Computer Science, CS50x (HarvardX / edX), Jul 2025
- Object-Oriented Programming in Java (Georgia Tech / Coursera)
- UX Design Fundamentals (Georgia Tech)

---

## 🌟 Leadership and Community

- **Learning Assistant, ICS 31: Introduction to Programming, UC Irvine** (Sep 2026 – Present): Support 30+ students in introductory Python through office hours, concept explanations and code feedback. Completed UCI CLAP pedagogical training
- **Adobe Student Ambassador** (Aug 2026 – Present): Promote creative AI and design tools in UCI's CS community
- **Animal Care and Social Media Lead, UCI ACC:** Grew the Instagram account to about 15.3K average interactions over 14 months
- **WICS and Data@UCI:** Member and mentee in technical workshops and mentorship programs
- **Volunteer Tutor, Angel Xpress Foundation:** Weekly tutoring for underprivileged students

---

## 🏅 Honors and Awards

- 🏆 **Winner, AI Safety Track**, AWS Cloud Hacks 2026 (GlassBoxAI)
- **UC Berkeley AI Hackathon 2026 Participant** (IMMUNE)
- **17th Sheikh Zayed Memorial Education Award**
- **CBSE UAE Sahodaya Math Excellence**
- **Top 5**, Emirates Aviation Water Rocket Competition
- **Guinness World Record Contributor**, Largest Water Safety Lesson, DCT Abu Dhabi

---

## 📫 Connect

🌐 **Portfolio:** [sixxhi.github.io](https://sixxhi.github.io)
💼 **LinkedIn:** [linkedin.com/in/siddhi-prajapati-127483268](https://www.linkedin.com/in/siddhi-prajapati-127483268/)
💻 **GitHub:** [github.com/Sixxhi](https://github.com/Sixxhi)
📧 **Email:** siddhi2277@gmail.com
📍 **Location:** Irvine, California, USA
