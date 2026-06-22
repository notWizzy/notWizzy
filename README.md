# Hi, I'm Kashyap 👋

🙍‍♂️ **About me**

I am currently a Data Engineer at Parexel, focused on building high-integrity data systems. My core work involves engineering scalable ingestion pipelines—handling both full loads and Change Data Capture (CDC)—to move critical finance data from Oracle EBS into ADLS Gen2 and Databricks. Because data reliability is paramount, I built a reconciliation framework that continuously validates replication across 400+ high-volume tables, ensuring absolute trust in downstream analytics.

I have a strong bias for action and a passion for automation. Recently, I identified a tedious workflow requiring over 20,000 manual database operations and collaborated with a teammate to fully automate it using PySpark and the OpenAI API. This transformed a high-risk, time-consuming process into an efficient, auditable system, saving hundreds of hours.

My approach to data engineering is heavily influenced by my software engineering background and internships at Fidelity. I treat data pipelines as distributed systems, prioritizing modularity, robust testing, and fault tolerance. Ultimately, I am driven to apply these engineering-first principles to architect robust data platforms operating at a global scale.

---

📌 **Experience highlights**
- **Parexel International | Data Engineer (February 2025 - Present)**
  - Designed and engineered a scalable Databricks reconciliation framework to prevent silent data loss across 400+ Oracle tables (5B+ records), automating source-to-target validation and logging discrepancies in an auditable Delta metrics table.
  - Decreased Change Data Capture monitoring latency from minutes to ~20 seconds by engineering a scheduled Databricks API automation, replacing error-prone manual UI checks.
  - Replaced 20,000+ manual database operations by building a PySpark and OpenAl automation that auto-generates table descriptions and executes the SQL needed to keep the Databricks catalog updated.

- **Fidelity Investments | Software Engineer Intern (June 2024 - August 2024)**
  - Mitigated production rollout risks and established deployment safety by migrating legacy feature flags to LaunchDarkly, engineering 50+ automated unit tests to catch regressions and prevent broken deployments.
  - Reduced deployment risk for a micro-frontend application by engineering comprehensive Postman test collections, rigorously validating REST and GraphQL API data accessibility prior to deployments.
  - Reduced deployment risk and release latency by transitioning tightly coupled UI workflows into a micro-frontend architecture, isolating team dependencies so individual modules could be deployed independently.
  - Boosted Planning Intelligence Engine accuracy by 15% by engineering data transformation workflows for Neo4j Knowledge Graph ingestion, resolving underlying dataset inconsistencies and improving downstream decision-making.

- **Fidelity Investments | Full Stack Developer Intern (June 2023 - August 2023)**
  - Replaced manual application checks by developing a real-time AngularJS health dashboard, continuously polling status APIs to instantly flag system outages across 5 internal environments.
  - Reduced initial page load time by 25% by replacing a render-blocking JavaScript splash screen with a lightweight CSS-only version, allowing the core application to load significantly faster.

---

⭐ **Projects**
- **Errex — AI-Powered Terminal Debugger**
  - Go CLI tool that executes shell commands, captures stderr on failure, and routes the error output to a locally hosted LLM via Ollama to generate a structured plain-English diagnosis with an exact remediation command
  - Engineered a constrained prompt schema enforcing a strict three-part diagnostic format, replacing verbose model responses with specific fixes referencing exact file paths and shell commands
  - Architected isolated internal packages for CLI orchestration (Cobra), LLM inference (Ollama HTTP client), and terminal rendering (Lip Gloss) with a GitHub Actions CI pipeline validating builds on every push

---

🛠️ **Tech I use**
- **Data:** Databricks (Delta, PySpark), Azure Data Factory, Azure Data Lake, Striim Cloud
- **Languages:** Python, SQL, Java, JavaScript, TypeScript
- **Web/Tools:** Node.js, Express, React, Angular, Docker, Git, Jenkins, Postman, Jira, Confluence
- **Other:** Oracle SQL Developer, SSMS, MongoDB, Neo4j

---

**Connect**
- 🔗 LinkedIn: https://www.linkedin.com/in/kashyap-patel-318b791a0/
- 🧑‍💻 GitHub: https://github.com/notWizzy
- ✉️ Email: kashyap76315@icloud.com
