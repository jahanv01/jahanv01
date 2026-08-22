<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,100:7dd3fc&height=220&section=header&text=Jahanvi%20Panchal&fontSize=42&fontColor=ffffff&animation=twinkling&fontAlignY=35&desc=AI%2FML%20Engineer%20%7C%20Data%20Scientist%20%7C%20Researcher&descAlignY=55&descSize=18" width="100%"/>

<a href="https://github.com/jahanv01">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=1000&color=7DD3FC&center=true&vCenter=true&width=650&lines=AI%2FML+Engineer+%7C+Data+Scientist+%7C+Researcher;Building+with+PyTorch%2C+LangChain+%26+LangGraph;RAFT%2FRAG+Fine-Tuning+%2B+NLP+%2B+Time+Series;Turning+Data+Into+Deployable+Intelligence" alt="Typing SVG" />
</a>

<br/>



</div>

<br/>

## 👋 Who I Am

<div align="center">

![Role](https://img.shields.io/badge/Role-AI%2FML%20Engineer%20%7C%20Data%20Scientist%20%7C%20Researcher-0f172a?style=for-the-badge&labelColor=7dd3fc)
![Status](https://img.shields.io/badge/Status-Researching%20RAFT%20%2F%20RAG%20Fine--Tuning-0f172a?style=for-the-badge&labelColor=7dd3fc)

</div>


<table width="100%">
<tr>
<td valign="top" width="50%">

**🚀 Launched Projects**

- 🎯 JobFitAI — Job-Match Scoring & Cover Letter Chrome Extension
- 📄 From Standard RAG to RAFT — Grounding in Financial QA
- 🤖 Cleo — AI Sales Coach
- 📦 Logimate — 🥇 STADS Datathon 2025
- 🧠 Emotion Regulation Classification (Active Learning)

</td>
<td valign="top" width="50%">

**📜 Certifications**

- ☁️ AWS for Data Science — *SimpliLearn*
- 🤝 Introduction to Agent Skills — *Anthropic*

**🎯 Open To**

`Software Engineering` `Data Science` `ML/AI Engineering`

</td>
</tr>
</table>

<br/>

## 🚀 Featured Projects

### 🎯 JobFitAI — Job-Match Scoring & Cover Letter Chrome Extension

Score any job posting against your profile and generate a tailored cover letter, in one click, from your browser. A Chrome extension reads the job description directly off whatever page you're on — LinkedIn, Indeed, or a company's own careers page — via an on-demand content script gated by a keyword heuristic so it only ever scrapes actual job postings, never unrelated pages. A FastAPI backend scores it against a stored profile using the Gemini API, returning a category-level match breakdown (education, programming, AI/ML, experience), named strengths and gaps, an apply/skip recommendation, and a tailored cover letter — all validated against an explicit response schema before anything is persisted. Fully containerized, CI-tested (lint + tests on every push via GitHub Actions), and deployed to Render.


| Layer | Technology |
|---|---|
| Backend | Python, FastAPI, SQLAlchemy, Pydantic, SQLite |
| AI | Google Gemini API, structured JSON output validation |
| Browser Extension | Vanilla JavaScript, Chrome Manifest V3, on-demand content script injection |
| Infrastructure | Docker, Render, GitHub Actions (CI) |

**🔗 Code:** [JobFitAI](https://github.com/jahanv01/JobFitAI)

<br/>

### 📄 From Standard RAG to RAFT: Grounding in Financial QA


Implemented RAFT-style fine-tuning on LLaMA 3.2-3B, LLaMA 3.1-8B, and Qwen3-4B using LoRA adapters, increasing answer faithfulness by over 20 percentage points and reducing hallucinations on the FINDER financial QA benchmark. Built a full experimental pipeline comparing two retrieval strategies (BM25, E5-Mistral) across three model architectures, with systematic ablations over retrievers, generators, and LoRA configurations, evaluated using the RAGAS framework. Demonstrated zero-shot cross-domain transfer to financial QA by training exclusively on Gorilla APIBench with no domain-specific financial data — showing the grounding behavior generalizes across domains.


| Layer | Technology |
|---|---|
| Models | LLaMA 3.2-3B, LLaMA 3.1-8B, Qwen3-4B |
| Fine-Tuning | RAFT-style training, LoRA/PEFT |
| Retrieval | BM25, E5-Mistral |
| Evaluation | RAGAS (faithfulness, correctness, context recall) |

**🔗 Code:** [Standard-RAG-to-RAFT-in-Finace-QnA](https://github.com/jahanv01/Standard-RAG-to-RAFT-in-Finace-QnA)

<br/>

### 🤖 Cleo - AI Sales Coach

*Qhack-26 Hackathon*

A full-stack AI-powered web application built on a modular multi-agent architecture to support sales representatives with automated customer preparation. Integrates external REST APIs for solar yield estimation, live energy pricing, and subsidy calculations, plus a document retrieval pipeline with voice interaction for context-aware product recommendations — all through scalable backend services.


| Layer | Technology |
|---|---|
| Architecture | Multi-agent orchestration |
| Backend | FastAPI, REST API integrations |
| Retrieval | Document retrieval pipeline |
| Interaction | Voice interaction capabilities |

**🔗 Code:** [Qhack-2026](https://github.com/jahanv01/Cleo-AI)

<br/>

### 📦 Logimate

*STADS Datathon 2025 — 🥇 1st Place*

Identified that delivery service time variance at Flaschenpost SE was **driver-specific rather than order-specific**, and designed a personalized per-driver OLS regression framework across **1.5M+ deliveries** that explained **82% of variance (R²=0.82)** in service time — winning 1st place among 7 competing teams. Extended into a scalable prediction framework supporting continuous model updates for new drivers using reinforcement learning concepts, with real-time caching via ElastiCache for production-style inference.

| Layer | Technology |
|---|---|
| Modeling | Personalized per-driver OLS regression |
| Scale | 1.5M+ delivery records |
| Extensions | Reinforcement learning concepts, ElastiCache |
| Result | R² = 0.82, 1st place / 7 teams |

> 🔒 Repo is private — details above summarized from project documentation.

<br/>

### 🧠 Emotion Regulation Classification Using Active Learning


Classifies emotion regulation strategies — Situation Selection, Situation Modification, Attentional Deployment, Cognitive Change, and Response Modulation — from grief-support app journal entries with limited labeled data (300 labeled across 35k+ unlabeled). Benchmarks traditional ML (Naive Bayes, SVM, Random Forest) against transformer models (BERT, EmoBERTa), and applies active learning with uncertainty sampling to cut manual labeling effort by 30% while achieving macro F1 of 0.61 (Journal) and 0.80 (Evening dataset), outperforming all baselines.


| Layer | Technology |
|---|---|
| Language | Python |
| NLP Models | BERT, EmoBERTa, Sentence-BERT |
| ML Frameworks | PyTorch, TensorFlow, Scikit-learn |
| Technique | Active Learning, Data Augmentation |

**🔗 Code:** [Masters-Team-Project-Emotion-Regulation-Classification-Using-Active-Learning](https://github.com/jahanv01/Emotion-Regulation-Classification-Using-Active-Learning)

<br/>

## 🛠️ Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-7dd3fc?style=for-the-badge&logo=python&logoColor=0f172a)
![SQL](https://img.shields.io/badge/SQL-7dd3fc?style=for-the-badge&logo=postgresql&logoColor=0f172a)
![R](https://img.shields.io/badge/R-7dd3fc?style=for-the-badge&logo=r&logoColor=0f172a)
![JavaScript](https://img.shields.io/badge/JavaScript-7dd3fc?style=for-the-badge&logo=javascript&logoColor=0f172a)

**Backend & Frontend**

![FastAPI](https://img.shields.io/badge/FastAPI-7dd3fc?style=for-the-badge&logo=fastapi&logoColor=0f172a)
![REST APIs](https://img.shields.io/badge/REST_APIs-7dd3fc?style=for-the-badge&logo=swagger&logoColor=0f172a)
![React](https://img.shields.io/badge/React-7dd3fc?style=for-the-badge&logo=react&logoColor=0f172a)
![HTML5](https://img.shields.io/badge/HTML5-7dd3fc?style=for-the-badge&logo=html5&logoColor=0f172a)
![CSS3](https://img.shields.io/badge/CSS3-7dd3fc?style=for-the-badge&logo=css3&logoColor=0f172a)

**ML Frameworks**

![PyTorch](https://img.shields.io/badge/PyTorch-7dd3fc?style=for-the-badge&logo=pytorch&logoColor=0f172a)
![TensorFlow](https://img.shields.io/badge/TensorFlow-7dd3fc?style=for-the-badge&logo=tensorflow&logoColor=0f172a)
![Scikit--learn](https://img.shields.io/badge/Scikit--learn-7dd3fc?style=for-the-badge&logo=scikitlearn&logoColor=0f172a)
![XGBoost](https://img.shields.io/badge/XGBoost-7dd3fc?style=for-the-badge)
![Random Forest](https://img.shields.io/badge/Random_Forest-7dd3fc?style=for-the-badge)
![ARIMA](https://img.shields.io/badge/ARIMA-7dd3fc?style=for-the-badge)
![AdaBoost](https://img.shields.io/badge/AdaBoost-7dd3fc?style=for-the-badge)

**LLMs & Generative AI**

![Hugging Face](https://img.shields.io/badge/Hugging_Face-7dd3fc?style=for-the-badge&logo=huggingface&logoColor=0f172a)
![LangChain](https://img.shields.io/badge/LangChain-7dd3fc?style=for-the-badge)
![LangGraph](https://img.shields.io/badge/LangGraph-7dd3fc?style=for-the-badge)
![LoRA/PEFT](https://img.shields.io/badge/LoRA%2FPEFT-7dd3fc?style=for-the-badge)
![RAGAS](https://img.shields.io/badge/RAGAS-7dd3fc?style=for-the-badge)
![Agent Orchestration](https://img.shields.io/badge/Agent_Orchestration-7dd3fc?style=for-the-badge)
![Prompt Engineering](https://img.shields.io/badge/Prompt_Engineering-7dd3fc?style=for-the-badge)

**NLP & Text Processing**

![BERT](https://img.shields.io/badge/BERT-7dd3fc?style=for-the-badge)
![EmoBERTa](https://img.shields.io/badge/EmoBERTa-7dd3fc?style=for-the-badge)
![Sentence--BERT](https://img.shields.io/badge/Sentence--BERT-7dd3fc?style=for-the-badge)
![FastText](https://img.shields.io/badge/FastText-7dd3fc?style=for-the-badge)
![E5--Mistral](https://img.shields.io/badge/E5--Mistral-7dd3fc?style=for-the-badge)
![NLTK](https://img.shields.io/badge/NLTK-7dd3fc?style=for-the-badge)
![VADER](https://img.shields.io/badge/VADER-7dd3fc?style=for-the-badge)
![BM25](https://img.shields.io/badge/BM25-7dd3fc?style=for-the-badge)
![TF--IDF](https://img.shields.io/badge/TF--IDF-7dd3fc?style=for-the-badge)

**Data Engineering**

![Pandas](https://img.shields.io/badge/Pandas-7dd3fc?style=for-the-badge&logo=pandas&logoColor=0f172a)
![NumPy](https://img.shields.io/badge/NumPy-7dd3fc?style=for-the-badge&logo=numpy&logoColor=0f172a)
![SciPy](https://img.shields.io/badge/SciPy-7dd3fc?style=for-the-badge&logo=scipy&logoColor=0f172a)
![DuckDB](https://img.shields.io/badge/DuckDB-7dd3fc?style=for-the-badge&logo=duckdb&logoColor=0f172a)
![Parquet](https://img.shields.io/badge/Parquet-7dd3fc?style=for-the-badge&logo=apacheparquet&logoColor=0f172a)
![ETL Pipelines](https://img.shields.io/badge/ETL_Pipelines-7dd3fc?style=for-the-badge)

**Cloud & DevOps**

![AWS](https://img.shields.io/badge/AWS-7dd3fc?style=for-the-badge&logo=amazonaws&logoColor=0f172a)
![Docker](https://img.shields.io/badge/Docker-7dd3fc?style=for-the-badge&logo=docker&logoColor=0f172a)
![Git](https://img.shields.io/badge/Git-7dd3fc?style=for-the-badge&logo=git&logoColor=0f172a)
![Linux](https://img.shields.io/badge/Linux-7dd3fc?style=for-the-badge&logo=linux&logoColor=0f172a)
![Vercel](https://img.shields.io/badge/Vercel-7dd3fc?style=for-the-badge&logo=vercel&logoColor=0f172a)
![Render](https://img.shields.io/badge/Render-7dd3fc?style=for-the-badge&logo=render&logoColor=0f172a)

**Data Visualization**

![Streamlit](https://img.shields.io/badge/Streamlit-7dd3fc?style=for-the-badge&logo=streamlit&logoColor=0f172a)
![Plotly](https://img.shields.io/badge/Plotly-7dd3fc?style=for-the-badge&logo=plotly&logoColor=0f172a)
![Matplotlib](https://img.shields.io/badge/Matplotlib-7dd3fc?style=for-the-badge)
![Power BI](https://img.shields.io/badge/Power_BI-7dd3fc?style=for-the-badge&logo=powerbi&logoColor=0f172a)
![Tableau](https://img.shields.io/badge/Tableau-7dd3fc?style=for-the-badge&logo=tableau&logoColor=0f172a)

<br/>

## 📊 GitHub Streak

<div align="center">
<img src="https://streak-stats.demolab.com/?user=jahanv01&theme=tokyonight" alt="GitHub Streak" />
</div>

<br/>

## 📈 Contribution Activity

<div align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=jahanv01&theme=nord&hide_border=true&color=7dd3fc&line=7dd3fc&point=ffffff" alt="Contribution Activity Graph"/>
</div>

<br/>

## 🤝 Connect With Me

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jahanvikpanchal/)
[![Email](https://img.shields.io/badge/Email-7DD3FC?style=for-the-badge&logo=gmail&logoColor=black)](mailto:jahanvikpanchal01@gmail.com)

</div>

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:7dd3fc,100:0f172a&height=150&section=footer" width="100%"/>
