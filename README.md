<div align="center">
  <img src="https://github.com/dahuyn1625/dahuyn1625/blob/main/assets/banner-ai-research.png?raw=true" 
       alt="Nguyễn Gia Huy – AI Research Engineering" 
       width="100%" 
       style="border-radius: 12px; margin-bottom: 32px; box-shadow: 0 8px 32px rgba(0, 247, 255, 0.12);">

  <img src="https://readme-typing-svg.herokuapp.com?font=Space+Grotesk&weight=600&size=32&duration=3200&pause=1200&color=00F7FF&center=true&vCenter=true&width=820&lines=AI+Engineer+%7C+Deep+Learning+%26+Quantitative+Research;Architecting+Scalable+LLM+%26+RAG+Systems;From+Neural+Networks+to+Real-World+Systems" 
       alt="Animated professional tagline" />

  <h3>AI Engineer • Deep Learning Researcher • Quantitative AI Systems</h3>
</div>

---

**Nguyễn Gia Huy**  
AI Engineer focused on building production-oriented intelligent systems that bridge research and scalable infrastructure.

My work centers on Large Language Models, Retrieval-Augmented Generation, deep learning optimization, and quantitative evaluation of AI architectures. I design systems that are reproducible, measurable, and engineered for real-world deployment rather than isolated experiments.

---

## Tech Stack

**Languages**  
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

**AI & Deep Learning**  
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)

**Backend & Infrastructure**  
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)

**Core Tools**  
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)

---

## Featured Research Project

### Hybrid BM25 + Vector Search: RAG vs LLM-only

**Research Objective**  
Benchmark the effectiveness of hybrid retrieval-augmented generation against vanilla LLM-only pipelines in a narrow, domain-specific question-answering task (nutrition-focused health queries). The goal is to quantify hallucination reduction, answer quality, and retrieval robustness when combining lexical (BM25) and semantic (vector) signals.

**System Architecture**  
- Modular pipeline architecture with isolated phases: data preparation, indexing, hybrid retrieval, generation, and automated evaluation.  
- Hybrid retrieval engine built on PostgreSQL using `pg_textsearch` (BM25) + `pgvector` (dense embeddings) with reciprocal rank fusion for ranking.  
- Dual inference paths: `hybrid_rag` (context-grounded) vs `llm_only` (direct generation).  
- Local-first deployment via Docker Compose for full reproducibility.  
- Side-by-side interactive demo with FastAPI backend and Next.js frontend displaying retrieval logs, citations, and timing metrics.

**Engineering Decisions**  
- Chose PostgreSQL as single source of truth for both lexical and vector indexing to minimize infrastructure complexity.  
- Implemented reciprocal rank fusion to balance BM25 and embedding scores without introducing external vector stores.  
- Automated evaluation harness covering retrieval metrics, answer quality scoring, and pairwise comparison between modes.  
- Prioritized clean separation of concerns and script-driven execution for research reproducibility.

**Scalability Direction**  
Designed as a foundation for larger-scale RAG systems: containerized, modular, and ready for distributed indexing or production serving layers.

**Future Work**  
Extend to multi-agent retrieval, long-context optimization, domain adaptation, and integration with open-source LLM serving frameworks.

[→ View Repository](https://github.com/dahuyn1625/hybrid-bm25-vector-search-rag-vs-llm-only)

---

## Research Philosophy

I approach AI engineering as the disciplined intersection of theoretical rigor and systems thinking. Every model, pipeline, or evaluation is built with three non-negotiable principles:

- **Reproducibility** through deterministic pipelines and versioned artifacts  
- **Measurability** via quantitative benchmarks and ablation studies  
- **Scalability** by default — infrastructure decisions are made early, not as an afterthought

Current research interests include advanced RAG architectures, efficient LLM inference, quantitative evaluation of generative systems, and production-grade MLOps for research-to-deployment workflows.

---

## GitHub Analytics

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=dahuyn1625&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=dahuyn1625&layout=compact&theme=tokyonight&hide_border=true&size_weight=0.5&count_weight=0.5)

</div>

---

## Current Exploration

**Active Focus**  
- Hybrid retrieval systems and quantitative RAG evaluation  
- Production-ready LLM serving and inference optimization  

**Next Horizon**  
- Multi-agent architectures and autonomous evaluation frameworks  
- Scalable AI infrastructure and MLOps at research scale  

**Long-Term Direction**  
Contribute to open-source AI tooling, publish technical research, and engineer systems that move from laboratory prototypes to reliable real-world intelligence.

---

## Connect

- **LinkedIn**: [linkedin.com/in/giahuy1625](https://www.linkedin.com/in/giahuy1625)  
- **Email**: [nguyengiahuy1625@gmail.com](mailto:nguyengiahuy1625@gmail.com)  
- **GitHub**: [github.com/dahuyn1625](https://github.com/dahuyn1625)

Open to research discussions, collaboration on LLM/RAG systems, or engineering roles in AI infrastructure.

---

<div align="center" style="margin-top: 64px; opacity: 0.6; font-size: 0.85em;">
  <p>© 2026 • Nguyễn Gia Huy</p>
  <p>Engineering intelligence from neural networks to production systems</p>
</div>
