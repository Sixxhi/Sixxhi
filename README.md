<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Siddhi Prajapati — Resume</title>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,600;0,700;1,400&family=DM+Sans:ital,opsz,wght@0,9..40,300;0,9..40,400;0,9..40,500;0,9..40,600;1,9..40,300&display=swap" rel="stylesheet">
<style>
  :root {
    --ink: #0d0f14;
    --ink2: #1e2028;
    --muted: #6b7280;
    --rule: #e5e7eb;
    --navy: #1a3a5c;
    --gold: #b8842a;
    --gold-light: #f5efe6;
    --bg: #faf9f7;
    --tag: #eef1f6;
    --page: 920px;
  }
  * { box-sizing: border-box; margin: 0; padding: 0; }
  body {
    background: #ddd9d0;
    font-family: 'DM Sans', sans-serif;
    font-size: 12.8px;
    line-height: 1.55;
    color: var(--ink2);
    -webkit-font-smoothing: antialiased;
    text-align: justify;
  }
  .page {
    background: var(--bg);
    max-width: var(--page);
    margin: 32px auto;
    padding: 48px 54px 56px;
    box-shadow: 0 8px 48px rgba(0,0,0,0.14), 0 1px 4px rgba(0,0,0,0.06);
  }
  .header { margin-bottom: 22px; }
  .header-top {
    display: flex;
    justify-content: space-between;
    align-items: flex-end;
    padding-bottom: 14px;
    border-bottom: 2.5px solid var(--navy);
    margin-bottom: 10px;
  }
  h1 {
    font-family: 'Playfair Display', serif;
    font-size: 38px;
    font-weight: 700;
    color: var(--navy);
    letter-spacing: -0.5px;
    line-height: 1;
  }
  .contact-block {
    text-align: right;
    font-size: 11.5px;
    color: var(--muted);
    line-height: 1.75;
  }
  .contact-block a { color: var(--navy); text-decoration: none; font-weight: 600; border-bottom: 1px solid rgba(26,58,92,0.3); }
  .contact-block a:hover { border-color: var(--navy); }
  .tagline {
    font-size: 10.2px;
    color: var(--muted);
    letter-spacing: 0.04em;
    text-transform: uppercase;
    font-weight: 400;
    margin-bottom: 6px;
    white-space: nowrap;
  }
  .edu-line { font-size: 12.5px; color: var(--ink2); font-weight: 500; }
  .cpt-badge {
    display: inline-block;
    background: var(--navy);
    color: #fff;
    font-size: 9.5px;
    font-weight: 600;
    letter-spacing: 0.08em;
    padding: 2px 7px;
    border-radius: 2px;
    text-transform: uppercase;
    margin-left: 8px;
    vertical-align: middle;
  }
  .summary {
    font-size: 12.5px;
    color: var(--ink2);
    font-weight: 300;
    line-height: 1.7;
    padding: 13px 18px;
    border-left: 3px solid var(--gold);
    background: var(--gold-light);
    margin-bottom: 24px;
  }
  .summary b { font-weight: 600; color: var(--navy); }
  .two-col { display: grid; grid-template-columns: 1fr 1fr; gap: 0 28px; }
  .col-left { min-width: 0; }
  .col-right { min-width: 0; }
  .section { margin-bottom: 20px; }
  .section-title {
    font-size: 10px;
    font-weight: 600;
    letter-spacing: 0.2em;
    text-transform: uppercase;
    color: var(--navy);
    padding-bottom: 4px;
    border-bottom: 1.5px solid var(--navy);
    margin-bottom: 11px;
    text-align: left;
    opacity: 0.85;
  }
  .skill-row { display: flex; gap: 5px; font-size: 12px; margin-bottom: 4px; line-height: 1.5; }
  .skill-label { font-weight: 600; color: var(--navy); min-width: 125px; flex-shrink: 0; font-size: 11px; }
  .skill-val { color: var(--ink2); font-weight: 300; }
  .skill-val b { font-weight: 500; color: var(--ink); }
  .job { margin-bottom: 14px; }
  .job:last-child { margin-bottom: 0; }
  .job-header { display: flex; justify-content: space-between; align-items: baseline; gap: 6px; margin-bottom: 1px; text-align: left; }
  .job-title { font-weight: 600; font-size: 12px; color: var(--ink); text-align: left; flex: 1; min-width: 0; }
  .job-date { font-size: 10.5px; color: var(--muted); white-space: nowrap; font-weight: 300; text-align: right; flex-shrink: 0; }
  .job-org { font-size: 11.5px; color: var(--muted); margin-bottom: 5px; font-style: italic; text-align: left; }
  .bullets { padding-left: 0; }
  .bullets li {
    list-style: none;
    position: relative;
    padding-left: 13px;
    margin-bottom: 3px;
    font-size: 12px;
    font-weight: 300;
    color: var(--ink2);
    line-height: 1.52;
  }
  .bullets li::before { content: '·'; position: absolute; left: 3px; color: var(--gold); font-size: 14px; line-height: 1.3; font-weight: 700; }
  .bullets li b { font-weight: 500; color: var(--ink); }
  .bullets li .metric { font-weight: 600; color: var(--navy); }
  .project { margin-bottom: 13px; }
  .project:last-child { margin-bottom: 0; }
  .project-name { font-weight: 600; font-size: 12.5px; color: var(--ink); margin-bottom: 1px; text-align: left; }
  .project-name .award { color: var(--gold); font-size: 11.5px; font-weight: 600; }
  .project-tech { font-size: 11px; color: var(--muted); font-style: italic; margin-bottom: 3px; text-align: left; }
  .edu-school { font-weight: 600; font-size: 12.5px; color: var(--ink); }
  .edu-meta { font-size: 12px; color: var(--ink2); font-weight: 300; margin-top: 2px; }
  .edu-meta b { font-weight: 600; color: var(--navy); }
  .edu-sub { font-size: 11.5px; color: var(--muted); font-weight: 300; margin-top: 1px; }
  .edu-sub b { font-weight: 500; color: var(--ink2); }
  .cert-item { font-size: 12px; font-weight: 300; color: var(--ink2); margin-bottom: 4px; padding-left: 13px; position: relative; line-height: 1.5; }
  .cert-item::before { content: '·'; position: absolute; left: 3px; color: var(--gold); font-size: 14px; line-height: 1.3; font-weight: 700; }
  .cert-item strong { font-weight: 600; color: var(--navy); }
  .lead-item { font-size: 12px; font-weight: 300; color: var(--ink2); margin-bottom: 4px; padding-left: 13px; position: relative; line-height: 1.5; }
  .lead-item::before { content: '·'; position: absolute; left: 3px; color: var(--gold); font-size: 14px; line-height: 1.3; font-weight: 700; }
  .lead-item strong { font-weight: 600; color: var(--ink); }
  .lead-item .metric { font-weight: 600; color: var(--navy); }
  .honors-wrap { display: flex; flex-wrap: wrap; gap: 5px; text-align: left; }
  .honor { background: var(--tag); color: var(--navy); font-size: 11px; font-weight: 400; padding: 3px 8px; border-radius: 2px; border: 1px solid #d4dae6; }
  .honor.gold { background: var(--gold-light); border-color: #d4a85a; color: #7a5200; font-weight: 600; }
  .full-rule { border: none; border-top: 1px solid var(--rule); margin: 20px 0; }
  @media print {
    body { background: white; }
    .page { margin: 0; box-shadow: none; max-width: 100%; padding: 32px 40px; }
  }
</style>
</head>
<body>
<div class="page">

  <!-- HEADER -->
  <div class="header">
    <div class="header-top">
      <div>
        <h1>Siddhi Prajapati</h1>
        <div class="tagline" style="margin-top:6px;">Software Engineering &nbsp;|&nbsp; Applied AI &amp; Machine Learning &nbsp;|&nbsp; Backend Systems &nbsp;|&nbsp; Full-Stack &nbsp;|&nbsp; Cloud &amp; Data Infrastructure</div>
        <div class="edu-line" style="margin-top:4px;">University of California, Irvine &nbsp;|&nbsp; B.S. Computer Science, Minor in Statistics &nbsp;|&nbsp; Expected June 2028</div>
      </div>
      <div class="contact-block">
        <div>Irvine, CA</div>
        <div>siddhi2277@gmail.com</div>
        <div><a href="https://www.linkedin.com/in/siddhi-prajapati-127483268/" target="_blank">LinkedIn</a> &nbsp;·&nbsp; <a href="https://github.com/Sixxhi" target="_blank">GitHub</a> &nbsp;·&nbsp; <a href="https://sixxhi.github.io" target="_blank">sixxhi.github.io</a></div>
        <div style="margin-top:4px;"><span class="cpt-badge">CPT / F-1 Eligible</span></div>
      </div>
    </div>
  </div>

  <!-- SUMMARY -->
  <div class="summary">
    UCI CS Junior (<b>GPA 3.6, Dean's Honor List ×4</b>) actively building AI, backend, and full-stack systems across research and industry. <b>AWS Cloud Hacks 2026 AI Safety Track winner (GlassBoxAI)</b> and <b>UC Berkeley AI Hackathon 2026 participant (IMMUNE)</b>. Undergraduate researcher at <b>UCI Calit2 SMART ITAC</b>. Experience across full stack: NLP pipelines, agentic AI systems, cloud infrastructure, and database-backed applications. CPT/F-1 eligible — no employer sponsorship needed.
  </div>

  <!-- SKILLS -->
  <div class="section">
    <div class="section-title">Technical Skills</div>
    <div style="display:grid;grid-template-columns:1fr 1fr;gap:4px 32px;">
      <div class="skill-row"><span class="skill-label">Languages</span><span class="skill-val"><b>Python, Java, C, C++</b>, SQL, JavaScript, HTML/CSS</span></div>
      <div class="skill-row"><span class="skill-label">Cloud &amp; Platforms</span><span class="skill-val"><b>AWS Lambda, Amazon Bedrock, Anthropic Claude API</b>, Vertex AI, IBM Watson Studio</span></div>
      <div class="skill-row"><span class="skill-label">Frameworks &amp; Backend</span><span class="skill-val"><b>Node.js, Express.js, Flask, React</b>, REST APIs</span></div>
      <div class="skill-row"><span class="skill-label">Developer Tools</span><span class="skill-val"><b>Git, GitHub, Docker, GitHub Actions</b>, CMake, GoogleTest, Figma, Three.js, Cursor, GitHub Copilot</span></div>
      <div class="skill-row"><span class="skill-label">Databases</span><span class="skill-val"><b>MongoDB, PostgreSQL</b>, SQLite</span></div>
      <div class="skill-row"><span class="skill-label">Familiarity</span><span class="skill-val">GitLab CI/CD, Jenkins, Salesforce CI/CD, Snyk, Dynatrace</span></div>
      <div class="skill-row" style="grid-column:1/-1"><span class="skill-label">AI / ML</span><span class="skill-val"><b>scikit-learn, NumPy, Pandas, OpenCV</b>, TF-IDF, Logistic Regression, Decision Trees, ROC-AUC, stratified cross-validation, <b>Redis RediSearch, LangGraph, FastMCP, Arize Phoenix, OpenTelemetry, Sentry</b></span></div>
    </div>
  </div>

  <hr class="full-rule">

  <div class="two-col">

    <!-- LEFT COLUMN -->
    <div class="col-left">
      <div class="section">
        <div class="section-title">Experience</div>

        <div class="job">
          <div class="job-header">
            <div class="job-title">Undergraduate Research Assistant — VR &amp; AI Systems</div>
            <div class="job-date">Apr 2026 – Present</div>
          </div>
          <div class="job-org">UCI Calit2 SMART ITAC, University of California Irvine</div>
          <ul class="bullets">
            <li>Developing <b>VR training simulations</b> in SimInsights HyperSkill for building energy assessments and data center cooling efficiency; designing end-to-end scenario flows covering mechanical equipment, sensor systems, and operational procedures.</li>
            <li>Developing reasoning workflows for an <b>AI training agent</b> leveraging the ITAC database, ASHRAE guidelines, California building codes, and ISO standards to deliver contextualized simulation feedback.</li>
            <li>Build and maintain modular <b>backend pipelines</b> supporting AI agent evaluation, observability, and real-time simulation-feedback workflows.</li>
          </ul>
        </div>

        <div class="job">
          <div class="job-header">
            <div class="job-title">Data Science Research Intern — Fake News Detection</div>
            <div class="job-date">Jun – Jul 2025 · 4 weeks</div>
          </div>
          <div class="job-org">3E Worldwide / CHARUSAT</div>
          <ul class="bullets">
            <li>Built an end-to-end <b>NLP classification pipeline</b> in Python using TF-IDF feature extraction, n-gram modeling, Logistic Regression, and Decision Tree classifiers with scikit-learn; best-performing model achieved <span class="metric">~91% accuracy on a 10,000+ article dataset</span>.</li>
            <li>Evaluated model reliability using <b>F1, precision-recall, ROC-AUC</b>, and stratified 5-fold cross-validation; identified and flagged a data leakage risk in the original train/test split that had inflated accuracy metrics.</li>
            <li>Documented methodology, experiments, model comparisons, and insights in a <b>research-style paper and report</b>.</li>
          </ul>
        </div>

        <div class="job">
          <div class="job-header">
            <div class="job-title">Summer Programming Intern — C, C++ &amp; Java</div>
            <div class="job-date">Aug 2025 · 2 weeks</div>
          </div>
          <div class="job-org">dg8ly, The School of Digital Mastery</div>
          <ul class="bullets">
            <li>Built Student Records, Bank Management, and Library Management systems in <b>C/C++ and Java</b>, applying OOP, file handling, and modular design.</li>
          </ul>
        </div>

        <div class="job">
          <div class="job-header">
            <div class="job-title">Software Development Intern</div>
            <div class="job-date">Jun – Jul 2023 · 4 weeks</div>
          </div>
          <div class="job-org">SUPROS · Mentored by Ex-Microsoft / PayPal Engineer</div>
          <ul class="bullets">
            <li>Built and tested software modules for community-facing applications; applied <b>test-driven debugging</b>, iterative refactoring, and modular design under structured engineering mentorship.</li>
            <li>Translated feature requirements into modular tasks, participated in review cycles, and shipped maintainable and well-tested code.</li>
          </ul>
        </div>

        <div class="job">
          <div class="job-header">
            <div class="job-title">Open-Source Development Intern</div>
            <div class="job-date">Jul – Aug 2023 · 4 weeks</div>
          </div>
          <div class="job-org">BizzAppDev Systems Pvt. Ltd.</div>
          <ul class="bullets">
            <li>Contributed to an open-source <b>Python/XML codebase</b> backed by PostgreSQL; strengthened backend data-handling workflows and collaborative development practices.</li>
          </ul>
        </div>

        <div class="job">
          <div class="job-header">
            <div class="job-title">Technology &amp; Data Analytics Intern</div>
            <div class="job-date">Jul 2023 · 2 weeks</div>
          </div>
          <div class="job-org">cult.fit / Samsonite Projects</div>
          <ul class="bullets">
            <li>Prototyped a mobile wellness app in Thunkable with onboarding, goal tracking, and accessibility-first UX; built <b>Google Data Studio dashboards</b> with dynamic segmentation to surface business trends.</li>
          </ul>
        </div>
      </div>

      <!-- EDUCATION -->
      <div class="section">
        <div class="section-title">Education</div>
        <div class="edu-school">University of California, Irvine — Donald Bren School of ICS</div>
        <div class="edu-meta">B.S. Computer Science, Minor in Statistics &nbsp;·&nbsp; <b>GPA: 3.6 / 4.0</b> &nbsp;·&nbsp; Expected June 2028</div>
        <div class="edu-sub" style="margin-top:3px;"><b>Dean's Honor List:</b> Fall 2024 · Winter 2025 · Winter 2026 · Spring 2026</div>
        <div class="edu-sub">Coursework: Artificial Intelligence (A), Information Retrieval (A+), Design &amp; Analysis of Algorithms (B+), Data Structures (A-), Systems Programming C/C++, Linear Algebra (A+), Discrete Math (A), Statistics (A-)</div>
      </div>

      <!-- CERTIFICATIONS -->
      <div class="section">
        <div class="section-title">Certifications</div>
        <div class="cert-item"><strong>IBM edX</strong> — Mastering Generative AI for Software Development · Mar 2026 · AI-assisted SDLC, Dockerfile generation; applied through CodeCraftHub.</div>
        <div class="cert-item"><strong>Node.js Certification</strong> — Scaler Topics · May 2026 · 58 modules: Express.js, async JS, MongoDB/Mongoose, REST API with full CRUD.</div>
        <div class="cert-item"><strong>CI/CD for Salesforce</strong> — DevOps Launchpad (Official Certification) · Jul 2026 · CI/CD automation, release pipelines, and continuous delivery for Salesforce DevOps ecosystems.</div>
        <div class="cert-item"><strong>Harvard CS50x</strong> — Introduction to Computer Science · HarvardX / edX (Verified) · C, Python, SQL, JavaScript.</div>
        <div class="cert-item"><strong>UX Design Fundamentals</strong> — Georgia Tech · <strong>OOP in Java</strong> — Georgia Tech / Coursera · Both Verified.</div>
      </div>
    </div>

    <!-- RIGHT COLUMN -->
    <div class="col-right">
      <div class="section">
        <div class="section-title">Projects</div>

        <div class="project">
          <div class="project-name">GlassBoxAI — Agentic AI Safety Observability Platform &nbsp;<span class="award">🏆 Winner · AI Safety Track, AWS Cloud Hacks 2026</span></div>
          <div class="project-tech">AWS Lambda · Amazon Bedrock · Three.js · Figma</div>
          <ul class="bullets">
            <li>Built a <b>real-time AI safety observability platform</b> for a Smart Stadium Simulator end-to-end in 24 hours — monitored agent reasoning traces, safety scores, and tool-call sequences; <span class="metric">detected 100% of injected high-risk scenarios with zero false negatives</span> during live judging.</li>
            <li>Designed the full <b>dark-mode UI in Figma</b>, implemented an interactive <b>Three.js globe/stadium visualization</b>, and configured AWS Lambda + Bedrock integrations for agent reasoning and safety evaluation pipelines.</li>
            <li>Caught a critical <b>Amazon Bedrock API parsing bug</b> during integration testing — Copilot-generated code assumed flat JSON when Bedrock nests output inside a content array; identified by testing Lambda functions against live endpoints before demo.</li>
          </ul>
        </div>

        <div class="project">
          <div class="project-name">IMMUNE — AI Agent Memory Integrity System &nbsp;<span style="font-weight:300;font-size:11.5px;color:var(--muted);">UC Berkeley AI Hackathon 2026, Participant</span></div>
          <div class="project-tech">Python · Redis RediSearch · Anthropic Claude Haiku 4.5 · LangGraph · FastMCP · Arize Phoenix · OpenTelemetry · Sentry</div>
          <ul class="bullets">
            <li>Built a <b>deterministic AI agent memory integrity system</b> addressing OWASP ASI06 memory poisoning — proves which memory caused a wrong answer through counterfactual replay and delta debugging with <b>no LLM judge</b> in the attribution loop.</li>
            <li>Enforced quarantine at <b>Redis KNN vector index level</b> using RediSearch FLAT index and cosine distance — poisoned memories physically cannot be retrieved; implemented adaptive group testing and <b>ddmin delta debugging</b> to find the minimal guilty memory set.</li>
            <li>Integrated <b>Arize Phoenix and OpenTelemetry</b> for full trace visibility, Sentry for incident reporting, and LangGraph BaseStore adapter for agent memory; <span class="metric">44 tests</span> across single-poison, redundant-poison, and staleness-rot scenarios.</li>
          </ul>
        </div>

        <div class="project">
          <div class="project-name">Forager — Sustainable AI Fashion Assistant &nbsp;<span style="font-weight:300;font-size:11.5px;color:var(--muted);">Irvine Hacks 2025</span></div>
          <div class="project-tech">Vertex AI · Flask · React · Depop API</div>
          <ul class="bullets">
            <li>Built a full-stack <b>AI fashion assistant</b> that analyzes outfit images with <b>Vertex AI vision models</b> and recommends second-hand alternatives via the Depop API; designed, integrated, and deployed end-to-end within 24 hours.</li>
          </ul>
        </div>

        <div class="project">
          <div class="project-name">CodeCraftHub — AI-Augmented Developer Learning Platform</div>
          <div class="project-tech">Node.js · Express.js · MongoDB · Docker · Generative AI</div>
          <ul class="bullets">
            <li>Designed modular <b>REST APIs and backend services</b> using Node.js, Express.js, and MongoDB; <b>Dockerized deployment</b> with GitHub CI/CD workflow and generative AI tooling across the full SDLC. IBM edX capstone.</li>
          </ul>
        </div>

        <div class="project">
          <div class="project-name">Python Systems Projects · UC Irvine</div>
          <div class="project-tech">Python · SQLite · Tkinter · Event-Driven Architecture</div>
          <ul class="bullets">
            <li>Built a <b>discrete-event alert propagation simulator</b>, SQLite-backed airport database engine with Tkinter GUI and parameterized CRUD, and a <b>Grin language interpreter</b> with label resolution, branching, and call-stack execution.</li>
          </ul>
        </div>

        <div class="project">
          <div class="project-name">Data Structures &amp; Algorithms Labs · UC Irvine</div>
          <div class="project-tech">C++ · GoogleTest · CMake</div>
          <ul class="bullets">
            <li>Implemented ArrayList, LinkedList, circular queue, QueueStack, and sorting algorithms in <b>C++</b>; validated correctness and edge-case behavior with <b>GoogleTest</b> unit test suites managed via CMake.</li>
          </ul>
        </div>

        <div class="project">
          <div class="project-name">Additional Technical Projects · Personal / UC Irvine</div>
          <div class="project-tech">Python · SQL · Android · OpenCV · Thunkable</div>
          <ul class="bullets">
            <li>Built database-backed <b>Blood Bank and Library Automation</b> systems with SQL-driven record, inventory, user, and transaction management; developed <b>DocTrack</b>, an Android utility app for document-expiration tracking and reminder workflows.</li>
            <li>Developed additional prototypes spanning <b>OpenCV edge detection</b>, fitness and book review apps, a meal plan generator, Scratch ML-style projects, and UCI EngiTank with demo-driven iteration.</li>
          </ul>
        </div>
      </div>

      <!-- LEADERSHIP -->
      <div class="section">
        <div class="section-title">Leadership &amp; Community</div>
        <div class="lead-item"><strong>Animal Care &amp; Social Media Lead — UCI ACC:</strong> Grew UCI ACC Instagram from baseline to <span class="metric">~15.3K average interactions</span> over 14 months through consistent content strategy and community engagement.</div>
        <div class="lead-item"><strong>WICS &amp; Data@UCI — Member/Mentee:</strong> Technical workshops, mentorship programs, and software-engineering professional development.</div>
        <div class="lead-item"><strong>Volunteer Tutor — Angel Xpress Foundation:</strong> Weekly academic tutoring for underprivileged students.</div>
      </div>

      <!-- HONORS -->
      <div class="section">
        <div class="section-title">Honors &amp; Awards</div>
        <div class="honors-wrap">
          <span class="honor gold">🏆 AWS Cloud Hacks 2026 — AI Safety Track Winner</span>
          <span class="honor">UC Berkeley AI Hackathon 2026 Participant — IMMUNE</span>
          <span class="honor">17th Sheikh Zayed Memorial Education Award</span>
          <span class="honor">CBSE UAE Sahodaya Math Excellence</span>
          <span class="honor">Top 5 · Emirates Aviation Water Rocket</span>
          <span class="honor">Guinness World Record Contributor — Largest Water Safety Lesson, DCT Abu Dhabi</span>
        </div>
      </div>

    </div>
  </div>

</div>
</body>
</html>
