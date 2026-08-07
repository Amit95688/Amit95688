<h1 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=26&pause=1000&color=6C63FF&center=true&vCenter=true&width=650&lines=Hi%2C+I'm+Amit+Dubey;AI+%2F+ML+Engineer+%7C+Data+Science%2C+IIT+Madras;Building+production-grade+ML+%26+LLM+systems." alt="Typing SVG" />
</h1>

<p align="center">
  <a href="https://www.linkedin.com/in/amit-dubey-45292629a">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://github.com/Amit95688">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <a href="https://www.kaggle.com/amit393">
    <img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white" />
  </a>
  <a href="https://huggingface.co/kingwar1">
    <img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" />
  </a>
  <a href="https://leetcode.com/u/kingwar300705">
    <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=white" />
  </a>
  <a href="https://drive.google.com/file/d/1IWFPUumR2l8n-jfQbjREQbshcSTel3wc/view?usp=sharing">
    <img src="https://img.shields.io/badge/Resume-4285F4?style=for-the-badge&logo=googledrive&logoColor=white" />
  </a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Amit95688&color=6C63FF&style=flat-square&label=Profile+Views" />
</p>

---

## About Me

I'm a Data Science & AI/ML student at **IIT Madras**, building toward ML/LLM Engineer roles. I focus on shipping **end-to-end AI systems** — data pipeline through deployment — rather than stopping at a notebook metric.

- 🔭 Currently building production RAG pipelines, multi-tool AI agents, and MLOps systems
- 🧠 Compete actively on **Kaggle** (top-8% finishes) across tabular ML, LLM fine-tuning, and NLP
- 🛠️ Care about reliability, evaluation, and cost — not just leaderboard scores
- 📈 209+ LeetCode problems solved, 41-day max streak, 1,430 contest rating
- 📫 Open to internships, collaborations, and interesting ML/LLM problems

---

## Tech Stack

**Languages & Tools**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

**ML & LLM**
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-006ACC?style=flat-square)
![LightGBM](https://img.shields.io/badge/LightGBM-9ACD32?style=flat-square)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)

**AI Agents & MLOps**
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)

---

## Featured Projects

### 🔁 [SentinelRAG — Production Self-Healing RAG Pipeline](https://github.com/Amit95688/self-healing-rag)
11-node LangGraph pipeline combining Self-RAG and CRAG-style correction, hybrid BM25 + dense retrieval, and cross-encoder reranking.
- Cut per-query LLM calls from 10+ to 4–7 (**60% cost reduction**); FAISS persistence brought cold-start from 4–8 min to **<3 sec**
- Bounded self-healing loops (max 1 revise + 1 query-rewrite, 3 exit paths) remove infinite-loop risk in production
- **99.5% uptime** at 1000+ concurrent queries, sub-2-second response time, with input/output guardrails for safe extension

### 🤖 [Multi-Tool AI Agent — GAIA Benchmark](https://huggingface.co/spaces/kingwar1/AGENT-GAIA)
Autonomous `smolagents` CodeAgent handling multi-step reasoning across math, web lookup, audio, and file parsing.
- **Top-15%** on the GAIA benchmark; processed 50+ file formats at **98% accuracy**
- Intelligent fallback across HuggingFace Inference providers — **99.9% availability**, 40% lower API cost
- Benchmarked accuracy across GAIA's three difficulty tiers to isolate failure modes

### 🏦 [DepositFlow — End-to-End MLOps Pipeline](https://github.com/Amit95688/DepositFlow)
Full MLOps pipeline on 100K+ banking records: XGBoost, LightGBM, and neural nets, tracked across 30+ MLflow experiments.
- **ROC-AUC 0.97, F1 0.93**; dbt on AWS S3 for feature transforms
- Automated retraining via Airflow DAGs with data-availability triggers; Dockerized Flask API on EC2 + Lambda
- Drift-monitoring layer triggers retraining before performance degrades in production

<details>
<summary><b>Other Projects</b></summary>
<br>

**[Medical Chatbot — RAG](https://github.com/Amit95688/MEDICAL-CHATBOT)**
Retrieval-augmented chatbot answering medical queries from a curated knowledge base using embeddings and vector search, built to minimize hallucination over pure generation.

**[Nutrition Dataset](https://huggingface.co/datasets/kingwar1/nutri_food)**
1,582-example multimodal food-nutrition dataset (108 classes, Food101) with LLM-generated annotations, fine-tuned via SFT + LoRA for VLM instruction data.

</details>

---

## Kaggle — 9 Competitions, All Solo

| Competition | Rank | Result |
|---|---|---|
| Predicting Stellar Class (S6 E6) | 209 / 2,816 | **Top 8%** — 11-model hill-climbing ensemble, 0.97030 accuracy |
| Predicting F1 Pit Stops (S6 E5) | 367 / 3,022 | **Top 12%** — Gradient boosting + hyperparameter tuning |
| Thermophysical Property: Melting Point | 234 / 1,176 | **Top 20%** — Ensemble + feature engineering, MAE 23.4 |
| NVIDIA Nemotron Reasoning Challenge (Featured) | 1,587 / 4,182 | **Top 38%** — Fine-tuned Nemotron-3-Nano-30B MoE, Score 0.85 |

---

## GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Amit95688&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Amit95688&layout=compact&theme=tokyonight&hide_border=true" height="165" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com?user=Amit95688&theme=tokyonight&hide_border=true" />
</p>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=Amit95688&theme=tokyonight&no-frame=true&row=1&column=6" />
</p>

---

<p align="center">
  <i>Open to internships, collaborations, and interesting AI/ML problems — reach out on <a href="https://www.linkedin.com/in/amit-dubey-45292629a">LinkedIn</a>.</i>
</p>
