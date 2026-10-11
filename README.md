&lt;div align="center"&gt;

# 🎯 SkillSync AI

### **Smart Resume Gap Analyzer Powered by RAG**

**By Farise aml**

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)](https://streamlit.io)
[![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)](https://plotly.com)
[![RAG](https://img.shields.io/badge/RAG-Vector%20Retrieval-green?style=for-the-badge)](https://)
[![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)

&lt;/div&gt;

---

## 📸 Preview

&lt;div align="center"&gt;

| **Upload Resume** | **Gap Analysis** | **Learning Path** |
|:---:|:---:|:---:|
| 📄 Paste or upload resume | 📊 Interactive gauge charts | 🎓 Curated course recommendations |
| 🎯 Select target role | 🔴 Missing skills highlighted | ⏱️ Time estimates per skill |
| 🤖 AI extracts skills | ✅ Strengths identified | 📥 Exportable reports |

&lt;/div&gt;

---

## ✨ What is SkillSync AI?

**SkillSync AI** is an intelligent resume analysis tool that uses **Retrieval-Augmented Generation (RAG)** to:

- 🔍 **Extract** skills from your resume using advanced pattern matching
- 📊 **Compare** your skills against real-world job role requirements
- 📉 **Identify** gaps between what you have and what employers want
- 🎓 **Recommend** curated courses to close those gaps
- 📈 **Score** your readiness for any target role (0-100%)

&gt; 💡 *"73% of resumes are rejected by ATS before a human sees them — usually due to missing keywords. SkillSync AI fixes that in seconds."*

---

## 🚀 Features

| Feature | Description |
|---------|-------------|
| 📄 **Multi-Format Resume Parsing** | Supports PDF, DOCX, and TXT files |
| 🧠 **AI Skill Extraction** | Detects 60+ technical and soft skills automatically |
| 🔍 **RAG-Powered Matching** | TF-IDF vector store retrieves relevant job requirements |
| 📊 **Interactive Dashboard** | Plotly gauge charts, skill tags, and gap heatmaps |
| 🎯 **5 Job Roles** | Software Engineer, Data Scientist, ML Engineer, DevOps, Product Manager |
| 🎓 **95 Curated Courses** | Hand-picked learning resources with time estimates |
| 📥 **Export Reports** | Downloadable Markdown and JSON analysis reports |
| ⚡ **Real-Time Analysis** | Results in under 10 seconds |

---

## 🏗️ Architecture
┌─────────────────┐     ┌─────────────────┐     ┌─────────────────┐
│   Resume Input  │────▶│  Resume Parser  │────▶│ Skill Extractor │
│ (PDF/DOCX/TXT)  │     │   (PyMuPDF)     │     │ (Pattern + NLP) │
└─────────────────┘     └─────────────────┘     └─────────────────┘
│
┌─────────────────────────┘

▼
┌─────────────────┐     ┌─────────────────┐     ┌─────────────────┐
│   Course DB     │◀────│  Gap Analyzer   │◀────│   RAG Engine    │
│ (95 resources)  │     │ (Scoring +      │     │ (TF-IDF Vector  │
└─────────────────┘     │  Recommend)     │     │  Store + Sim)   │
└─────────────────┘     └─────────────────┘
│
▼
┌─────────────────┐
│  Streamlit UI   │
│ (Gauge Charts + │
│  Skill Gaps +   │
│  Learning Path)  │
└─────────────────┘

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|------------|
| **Frontend** | Streamlit |
| **Visualizations** | Plotly |
| **PDF Parsing** | PyMuPDF |
| **DOCX Parsing** | python-docx |
| **Vector Store** | Custom TF-IDF + NumPy |
| **Embeddings** | TF-IDF with IDF weighting |
| **Language** | Python 3.8+ |

---

## 📦 Installation

### Prerequisites
|- Python 3.8 or higher|
|- pip (Python package manager)|

    ╭──────────────╮
    │              │
    │    68%       │  ← Your readiness score
    │   Ready      │  ← Readiness level
    │              │
    ╰──────────────╯
| Skill               | Category     | Priority | Status     | Target       |
| ------------------- | ------------ | -------- | ---------- | ------------ |
| Docker & Kubernetes | DevOps       | should   | 🔴 missing | intermediate |
| System Design       | Architecture | must     | 🔴 missing | intermediate |
| Microservices       | Architecture | should   | 🟡 partial | intermediate |

Recommended Learning Path

Docker & Kubernetes (should priority)

Docker & Kubernetes: The Practical Guide — Academind (Udemy)

CKAD Certification — Linux Foundation

⏱️ Estimated: 4-8 weeks

System Design (must priority)

System Design Interview — Alex Xu

Designing Data-Intensive Applications — Martin Kleppmann

⏱️ Estimated: 4-8 weeks

📁 Project Structure

skillsync-ai/
│
├── app.py                    # Main Streamlit application
├── resume_parser.py          # PDF/DOCX/TXT text extraction
├── skill_extractor.py        # 60+ skill detection patterns
├── rag_engine.py             # TF-IDF vector store + retrieval
├── gap_analyzer.py           # Gap scoring + recommendations
├── requirements.txt          # Python dependencies
├── demo.html                 # Standalone browser demo
└── data/
    ├── job_roles.json        # 5 roles, 75 required skills
    └── courses.json          # 95 curated learning resources




👤 Author
Farise aml
🏆 Built for Workshop Presentation
🎯 Focused on practical AI applications
💡 Passionate about bridging skill gaps
📜 License
This project is licensed under the MIT License — free for educational and workshop use.
<div align="center">
⭐ Star this repo if you found it helpful!
Built with ❤️ by Farise aml
🎯 SkillSync AI — Know Your Gaps, Close Them Fast.
</div>
