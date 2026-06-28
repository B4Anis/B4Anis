<h1 align="center">Mohamed Anis Bensabra</h1>


<p align="center">
  <b>AI &amp; Data Science Engineer</b> &nbsp;·&nbsp; Deep Learning &nbsp;·&nbsp; NLP &nbsp;·&nbsp; LLMs &amp; RAG &nbsp;·&nbsp; Reinforcement Learning &nbsp;·&nbsp; AI Agents
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/mohamed-anis-bensabra-a9798630b/">
    <img src="https://img.shields.io/badge/LinkedIn-Mohamed%20Anis%20Bensabra-1f6feb?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:mohamed.bensabra@ensia.edu.dz">
    <img src="https://img.shields.io/badge/Email-mohamed.bensabra@ensia.edu.dz-1f6feb?style=flat-square&logo=gmail&logoColor=white" alt="Email"/>
  </a>
</p>

---

Fourth-year engineering student at **ENSIA** — the National Higher School of Artificial Intelligence (Algeria) — specializing in **Artificial Intelligence & Data Science**. I build and deploy intelligent systems end-to-end, from retrieval-augmented LLM pipelines and reinforcement-learning agents to production microservices. My focus is on systems that are **grounded, measurable, and actually shipped** — not demos.

### What I'm working on / looking for

- 🎓 **Seeking a final-year project (PFE)** — in **industry, a research lab, or abroad**.
-  Going deep on **LLMs / RAG**, agentic workflows, deep reinforcement learning, and MLOps.
-  Recent work spans citation-grounded RAG engines, deep-RL pricing agents, and message-driven microservices.
-  Reach me at **mohamed.bensabra@ensia.edu.dz** — open to internships, research collaborations, and PFE offers.

---

## Featured Projects


###  Hospital Readmission Risk — End-to-End MLOps
Production-style MLOps pipeline for hospital readmission and length-of-stay prediction: **XGBoost** models, an **MLflow** registry (champion/challenger), a **FastAPI** serving layer, **Evidently** drift detection with automated retraining, **Fairlearn** fairness checks, a **Streamlit** dashboard, Docker Compose, and GitHub Actions CI.

`Python` · `XGBoost` · `MLflow` · `FastAPI` · `Evidently` · `Docker` · `CI`
&nbsp;·&nbsp; [**Repo →**](https://github.com/B4Anis/hospital-readmission-mlops)


###  Islamic Studies Scholarly Platform — RAG Engine
Core **Retrieval-Augmented Generation** engine for a scholarly assistant that answers questions from authenticated sources (Qur'an, Hadith, Fiqh, Tafsir, Fatwa) with strict, **citation-first** responses. JSON-to-vector ingestion with **BGE-M3** embeddings in **Qdrant**, an intent-aware search router that applies metadata filters *before* retrieval to eliminate context pollution, and a citation-first generation layer over a quantized **Qwen 2.5-7B-Instruct**. Deployed on NVIDIA H100 GPUs.

`Python` · `BGE-M3` · `Qdrant` · `Qwen 2.5-7B` · `RAG` · `NLP`

###  Deep Reinforcement Learning for Dynamic E-Commerce Pricing
A custom **Gymnasium** environment modeling 30-day pricing with price-elastic demand, seasonality, and inventory clearing pressure — then four deep-RL algorithms implemented **from scratch** in PyTorch: **DQN, A2C, PPO** (clipped surrogate + GAE), and **SAC-Discrete** (automatic entropy tuning). All agents beat the best hand-coded baseline by ~50% (~$15K/season), with comparative analysis of policy structure and sample efficiency across seeds.

`PyTorch` · `Gymnasium` · `DQN` · `A2C` · `PPO` · `SAC`

###  EEG-Based Sleep Stage Classification
Compared classical ML and deep learning for classifying sleep stages from raw EEG time series. Engineered time-domain, Hjorth, wavelet, and spectral features with SMOTE for class imbalance (**XGBoost** best at 65.6%), then implemented **CNN, LSTM, CNN-LSTM, and attention** architectures on raw signals — the CNN reaching **72.4% accuracy / 70.9% macro F1**, showing the edge of learned representations over hand-crafted features. *(Team project, 5 members.)*

`Python` · `TensorFlow` · `Scikit-learn` · `CNN / LSTM` · `Signal Processing`

###  ENSIA Document Management System
A message-driven **microservices** DMS behind a Spring Cloud API Gateway: JWT auth, a documents service with **MinIO (S3)** storage and **Redis** caching, a **Cassandra**-backed comments service for high-volume writes, and a Python translator service consuming **Kafka** events to auto-translate documents via the Gemini API. Adds Odoo ERP integration with RBAC, Prometheus/Grafana observability, Playwright/k6 testing, and Docker/Kubernetes deployment.

`Spring Boot` · `Kafka` · `React` · `PostgreSQL / Cassandra / Redis` · `Docker / Kubernetes`
&nbsp;·&nbsp; [**Repo →**](https://github.com/B4Anis/dms_microservices)

###  StudyMate — Educational AI Platform
A React front-end and Express.js back-end integrating LLMs (**Mistral 7B, DeepSeek Coder, Llama3-70B**) via Hugging Face and the **Groq API**. Implements **RAG** to generate flashcards and an AI chatbot that answers questions contextually from uploaded lecture material.

`React` · `Express.js` · `Hugging Face` · `Groq API` · `RAG` · `LLMs`


### Clinic Management System
Full-stack clinic platform (Sidi-Abdellah clinic) built as **Project Manager / Lead Developer** under Scrum: a **Node.js / Express / MongoDB** backend with JWT auth and REST APIs, and a **React / TypeScript / Redux** frontend with appointment scheduling.

`React` · `TypeScript` · `Redux` · `Node.js` · `Express` · `MongoDB`
&nbsp;·&nbsp; [**Repo →**](https://github.com/B4Anis/cims_final_sprint)

---

## Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-025E8C?style=flat-square&logo=postgresql&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)

**ML / AI**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=flat-square&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Ollama](https://img.shields.io/badge/Ollama-343434?style=flat-square&logo=ollama&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logo=qdrant&logoColor=white)

**Web & Backend**

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)

**Data & Infrastructure**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Cassandra](https://img.shields.io/badge/Cassandra-1287B1?style=flat-square&logo=apachecassandra&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=B4Anis&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&title_color=1f6feb&icon_color=1f6feb&text_color=c9d1d9&bg_color=0d1117" alt="B4Anis GitHub stats"/>
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=B4Anis&layout=compact&hide_border=true&langs_count=8&title_color=1f6feb&text_color=c9d1d9&bg_color=0d1117" alt="Top languages"/>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=B4Anis&hide_border=true&background=0d1117&ring=1f6feb&fire=1f6feb&currStreakNum=c9d1d9&sideNums=c9d1d9&currStreakLabel=1f6feb&sideLabels=c9d1d9&dates=8b949e&stroke=30363d" alt="GitHub streak"/>
</p>

<!--
  Repo links — current state:
  - Linked (public): ENSIA DMS, Hospital Readmission MLOps, Clinic Management System.
  - Text only (no public repo yet): Islamic Studies RAG, Deep RL Pricing (private: rl-project), EEG Sleep Stage, StudyMate.
    To link any of these later, make the repo public and append this to its tags line:
      &nbsp;·&nbsp; [**Repo →**](https://github.com/B4Anis/<repo>)
  - Not included (your choice): voting-dapp (Decentralized Voting System).
-->
