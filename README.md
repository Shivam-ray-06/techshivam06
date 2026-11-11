<div align="center">

<!-- Profile View Counter -->
<img src="https://komarev.com/ghpvc/?username=Shivam-ray-06&style=for-the-badge&color=0d1117&label=PROFILE+VIEWS" alt="Profile Views" />

<br/><br/>

# Shivam Swastik Ray

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=58A6FF&center=true&vCenter=true&width=700&lines=AI+%26+Data+Science+Undergrad+%40+ADYPU+Pune;Temporal+Graph+Intelligence+%7C+Cybersecurity;Multimodal+AI+%7C+Systems+Engineering;Building+at+the+intersection+of+ML+%26+Security" alt="Typing SVG" />

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shivam-swastik-ray-2b23a1409)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Shivam-ray-06)

</div>

---

## 🧑‍💻 About Me

I am a **B.Tech student in Artificial Intelligence & Data Science** at **Ajeenkya D Y Patil University, Pune** (Class of 2029), building multi-language systems at the intersection of machine learning, cybersecurity research, and scalable software architecture.

My work focuses on **temporal graph intelligence**, **intrusion detection**, **multimodal AI evaluation**, and **systems-level engineering** — writing production-quality code in C++, Java, Python, and TypeScript, often within the same project.

```text
🎓  B.Tech · AI & Data Science · ADYPU Pune · 2025 – 2029
🔬  Research: Temporal Graphs · Anomaly Detection · Multimodal Reasoning
⚙️  Engineering: Multi-language systems · Cybersecurity · ML pipelines
🌍  Open to research collaborations and engineering internships
```

---

## 🛠️ Technology Stack

<div align="center">

**Languages**

