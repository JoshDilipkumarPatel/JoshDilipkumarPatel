<div align="center">

```
        ██╗ ██████╗ ███████╗██╗  ██╗
        ██║██╔═══██╗██╔════╝██║  ██║
        ██║██║   ██║███████╗███████║
        ██║██║   ██║╚════██║██╔══██║
    ██████║╚██████╔╝███████║██║  ██║
    ╚═════╝ ╚═════╝ ╚══════╝╚═╝  ╚═╝
```

### `> building intelligent systems, one model at a time.`

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=16&pause=1000&color=00F5A0&center=true&vCenter=true&width=600&lines=ML+Engineer+%7C+AI+Builder+%7C+TechMAN;LLMs+%2B+Diffusion+Models+%2B+RAG+Systems;Blockchain+%2B+CI%2FCD+%2B+Data+Pipelines;Turning+data+into+decisions...;Open+to+interesting+projects+%F0%9F%9A%80)](https://git.io/typing-svg)

</div>

---

## `whoami`

```python
josh = {
    "name"        : "Josh Dilipkumar Patel",
    "role"        : "ML Engineer & AI Builder",
    "focus"       : ["LLMs", "Generative AI", "Deep Learning", "Data Science"],
    "also_builds" : ["Blockchain Apps", "CI/CD Tools", "ETL Pipelines", "Web Apps"],
    "cloud"       : ["AWS", "GCP", "Azure"],
    "status"      : "🟢 Open to interesting projects",
    "motto"       : "If it can be learned, it can be automated.",
}
```

I build AI systems that **think**, **remember**, and **generate** — from fully offline RAG pipelines and diffusion-based video upscalers to decentralized blockchain apps and visual CI/CD designers. I love working at the intersection of research and real-world impact.

---

## `skills --list`

<div align="center">

**Languages & Core**

![Python](https://img.shields.io/badge/Python-0d1117?style=for-the-badge&logo=python&logoColor=00F5A0)
![SQL](https://img.shields.io/badge/SQL-0d1117?style=for-the-badge&logo=postgresql&logoColor=00F5A0)
![Solidity](https://img.shields.io/badge/Solidity-0d1117?style=for-the-badge&logo=solidity&logoColor=00F5A0)

**AI / ML Stack**

![PyTorch](https://img.shields.io/badge/PyTorch-0d1117?style=for-the-badge&logo=pytorch&logoColor=00F5A0)
![HuggingFace](https://img.shields.io/badge/HuggingFace-0d1117?style=for-the-badge&logo=huggingface&logoColor=00F5A0)
![LangChain](https://img.shields.io/badge/LangChain-0d1117?style=for-the-badge&logo=chainlink&logoColor=00F5A0)
![scikit-learn](https://img.shields.io/badge/scikit--learn-0d1117?style=for-the-badge&logo=scikit-learn&logoColor=00F5A0)
![LightGBM](https://img.shields.io/badge/LightGBM-0d1117?style=for-the-badge&logo=leaf&logoColor=00F5A0)
![OpenCV](https://img.shields.io/badge/OpenCV-0d1117?style=for-the-badge&logo=opencv&logoColor=00F5A0)
![FAISS](https://img.shields.io/badge/FAISS-0d1117?style=for-the-badge&logo=meta&logoColor=00F5A0)
![Streamlit](https://img.shields.io/badge/Streamlit-0d1117?style=for-the-badge&logo=streamlit&logoColor=00F5A0)
![ChromaDB](https://img.shields.io/badge/ChromaDB-0d1117?style=for-the-badge&logo=databricks&logoColor=00F5A0)

**Web & Backend**

![React](https://img.shields.io/badge/React-0d1117?style=for-the-badge&logo=react&logoColor=00F5A0)
![FastAPI](https://img.shields.io/badge/FastAPI-0d1117?style=for-the-badge&logo=fastapi&logoColor=00F5A0)
![Django](https://img.shields.io/badge/Django-0d1117?style=for-the-badge&logo=django&logoColor=00F5A0)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0d1117?style=for-the-badge&logo=postgresql&logoColor=00F5A0)
![Docker](https://img.shields.io/badge/Docker-0d1117?style=for-the-badge&logo=docker&logoColor=00F5A0)

**Cloud & Blockchain**

![AWS](https://img.shields.io/badge/AWS-0d1117?style=for-the-badge&logo=amazon-aws&logoColor=00F5A0)
![GCP](https://img.shields.io/badge/GCP-0d1117?style=for-the-badge&logo=google-cloud&logoColor=00F5A0)
![Azure](https://img.shields.io/badge/Azure-0d1117?style=for-the-badge&logo=microsoft-azure&logoColor=00F5A0)
![Ethereum](https://img.shields.io/badge/Ethereum-0d1117?style=for-the-badge&logo=ethereum&logoColor=00F5A0)
![Web3](https://img.shields.io/badge/Web3-0d1117?style=for-the-badge&logo=web3dotjs&logoColor=00F5A0)

</div>

---

## `research --active`

> 🔬 **Quantization Impact on Hallucination in RAG Systems** *(Nov 2025 — Present)*
---
Investigated the causal impact of 4-bit quantization on hallucination rates in retrieval-augmented language models
by designing a controlled RAG evaluation framework with calibrated ensemble-based reliability scoring.

```
Hypothesis: Does INT4 quantization degrade contextual faithfulness in RAG models
            under low-resource deployment constraints?
```

- Designed a **controlled RAG pipeline** (FAISS retrieval · fixed chunking · identical decoding) to isolate quantization precision as the sole independent variable
- Built a **calibrated ensemble hallucination detector** combining DeBERTa NLI + FlowJudge semantic evaluation + lexical overlap — achieving reliable agreement with human-labeled data
- Ran paired experiments on **1,000 RAGTruth queries (2,000 responses)** · applied **McNemar's statistical test** to compare FP16 vs INT4 Llama-3 hallucination rates
- Engineered a **time-multiplexed GPU execution strategy** — enabling full generation + evaluation within **16GB VRAM**, keeping experiments reproducible and low-cost

`Python` `HuggingFace` `FAISS` `bitsandbytes` `DeBERTa` `Llama-3`

---

## `ls ./projects`

### 🤖 AI / Machine Learning

| Project | Highlights | Stack |
|---|---|---|
| 🎬 [**Video SD→HD Upscaler**](https://github.com/JoshDilipkumarPatel/Video-Conversion-from-SD-to-HD-using-Diffusion-Model) | Diffusion-based super-resolution · **2× speedup** over OpenCV baseline · Sliding-window GPU batching · temporal consistency refinement | `PyTorch` `Diffusion Models` `OpenCV` |
| 🧠 [**Local RAG System**](https://github.com/JoshDilipkumarPatel/Local-Retrieval-Augmented-Text-Generation) | Fully offline RAG · 10,000+ line corpus · FAISS + TinyLlama-1.1B · similarity threshold hallucination control | `FAISS` `HuggingFace` `PyTorch` |
| 📖 [**Story Recall Bot**](https://github.com/JoshDilipkumarPatel/Story-Recall-Bot-Using-Narrative-Memory-System) | Episodic memory w/ decay · **79% Recall@5** · BART summarization ROUGE-1: 0.512 · 4.2/5 user coherence score | `LangChain` `ChromaDB` `Streamlit` |
| 📈 [**Time-Series Sales Forecasting**](https://github.com/JoshDilipkumarPatel/Time-Series-Sales-Forecasting) | LightGBM · RMSE 5.47 · lag features, rolling stats & seasonality · time-aware cross-validation | `LightGBM` `Pandas` `Python` |

### 🔗 Blockchain & Web3

| Project | Highlights | Stack |
|---|---|---|
| 💬 **Blockchain Messaging App** | Decentralized P2P messaging · Keccak-256 serverless peer discovery · **25% gas reduction** · deployed on Sepolia testnet | `Solidity` `Ethereum` `Web3` |

### ⚙️ DevOps & Data Engineering

| Project | Highlights | Stack |
|---|---|---|
| 🔄 **Declarative CI/CD Pipeline Designer** | Visual GitHub Actions generator · React Flow drag-and-drop · 10+ node types · cyclic dependency detection · Docker sandbox | `React` `FastAPI` `Docker` |
| 🗄️ **ETL Pipeline for Retail Data** | CSV + REST API ingestion · normalized PostgreSQL schema · batch processing with logging & anomaly detection | `Pandas` `PostgreSQL` `Python` |
| 🏢 **Meeting Room Management App** | Concurrency-safe scheduling · **40% lower query latency** · transaction isolation · real-time multi-user frontend | `Django` `PostgreSQL` `REST APIs` |

---

## `git stats`

<div align="center">

![Josh's GitHub Stats](https://github-readme-stats.vercel.app/api?username=JoshDilipkumarPatel&show_icons=true&theme=chartreuse-dark&bg_color=0d1117&title_color=00F5A0&icon_color=00F5A0&text_color=ffffff&border_color=00F5A0)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=JoshDilipkumarPatel&layout=compact&theme=chartreuse-dark&bg_color=0d1117&title_color=00F5A0&text_color=ffffff&border_color=00F5A0)

![GitHub Streak](https://streak-stats.demolab.com?user=JoshDilipkumarPatel&theme=chartreuse-dark&background=0d1117&border=00F5A0&ring=00F5A0&fire=00F5A0&currStreakLabel=00F5A0)

</div>

---

## `ping me`

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0d1117?style=for-the-badge&logo=linkedin&logoColor=00F5A0)](https://www.linkedin.com/in/josh-d-patel/)
[![GitHub](https://img.shields.io/badge/GitHub-0d1117?style=for-the-badge&logo=github&logoColor=00F5A0)](https://github.com/JoshDilipkumarPatel)

</div>

<div align="center">

```
> always learning. always building. always shipping.
```

![Visitor Count](https://komarev.com/ghpvc/?username=JoshDilipkumarPatel&color=00F5A0&style=flat-square&label=profile+views)

</div>
