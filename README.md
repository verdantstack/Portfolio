# Nicholas Rodak | Strategic Intelligence & Operations Portfolio

Strategic Intelligence & Operations Portfolio

This repository demonstrates the technical execution of intelligence tradecraft.

While traditional analysis stops at the report, this portfolio focuses on operationalizing intelligence—building the automated Python pipelines, mock-driven frameworks, and "Minimum Viable Systems" (MVS) required to answer Key Intelligence Questions (KIQs) in real-time.

Core Focus: R&D Laboratories for bridging the gap between high-level strategic intent and technical reality.

---

## Delphi v1.0 (Internal Tooling)

>**Key Intelligence Question:** How does a soverign, offline AI system function as a reliable, secure force multipler for strategic intelligence analysis and decision support?

A local-first, air-gapped Retrieval-Augmented Generation (RAG) system engineered to prioritize proprietary doctrine and hard data over general model weights. Delphi is architected with a strict "Hierarchy of Truth" and defined mental models to eliminate hallucinations and enforce rigorous analytic methodology and tradecraft, allowing the incorporation of sensitive information into workflow and decision-making processes. The system is a long-term initiative for internal business development (e.g. HydroMesh, etc).

* **Technology Stack:** Local LLM (Llama 3 / DeepSeek), Ollama, Open WebUI, Python (Telemetry Ingestion), Ubuntu
* **Status:** Actively Developing: Hierarchy, Mental Models Architecture Defined / Data Collection (Continuous), Defining Hardware Requirements
* **Workflow:**
  * **Ingestion:** Tiered data architecture that ranks information sources and differentiates between high-fidelity and general open-source knowledge.
  * **Arbitration:** Strict logic layer that forces the model to priortize "Commander's Intent" and hard data over its base training data.
  * **Analysis:** Dynamic persona switching using defined "Mental Models" to automatically shift the analytic framework based on operational context.
  * **Relevance:** Relates responses to standing assessments and assumptions.  

## AcousticPump v1.0 (MVS)

>**Key Intelligence Question:** How can observable crypto-manipulation behaviors bridge the intelligence gap between open-source signals and on-chain transactions to attribute serial malicious actors?

A specialized intelligence collection tool/workflow designed to test the correlation between social engineering events (OSINT) and blockchain forensics. The system utilizes a Mock-Driven Development (MDD) framework to simulate adversarial tradecraft, validating a "Hunter-Listener-Analyst" workflow that detects behavioral patterns across the "OSINT-to-On-Chain" divide to identify funding clusters.

* **Technology Stack:** Python, SQLite, Alchemy SDK (Web3), PRAW (Reddit), Telethon (Telegram), Mock-Driven Data Simulation.
* **Status:** `MVS MDD Complete / Pipeline Logic Validated`
* **Workflow:**
  * **Hunter (Discovery):** Automates the scraping and sanitization of "dirty" OSINT leads (Reddit) to identify high-risk Telegram channels. Note: Future live capability incorporates human-in-the-loop OSINT investigation validates and prioritizes target channels for Listener module.
  * **Listener (Collection):** Monitors targeted channels for obfuscated "pre-pump" signals (Coin Ticker, Time, Exchange Context).
  * **Translator (Normalization):** Maps social signals to actionable Contract Addresses via multi-chain lookups.
  * **Analyst (Attribution):** Executes heuristic trace-back logic on the blockchain to identify the specific wallets funding the intial pump purchases.
* **Conclusion:** Rapid prototyping demonstrated through this project can be used to test novel, tailored targeting methodologies against dynamic adversary behavior and establish the technical roadmap for moving from controlled (MDD) to real-time environment. Future updates to operationalize methodology should include integration of OCR (Tesseract) to parse image-based signals, NLP for complex date parsing, and development of live API sensors to production clean room environment.
* **Code Repository:** The code for this project is in a private repository, available upon request.

---
## HydroMesh v1.0
> **Key Intelligence Question:** How can a decentralized sensor mesh enable real-time command and control (C2) over autonomous, distributed logistics nodes?  