[![My Skills](https://skillicons.dev/icons?i=cpp,python,java,javascript,typescript&theme=dark)](https://skillicons.dev)

**Frameworks & Tools**

[![My Skills](https://skillicons.dev/icons?i=react,fastapi,postgresql,docker,git,github,pytorch,tensorflow,opencv,aws&theme=dark)](https://skillicons.dev)

</div>

---

## 🚀 Featured Projects

> Projects listed in order of research depth and engineering complexity.

---

### 🔬 1 · ChronoGraph — Temporal Graph Intelligence for Intrusion Detection

<div align="center">

[![ChronoGraph](https://img.shields.io/badge/ChronoGraph-Temporal%20Graph%20IDS-58A6FF?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Shivam-ray-06/chronograph)
![Status](https://img.shields.io/badge/Status-Active%20Research-brightgreen?style=for-the-badge)
![Languages](https://img.shields.io/badge/Stack-C%2B%2B17%20%7C%20Java17%20%7C%20Python%20%7C%20TypeScript-orange?style=for-the-badge)

</div>

**ChronoGraph** is a student research prototype exploring whether **temporal network graph analysis** — tracking how network relationships evolve across time-ordered sliding-window snapshots — can surface anomalous behaviour that static flow classifiers may miss.

> **Research Status:** This is an early prototype. No detection performance, novelty, or zero-day capability has been established. All baseline results are validated with leakage-resistant chronological splits.

#### 🏗️ Multi-Language Architecture

| Layer | Technology | Role |
|---|---|---|
| **Graph & Feature Engine** | C++17 | Streaming temporal graph, sliding-window feature extraction, timestamp validation, RFC 4180 CSV reader, 24+ unit tests |
| **REST Orchestration API** | Java 17 | Dependency-free HTTP server orchestrating C++ binary via strict `ProcessBuilder` isolation, path-traversal sandboxing, atomic job outputs |
| **ML Baseline & Evaluation** | Python 3 | CICIDS2017 data preparation pipeline, Robust MAD + Isolation Forest anomaly detectors, chronological train/val/test splitting, PR-AUC reporting |
| **Analyst Dashboard** | TypeScript + HTML | Dependency-free analyst console: dataset selection, C++ job orchestration, 33-column CSV viewer, SVG temporal activity timeline, circular graph topology |
| **Containerisation** | Docker Compose | Pinned multi-stage builds (`eclipse-temurin:17`, `python:3.12-alpine`, `node:22-alpine`), loopback-bound ports, unprivileged users, health checks |

#### ✅ Completed Phases (8 of 8)

- **Phase 1** — C++17 temporal graph engine, streaming CSV ingestion, 14 unit tests
- **Phase 2** — CICIDS2017 offline preparation pipeline (Python stdlib only, 67 unit tests)
- **Phase 3** — Deterministic sliding-window feature extractor (`chrono_features`): flow direction, duration rates, previous-window deltas, new-peer ratio, fan-out growth
- **Phase 4** — Leakage-safe evaluation: chronological splits with boundary purge, Robust MAD & Isolation Forest, PR-AUC
- **Phase 5** — Java 17 REST API orchestrating C++ binary with strict sandboxing, 7 test suites
- **Phase 6** — Dependency-free TypeScript dashboard: job orchestration, SVG timeline, graph topology
- **Phase 7** — Reproducible Docker Compose demo: pinned images, loopback isolation, health checks, unprivileged containers
- **Phase 8** — Integrated offline evaluation workflow: `ProcessBuilder`-safe Python execution, confusion matrix visualisation, synthetic demo fixtures

#### 🔑 Research Themes

`temporal-graphs` · `anomaly-detection` · `network-security` · `intrusion-detection` · `graph-algorithms` · `sliding-window-analysis` · `cybersecurity-research`

<div align="center">

[![View Repository](https://img.shields.io/badge/→%20View%20ChronoGraph-181717?style=for-the-badge&logo=github)](https://github.com/Shivam-ray-06/chronograph)

</div>

---

### 🚨 2 · AEGIS AI — AI Emergency Guidance & Intelligent Surveillance

<div align="center">

[![AEGIS](https://img.shields.io/badge/AEGIS-Emergency%20AI%20Platform-DC143C?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Shivam-ray-06/aegis-ai)
![Stack](https://img.shields.io/badge/Stack-Next.js%20%7C%20FastAPI%20%7C%20PostgreSQL%20%7C%20Docker-orange?style=for-the-badge)

</div>

**AEGIS** (_Artificial Emergency Guidance & Intelligent Surveillance_) is a command-centre platform concept for AI-assisted emergency response coordination. It models the full incident lifecycle — from road accident detection through victim triage, hospital recommendation, emergency unit dispatch, and report generation.

#### Architecture
- **Frontend** — Next.js App Router dashboard with typed incident state and deterministic end-to-end simulation
- **Backend** — FastAPI orchestration layer with typed service contracts
- **Service Boundaries** — Isolated engine modules: `ai-engine` (YOLO/OpenCV/PyTorch boundary), `hospital-engine`, `maps-engine`, `dispatch-engine`
- **Database** — PostgreSQL schema with structured incident records
- **Runtime** — Full Docker Compose local stack with live camera feed support (`getUserMedia`)

> *Service boundaries are designed for real production adapters (JWT auth, GPU inference workers, event-driven transport) while keeping the demo deterministic and self-contained.*

<div align="center">

[![View Repository](https://img.shields.io/badge/→%20View%20AEGIS%20AI-181717?style=for-the-badge&logo=github)](https://github.com/Shivam-ray-06/aegis-ai)

</div>

---

### 📐 3 · GeoReasonBench — Geometry Reasoning Benchmark for Multimodal LLMs

<div align="center">

[![GeoReasonBench](https://img.shields.io/badge/GeoReasonBench-Multimodal%20Benchmark-9B59B6?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Shivam-ray-06/GeoReasonBench-v2)
![Stack](https://img.shields.io/badge/Stack-Python%20%7C%20C%2B%2B%20%7C%20PyBind11-orange?style=for-the-badge)

</div>

**GeoReasonBench** is a research-engineering framework for evaluating **geometric spatial reasoning** in multimodal language models and vision-language models. It generates fully synthetic geometry problems with symbolic ground truth and structured reasoning traces, runs model benchmarks, and classifies failure modes.

#### Key Capabilities
- **Synthetic Dataset Generation** — End-to-end pipeline: geometric primitives → diagram renderer → symbolic solver → structured problem records with symbolic reasoning traces
- **Multimodal Evaluation** — Modular adapters for LLMs and VLMs across spatial and geometry reasoning tasks
- **Failure Taxonomy** — Automated failure mode classification and Markdown report generation
- **C++ Acceleration** — Optional PyBind11 C++ kernel for heavy geometric computations (distance, angle, polygon area) on large datasets
- **Geometry-Aware Attention** — Prototype adapter for injecting primitive-level geometric features into VLM attention layers

<div align="center">

[![View Repository](https://img.shields.io/badge/→%20View%20GeoReasonBench-181717?style=for-the-badge&logo=github)](https://github.com/Shivam-ray-06/GeoReasonBench-v2)

</div>

---

### 🧠 4 · Custom RAG Engine with C++ Vector Database

<div align="center">

[![RAG Engine](https://img.shields.io/badge/RAG%20Engine-C%2B%2B%20Vector%20DB-27AE60?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Shivam-ray-06/rag-engine-custom-vector-db)
![Stack](https://img.shields.io/badge/Stack-C%2B%2B14%20%7C%20Python%20%7C%20PyTorch%20%7C%20PyBind11-orange?style=for-the-badge)

</div>

A **Retrieval-Augmented Generation** system built from scratch, bridging high-performance C++ data structures with Python LLM pipelines. The core insight: understanding the mathematics underlying modern AI vector search rather than depending on black-box libraries.

#### Engineering Highlights
- **Custom C++ Vector Database** — Memory-efficient vector store with **Exact KNN Search** and **Locality-Sensitive Hashing (LSH)** using Cosine Similarity; built in C++14 with zero external dependencies
- **PyBind11 Bridge** — Native C++ extension exposed to Python, bypassing GIL bottlenecks during vector search
- **Embedding Pipeline** — `all-MiniLM-L6-v2` sentence embeddings via `SentenceTransformers`; local LLM inference via `TinyLlama`
- **End-to-End RAG** — PDF/TXT ingestion → chunking → embedding → LSH indexing → semantic retrieval → LLM answer synthesis

<div align="center">

[![View Repository](https://img.shields.io/badge/→%20View%20RAG%20Engine-181717?style=for-the-badge&logo=github)](https://github.com/Shivam-ray-06/rag-engine-custom-vector-db)

</div>

---

### 🛡️ 5 · ADTCN — Autonomous Threat Detection & Containment Network

<div align="center">

[![ADTCN](https://img.shields.io/badge/ADTCN-Threat%20Detection%20%26%20Containment-E74C3C?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Shivam-ray-06/adtcn-threat-containment-network)
![Stack](https://img.shields.io/badge/Stack-Java%20%7C%20C%2B%2B17%20%7C%20JavaScript-orange?style=for-the-badge)

</div>

**ADTCN v2** is a full three-language rewrite of a threat detection and containment prototype: **Java** for the backend correlation engine, policy engine, evidence hash chain, and REST + WebSocket API; **C++** for endpoint agent (Linux `inotify`), network sensor, and attack simulator using raw POSIX sockets; **JavaScript** for a live SOC dashboard with deterministic attack-flow visualisation.

#### Architecture

| Component | Language | Role |
|---|---|---|
| `backend-java/` | Java (JDK stdlib only) | Correlation engine · Policy engine · Evidence hash chain · REST `:8000` · WebSocket `:8001` |
| `agent-cpp/` | C++17 | Endpoint agent with real Linux `inotify` decoy file monitoring |
| `network-cpp/` | C++17 | Network sensor: tails flow-record log, detects port scanning and abnormal connections |
| `simulator-cpp/` | C++17 | Scripted attacker — plays the PC-47 scenario end-to-end |
| `dashboard/` | JavaScript | Live SOC dashboard: threat scores, event feed, attack-flow diagram, incident timeline, alarm |

> *Built without external package managers (Maven/vcpkg/conan): every line is project logic, not framework boilerplate — ~2,000 lines of raw Java, C++, and JS.*

<div align="center">

[![View Repository](https://img.shields.io/badge/→%20View%20ADTCN-181717?style=for-the-badge&logo=github)](https://github.com/Shivam-ray-06/adtcn-threat-containment-network)

</div>

---

## 🔭 Research Interests

```
📡  Temporal Graph Intelligence         Tracking evolving network behaviour through time-ordered graph snapshots
🔐  Cybersecurity & Threat Detection    Anomaly-based intrusion detection, zero-day threat modelling, evidence chains
🧠  Multimodal AI & VLMs               Evaluating spatial and geometric reasoning in vision-language models
🤖  Machine Learning Systems           Retrieval-Augmented Generation, embeddings, local LLM inference
📊  Graph Algorithms & Data Structures  Sliding-window graphs, KNN, LSH, temporal graph features
🏗️  Scalable Software Architecture     Multi-language systems, containerisation, service isolation
```

---

## 📊 GitHub Analytics

<div align="center">

<img height="180" src="https://github-readme-stats.vercel.app/api?username=Shivam-ray-06&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58A6FF&icon_color=58A6FF&text_color=c9d1d9&include_all_commits=true&count_private=true" alt="GitHub Stats" />

<img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Shivam-ray-06&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58A6FF&text_color=c9d1d9&langs_count=8" alt="Top Languages" />

</div>

<div align="center">

<img src="https://streak-stats.demolab.com?user=Shivam-ray-06&theme=github-dark-blue&hide_border=true&background=0d1117&stroke=58A6FF&ring=58A6FF&fire=FF6B6B&currStreakLabel=58A6FF" alt="Contribution Streak" />

</div>

---

## 🤝 Connect

<div align="center">

| Platform | Link |
|---|---|
| 🔗 **LinkedIn** | [shivam-swastik-ray-2b23a1409](https://www.linkedin.com/in/shivam-swastik-ray-2b23a1409) |
| 🐙 **GitHub** | [Shivam-ray-06](https://github.com/Shivam-ray-06) |

</div>

---

<div align="center">

*B.Tech · AI & Data Science · Ajeenkya D Y Patil University, Pune · 2025–2029*

</div>
