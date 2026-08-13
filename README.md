# 👋 Hi, I'm Mohd Nauman

**Data Research Engineer @ BharatGen** — I build the data that makes LLMs work, and the platform behind it.

I build **high-throughput, cost-efficient data platforms for LLMs** — from petabyte-scale ingestion to governed metadata, evaluation harnesses, and agentic delivery. Currently leading data infrastructure for **India's Sovereign AI** at BharatGen.

---

## 📄 Publications

- **Chitrakshara: A Large Multilingual Multimodal Dataset for Indian Languages** — CVPR 2025 (VLMs4All Workshop). 193M images, 30B tokens. [HuggingFace](https://huggingface.co/bharatgenai/chitrakshara)
- **AyurParam: A State-of-the-Art Bilingual Language Model for Ayurveda** — [ArXiv 2511.02374](https://arxiv.org/abs/2511.02374) · [HuggingFace](https://huggingface.co/bharatgenai/AyurParam)
- **BhashaBench V1: A Comprehensive Benchmark for the Quadrant of Indic Domains** — [ArXiv 2510.25409](https://arxiv.org/abs/2510.25409)

---

## 🚀 Snapshot

- Delivered a **1T+ token pre-training corpus** for BharatGen's foundation models — Common Crawl WARC, 11M books (Internet Archive), 30M+ open-access papers, 7M GitHub repos.
- Co-authored **3 papers**: Chitrakshara (CVPR 2025), AyurParam, BhashaBench V1.
- **~10M Q&A synthetic-data pipeline** that shipped AyurParam, the highest-SOTA Ayurveda LLM.
- **BhashaBench** — Indic LLM evaluation benchmark, adopted as BharatGen's standard eval framework.
- Cut crawling infrastructure **87.5%** (40 → 5 machines) with zero throughput loss.
- Rewrote the tokenizer in **Rust** for a 3× SLURM-native training speedup.

---

## 🔬 Building

### 🎬 [Motionify](motionify.app) — AI Video Editor for Talking-Head Shorts
Desktop app (**Electron + React 19 + TypeScript**) that turns raw talking-head footage into high-retention edutainment shorts. Uses **Gemini 2.5** for multimodal transcription and GSAP animation generation, with an **FFmpeg** render pipeline. Solo build, end-to-end.

### 🌾 Krishi Bot — Agentic AI Advisor for Agriculture + Government Services *(BharatGen)*
BharatGen's live AI product for farmers. **RAG-optimized agent with tool use**: location-aware search, government policy lookup, and form-filling workflows. Curated the knowledge base and shaped the agent's retrieval and tool layer.

### 📚 [dataengineer_prep](https://github.com/Noman654/dataengineer_prep) — 73★ Open-Source DE Learning Repo
Data engineering interview prep — PySpark notebooks, theory docs, quizzes, and company-specific patterns. Built around **Zephyr Coffee Co.**, a fictional 200-store chain with messy data. Community-adopted.

### 🌊 Bharat Data Sagar — On-Prem PB-Scale Data Platform *(BharatGen, internal)*
**JuiceFS + DuckDB + DataHub** lineage across **1M+ datasets**. Reproducible pipelines for LLM training and evaluation. Chosen over S3/Athena/Glue for cost efficiency at petabyte scale.

### 🧠 [second-brain-rpg](https://github.com/Noman654/second-brain-rpg) — PARA-Based Productivity System
Applying Tiago Forte's PARA method as a gamified personal knowledge system. Side project, TypeScript.

---

## 🧭 What I Do

- **Pretraining Data Engineering** — corpus curation at PB scale, dedup, contamination filtering, quality gating (Common Crawl WARC, Archive.org, ArXiv, GitHub).
- **Synthetic Data, Evaluation & Harnesses** — context-grounded Q&A generation, benchmark design, LLM-judge pipelines, and evaluation harnesses for standardized model scoring.
- **Agent Building** — RAG-optimized agents with tool use (location search, policy lookup, form filling); production advisory agents for real-world advisory workflows. Agent Harness for complex task. 
- **Model Serving & Inference** — vLLM + Ray multi-node (1 → 50 nodes), ONNX optimization, Rust tokenizer.
- **Data Platforms & Governance** — on-prem lakehouse (JuiceFS + DuckDB + DataHub), Great Expectations, dbt tests, custom Indic-script validators.

---

## 🧰 Tech Stack

- **Languages:** Python (PyTorch, PySpark, Pandas), Rust, SQL, Bash, JavaScript
- **Data / Compute:** Spark, Kafka, Debezium (CDC), Airflow, DataHub, DuckDB, Trino/Presto, Scrapy, JuiceFS
- **AI / ML:** vLLM + Ray, SGLang, Essential AI, ONNX, Surya OCR, Vertex AI, Great Expectations
- **Cloud / Infra:** AWS (S3, EMR, Glue, Redshift, EC2), Azure (Blob, Functions, Databricks, SQL), Docker, SLURM, GitHub Actions

---

## 🎤 Teaching & Community

- **AI / Data Instructor @ upGrad** — applied data engineering and LLMs.
- **Head Organizer, Kafka Mumbai Community** — meetups, 10+ talks, technical discussions.
- **Maintainer, [dataengineer_prep](https://github.com/Noman654/dataengineer_prep)** — 73★ open-source DE learning repo.

---

## 🏆 Recognition

- **Harvard CS50** — score 9.9
- **2nd Rank in Diploma** — Rajokari Institute of Technology
- **Extension Mania (IIT Madras)** — Winner
- **AWS Cloud Practitioner**, **Azure Data Fundamentals**, **SQL (Intermediate)** certified

📍 Mumbai, India
🎓 IIT Madras Online — Foundation Certificate, Programming & Data Science (2022–2023)
🎓 Rajokari Institute of Technology — Diploma in Computer Science (2018–2021)

---

## 🤝 Let's Connect
- 💼 [LinkedIn](https://www.linkedin.com/in/nauman-data-llm/)
