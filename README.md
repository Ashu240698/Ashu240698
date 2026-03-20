# Hi there, I'm Ashutosh! 👋

**Data Engineer | Python Developer | AI/ML Engineer | PySpark & ETL Specialist**

🔧 Currently working as a **Data Engineer at Virtusa** (Citi Private Bank engagement)  
🚀 Passionate about **AI-powered systems**, **large-scale data engineering**, and **intelligent pipelines**  
💡 **4.4 years of experience** in Python, Oracle ETL, and production data systems

---

## 🎯 Featured Projects

### 🤖 PyDoc AI — AI-Powered Python Documentation Assistant
**Production-grade RAG system** with hybrid search and LLM integration

**🌐 [Live Demo](https://huggingface.co/spaces/ashu240698/pydoc-ai)** | **📂 [Source Code](https://github.com/YOUR_USERNAME/pydoc-ai)**

**Key Achievements:**
- 🔍 **35% accuracy improvement** using BM25 + FAISS hybrid search
- 🎯 **Cross-encoder re-ranking** for superior result quality
- ⚡ **Sub-2-second response time** with source citations
- 🤖 **Groq LLM integration** (llama-3.1-8b-instant) with conversation memory
- 📚 **1,371 documentation chunks** from Python stdlib, pandas, requests
- 🔐 **Secure deployment** with user-provided API keys

**Technical Implementation:**
- Two-stage retrieval: Hybrid search (20 candidates) → Cross-encoder re-ranking (top 4)
- Auto-downloading indexes from HuggingFace dataset (no Git LFS)
- Comprehensive logging (query, performance, error tracking)
- Streamlit UI with chat interface and expandable sources

**Tech Stack:** Python, FAISS, sentence-transformers, BM25, Groq API, LangChain, Streamlit, HuggingFace

---

### ⚡ Spark ETL Projects — Production-Grade PySpark Pipelines
**Two end-to-end PySpark pipelines** built from scratch with real-world data quality challenges

#### **Project 2 — Financial Transaction Intelligence Pipeline**

**Business Context:** Multi-channel payment monitoring with fraud detection and merchant risk profiling

**Key Features:**
- 🔍 **Multi-channel ingestion** (UPI, NEFT, RTGS, IMPS, Card) with 6 timestamp formats
- 🚨 **5-rule fraud detection engine:**
  - Missing transaction amounts
  - Limit breaches (>₹2L)
  - High-value international transfers (>₹5L)
  - Suspicious velocity patterns
  - Card fraud indicators
- 🏪 **Merchant risk profiling** — failure rates, reversal rates, international ratios per category
- 📊 **Partitioned Parquet output** by payment channel + transaction status (20 partitions, pruning verified)

**Technical Highlights:**
- Broadcast join optimization for merchant data
- Window functions for transaction velocity analysis
- Timestamp normalization across 6 formats
- Data quality validation with detailed logging

#### **Project 1 — Database Fleet Intelligence Pipeline**

**Business Context:** Enterprise database fleet monitoring and incident classification

**Key Features:**
- 🖥️ **Fleet monitoring** — ingests raw database metrics from CSV (CPU, Memory, Disk, Sessions)
- ⚖️ **Weighted risk scoring:**
  - CPU (40%) + Memory (30%) + Disk (20%) + Sessions (10%)
  - SLA multiplier (CRITICAL: 1.5x, HIGH: 1.2x, MEDIUM: 1.0x)
- 🚨 **Incident classification:**
  - IMMEDIATE_PAGE (risk ≥ 90)
  - URGENT_TICKET (risk 70-89)
  - MEMORY_ALERT, DISK_ALERT (specific thresholds)
- 📊 **Partitioned Parquet output** by region + environment with partition pruning verified

**Technical Highlights:**
- Custom UDFs for risk scoring logic
- Multi-level partitioning strategy
- Performance optimization with caching
- Comprehensive unit test coverage

**Tech Stack:** PySpark 4.1.1, Python 3.12, Parquet, CSV, Broadcast Joins, Delta Lake (in progress)

**📂 [Spark Projects Repository](https://github.com/YOUR_USERNAME/spark-projects)**

---

## 💻 Tech Stack

**Languages:**  
`Python` • `SQL`

**AI/ML:**  
`RAG` • `LLMs` • `FAISS` • `sentence-transformers` • `LangChain` • `Groq API`

**Data Engineering:**  
`PySpark` • `ETL Pipelines` • `Delta Lake` • `Parquet` • `Broadcast Joins` • `Partitioning` • `Window Functions`

**Databases:**  
`Oracle` • `PostgreSQL` • `MongoDB`

**Web Development:**  
`Streamlit` • `Flask`

**Tools & DevOps:**  
`Git` • `Docker` • `Linux` • `WSL2` • `HuggingFace`

---

## 📊 What I'm Working On

⭐ **Currently exploring:**
- Advanced RAG architectures (multi-modal, agentic RAG)
- Databricks and Delta Lake optimization
- PySpark performance tuning and cost optimization
- Production LLM deployment patterns

💞️ **Open to collaborate on:**
- AI/ML projects (RAG, LLMs, NLP)
- Data engineering and PySpark pipelines
- Python automation and intelligent systems
- Open source contributions

---

## 📫 Let's Connect

📧 **Email:** [janapureashutosh@gmail.com](mailto:janapureashutosh@gmail.com)  

🚀 **HuggingFace:** [ashu240698](https://huggingface.co/ashu240698)

---

## 🏆 Professional Experience

**Data Engineer @ Virtusa** (Citi Private Bank)  
- Building production ETL pipelines for financial data processing
- Oracle-based data integration and transformation
- Performance optimization and data quality frameworks

---

⭐ **If you find my projects useful, please star them!**  
💬 **Feel free to reach out for collaborations or just to chat about data & AI!**
```
