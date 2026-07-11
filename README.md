<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,100:7dd3fc&height=220&section=header&text=Jahanvi%20Panchal&fontSize=42&fontColor=ffffff&animation=twinkling&fontAlignY=35&desc=Software%20Engineer%20%7C%20ML%2FAI%20Engineer&descAlignY=55&descSize=18" width="100%"/>

<a href="https://github.com/jahanv01">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=1000&color=7DD3FC&center=true&vCenter=true&width=650&lines=Software+Engineer+%7C+ML%2FAI+Engineer;Building+with+PyTorch%2C+LangChain+%26+LangGraph;RAFT%2FRAG+Fine-Tuning+%2B+NLP+%2B+Time+Series;Turning+Data+Into+Deployable+Intelligence" alt="Typing SVG" />
</a>

<br/>

<img src="https://komarev.com/ghpvc/?username=jahanv01&label=Profile%20Views&color=7dd3fc&style=flat-square" alt="Profile views"/>
<img src="https://img.shields.io/github/followers/jahanv01?label=Followers&style=flat-square&color=7dd3fc" alt="Followers"/>

</div>

<br/>

## 👋 Who I Am

```typescript
const jahanvi = {
  title: "Software Engineer | ML/AI Engineer",
  stack: {
    languages: ["Python", "SQL", "R", "JavaScript"],
    backend: ["FastAPI", "REST APIs"],
    frontend: ["React", "JavaScript", "HTML", "CSS"],
    mlFrameworks: ["PyTorch", "TensorFlow", "Scikit-learn", "XGBoost", "Random Forest", "ARIMA", "AdaBoost"],
    llmAndGenAI: ["Hugging Face Transformers", "LangChain", "LangGraph", "LoRA/PEFT", "RAGAS", "Agent Orchestration", "Prompt Engineering"],
    nlp: ["BERT", "EmoBERTa", "Sentence-BERT", "FastText", "E5-Mistral", "NLTK", "VADER", "BM25", "TF-IDF"],
    dataEngineering: ["Pandas", "NumPy", "SciPy", "DuckDB", "Parquet", "ETL Pipelines"],
    cloudAndDevOps: ["AWS", "Docker", "Git", "Linux", "Vercel", "Render"],
    dataViz: ["Streamlit", "Plotly", "Matplotlib", "Power BI", "Tableau"],
  },
  launchedProjects: [
    "From Standard RAG to RAFT: A Cross-Domain Study on Grounding in Financial QA",
    "Cleo - AI Sales Coach",
    "Logimate (STADS Datathon 2025 — 1st place)",
    "Emotion Regulation Classification Using Active Learning",
  ],
  certifications: [
    "AWS for Data Science - SimpliLearn",
    "Introduction to Agent Skills - Anthropic",
  ],
  status: "Researching RAFT-style fine-tuning for financial RAG (LLaMA, Qwen3, LoRA) — Master's thesis at University of Mannheim",
  openTo: ["Software Engineering roles", "Data Science roles", "ML/AI Engineering roles"],
};
```

<br/>

## 🚀 Featured Projects

### 📄 From Standard RAG to RAFT: Grounding in Financial QA


Implemented RAFT-style fine-tuning on LLaMA 3.2-3B, LLaMA 3.1-8B, and Qwen3-4B using LoRA adapters, increasing answer faithfulness by over 20 percentage points and reducing hallucinations on the FINDER financial QA benchmark. Built a full experimental pipeline comparing two retrieval strategies (BM25, E5-Mistral) across three model architectures, with systematic ablations over retrievers, generators, and LoRA configurations, evaluated using the RAGAS framework. Demonstrated zero-shot cross-domain transfer to financial QA by training exclusively on Gorilla APIBench with no domain-specific financial data — showing the grounding behavior generalizes across domains.

<div align="center">
<a href="https://github.com/jahanv01/Standard-RAG-to-RAFT-in-Finace-QnA">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=jahanv01&repo=Standard-RAG-to-RAFT-in-Finace-QnA&theme=nord&border_color=7dd3fc&title_color=7dd3fc&text_color=c9d1d9" alt="From Standard RAG to RAFT"/>
</a>
</div>

