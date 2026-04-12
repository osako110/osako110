<h1 align="center">Hi, I'm Qijun Li 👋</h1>

<p align="center">
  <em>Full-Stack AI Engineer · Building agentic systems with real engineering rigor</em>
  <br/>
  <sub>M.S. Computer Science @ UC San Diego</sub>
</p>

<p align="center">
  <a href="mailto:qil060@ucsd.edu"><img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/qijun-li-5b9468311/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" /></a>
  <a href="https://github.com/osako110"><img src="https://komarev.com/ghpvc/?username=qijun-li&label=Profile%20views&color=0e75b6&style=flat" /></a>
</p>

---

### 🚀 About Me



- 🤖 **AI Engineer** — building multi-agent orchestration, MCP-connected tools, RAG pipelines, and LLM evaluation harnesses
- 🛠️ **Full-Stack SDE** — comfortable end-to-end from React/Next.js UIs down to Kafka, PostgreSQL, and Kubernetes
- 💼 Most recently shipped a production AI product at **Hirello.ai**, taking LLM service reliability from 85% → 99%+
- 🎓 Finishing my M.S. at UCSD (graduating **March 2026**) — open to full-time **AI Engineer / SDE** roles
- 📫 Reach me at **qil060@ucsd.edu**

---

### 🛠️ Tech Stack

**🤖 AI / Agent Systems**

<p>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white" />
  <img src="https://img.shields.io/badge/Vertex_AI-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white" />
  <img src="https://img.shields.io/badge/MCP-000000?style=for-the-badge&logo=anthropic&logoColor=white" />
  <img src="https://img.shields.io/badge/Pinecone-1C17FF?style=for-the-badge&logo=pinecone&logoColor=white" />
  <img src="https://img.shields.io/badge/pgvector-336791?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/FAISS-0467DF?style=for-the-badge&logo=meta&logoColor=white" />
  <img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" />
</p>

**⚙️ Backend & Data**

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white" />
</p>

**🌐 Frontend & Cloud**

<p>
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/TailwindCSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white" />
  <img src="https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" />
</p>

---

### 📌 Featured Projects

#### 🤖 [AI Sales Automation Platform](https://github.com/osako110/ai-sales-platform)
> **Agent orchestration engine with multi-turn function calling, MCP tools, and a custom RouterKernel for multi-step tool selection.** Built a semantic part-retrieval layer on pgvector + BGE embeddings + HF TEI reranking. Achieved **91% field-level accuracy** on structured quotation extraction.
>
> `OpenRouter` · `MCP` · `pgvector` · `BGE` · `FastAPI` · `React` · `TypeScript`

#### 🎬 [AI Video Insight Platform](https://github.com/osako110/AI-Summary)
> **Long-form transcript understanding with grounded QA and topic-level summarization.** RAG pipeline on LangChain + FAISS with vector indexes persisted to S3 for cross-session reuse. Built an **LLM-as-a-judge eval harness** measuring recall, grounding, and hallucination rate. Cut transcript lookup latency to **<300ms**.
>
> `LangChain` · `FAISS` · `AWS S3` · `MongoDB`

#### 💬 [Distributed Messaging Engine](https://github.com/osako110/chat)
> **Horizontally-scalable IM system** with Nginx load-balanced WebSocket clusters, Kafka-partitioned event pipeline, and Redis routing for cross-server state sync. Polyglot persistence: PostgreSQL for metadata, MongoDB for chat logs.
>
> `WebSocket` · `Kafka` · `Redis` · `PostgreSQL` · `MongoDB` · `Nginx`

#### 📚 [Social Book Recommendation Platform](https://github.com/osako110/Recommend)
> **Two-stage ranking pipeline** combining candidate generation with XGBoost re-ranking — improved **NDCG@10 by 12%**. Sentence-BERT embeddings for cold-start retrieval. Event-driven training on Kafka + Ray + Airflow + K8s, cutting retraining time **3×**.
>
> `XGBoost` · `Sentence-BERT` · `Kafka` · `Ray` · `Airflow` · `Kubernetes`

---

### 📊 GitHub Stats

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=qijun-li&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=qijun-li&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=qijun-li&theme=tokyonight&hide_border=true" />
</p>

---

<p align="center">
  <em>"Build AI systems that actually work in production — not just demos."</em>
</p>