A scalable data engineering framework designed to monitor and optimize a network of independent production units ("microfarms"). The system validates the New Virginia Microfarms (NVMF) operational concept by aggregating environmental telemetry into a centralized dashboard, proving the viability of autonomous, distributed supply chains.

* **Technology Stack:** Python (Data Automation) Google Sheets API (Data Lake), Looker Studio (Dashboard), IoT Sensors (Hardware Telemetry).
* **Status:** `Actively Developing: Architecture Defined / Prototyping Phase`
* **Workflow:**
  * **Collection (Edge Nodes):** Physical prototype production nodes act as data generators, producing raw operational and production metrics.
  * **Ingestion/Integration (Mesh):** Multi-vector data pipelines (telemetry, user input, forecast projections) normalized into a unified structural database.
  * **Visualization (C2 Dashboard):** Displays real-time Heath & Status indicators, enabling data-driven decisions and validation of NVMF key performance indicators (KPI).
* **Next Steps:** Once validation of KPIs, expand and itegrate real-time low-cost hardware sensors, implement automated alert logic for node failures and warnings.  
  
---
## MarketFeel v1.1

> **Key Intelligence Question:** What is the real-time sentiment and narrative of public discourse surrounding the U.S. economy?

An automated OSINT pipeline that tracks daily economic sentiment from Reddit using a FinBERT NLP model and visualizes the live output with an interactive Looker Studio dashboard.

* **Live Dashboard:** https://lookerstudio.google.com/s/uPVKEKSONHw
* **Technology Stack:** Python, Reddit API, NLP (Hugging Face), Google Cloud, Google Sheets, Looker Studio.
* **Status:** `Live / Updating Daily`
* **Workflow:**
  * **Discover:** Executed recursive searches across r/all for neutral economic keywords across economic topics.
  * **Prioritize:** Upvote Ratio threshold serves as proxy to identify high-velocity narratives and reduce processing volume to high-consensus posts.
  * **Filter:** Applies a multi-layer mesh (Topical, Geographic, and "Not of Interest" keywords) to systematically prune irrelevant noise.
  * **Analysis:** Employs a domain-specific NLP layer with contextual overrides to correctly interpret economic modifiers and assign high-fidelity sentiment scores.
* **Conclusion:** Closer analyst investigation of sentiment shifts can be correlated to real-world events; however, the signal-to-noise ratio, despite robust filtering, and ambiguous sentiment (neutral posts) remain a challenge. These challenges, along with nearly certain bot activity, suggest that the current vector (Reddit) does not consistently produce reliable, authentic sentiment. Future iterations should refine the KIQ and methodology to focus on an "expert panel" as a proxy for sentiment and public discourse, thereby reducing ambiguous and inauthentic data points.  
* **Code Repository:** The code for this project is in a private repository, available upon request.

---
## SignalBot v2.0

> **Key Intelligence Question:** How does a rules-based, top-down analytical trading strategy perform against emotionally-driven investment decisions?

A quantitative system designed to test rule-based logic against emotional market behavior. Uses a modular, multi-bot architecture to automate decision hierarchies.

* **Technology Stack:** Python, FRED API, Financial Data (Yahoo Finance), Google Cloud, Google Sheets, Looker Studio.
* **Status:** `Core Functionality Complete`
* **Workflow (Core Functionality):**
  * **Strategic Assessment:** Determines overall "Risk-On/Risk-Off" posture based on yield curves and momentum.
  * **Technical Filtering:** Executes scan of pre-defined sector ETFs to identify sectors outperforming SPY and then identifies "Alpha Symbols" within identified sectors (relative strength score, moving average, breakout trigger, volume confirmation)
* **Conclusion:** The system successfully demonstrated that rules-based Python bots can effectively prioritize and highlight "winning" ticker symbols in backtesting. Realistic limitations of API latency and human-in-the-loop requirements for trade execution renders the the strategy uncompetitive against institutional HFT algorithms.   
* **Code Repository:** The code for this project is in a private repository, available upon request.