| Layer | Technology |
|---|---|
| Models | LLaMA 3.2-3B, LLaMA 3.1-8B, Qwen3-4B |
| Fine-Tuning | RAFT-style training, LoRA/PEFT |
| Retrieval | BM25, E5-Mistral |
| Evaluation | RAGAS (faithfulness, correctness, context recall) |

**🔗 Code:** [Standard-RAG-to-RAFT-in-Finace-QnA](https://github.com/jahanv01/Standard-RAG-to-RAFT-in-Finace-QnA)

<br/>

### 🤖 Cleo - AI Sales Coach

*Qhack-26 Hackathon 

A full-stack AI-powered web application built on a modular multi-agent architecture to support sales representatives with automated customer preparation. Integrates external REST APIs for solar yield estimation, live energy pricing, and subsidy calculations, plus a document retrieval pipeline with voice interaction for context-aware product recommendations — all through scalable backend services.

<div align="center">
<a href="https://github.com/jahanv01/Qhack-2026">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=jahanv01&repo=Qhack-2026&theme=nord&border_color=7dd3fc&title_color=7dd3fc&text_color=c9d1d9" alt="Cleo - AI Sales Coach"/>
</a>
</div>

| Layer | Technology |
|---|---|
| Architecture | Multi-agent orchestration |
| Backend | FastAPI, REST API integrations |
| Retrieval | Document retrieval pipeline |
| Interaction | Voice interaction capabilities |

**🔗 Code:** [Qhack-2026](https://github.com/jahanv01/Qhack-2026)

<br/>

### 📦 Logimate

*STADS Datathon 2025 — 🥇 1st Place 

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

<div align="center">
<a href="https://github.com/jahanv01/Masters-Team-Project-Emotion-Regulation-Classification-Using-Active-Learning">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=jahanv01&repo=Masters-Team-Project-Emotion-Regulation-Classification-Using-Active-Learning&theme=nord&border_color=7dd3fc&title_color=7dd3fc&text_color=c9d1d9" alt="Emotion Regulation Classification Using Active Learning"/>
</a>
</div>

| Layer | Technology |
|---|---|
| Language | Python |
| NLP Models | BERT, EmoBERTa, Sentence-BERT |
| ML Frameworks | PyTorch, TensorFlow, Scikit-learn |
| Technique | Active Learning, Data Augmentation |

**🔗 Code:** [Masters-Team-Project-Emotion-Regulation-Classification-Using-Active-Learning](https://github.com/jahanv01/Masters-Team-Project-Emotion-Regulation-Classification-Using-Active-Learning)

<br/>

## 🛠️ Tech Stack

**Languages**

<img src="https://skillicons.dev/icons?i=python,js,r" />

**Frontend**

<img src="https://skillicons.dev/icons?i=react,js,html,css" />

**Backend / Infra**

<img src="https://skillicons.dev/icons?i=fastapi,docker,linux,git" />

**Cloud**

<img src="https://skillicons.dev/icons?i=aws,vercel,render" />

**AI / ML / DB**

<img src="https://skillicons.dev/icons?i=pytorch,tensorflow,sklearn,huggingface" />

<br/>

## 📊 GitHub Stats

<div align="center">
<img src="https://github-readme-stats.vercel.app/api?username=jahanv01&show_icons=true&theme=nord&border_color=7dd3fc&title_color=7dd3fc&icon_color=7dd3fc&text_color=c9d1d9" alt="Jahanvi's GitHub Stats" height="180"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=jahanv01&layout=compact&theme=nord&border_color=7dd3fc&title_color=7dd3fc&text_color=c9d1d9" alt="Top Languages" height="180"/>
</div>

<div align="center">
<img src="https://streak-stats.demolab.com?user=jahanv01&theme=nord&border=7dd3fc&ring=7dd3fc&fire=7dd3fc&currStreakLabel=7dd3fc" alt="GitHub Streak Stats"/>
</div>

<br/>

## 🏆 Trophies

<div align="center">
<img src="https://github-profile-trophy.vercel.app/?username=jahanv01&theme=nord&no-frame=true&no-bg=true&row=1&column=6" alt="GitHub Trophies"/>
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
