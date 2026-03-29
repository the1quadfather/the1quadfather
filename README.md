# the1quadfather

I build analytical tools across many domains, including:
 
**Open source intelligence & policy analysis** — NLP pipelines for unstructured government documents, cross-referencing defense budgets, policy documents, and program records to surface insights that aren't visible in any single source.
 
**Dynamics & systems engineering** — predictive modeling, simulation, and remaining useful life estimation for mechanical and aerospace systems. From turbofan degradation to SLAM-based robotics.
 
**Business intelligence** — translating messy operational data into structured, queryable systems with clear analytical outputs. Building the pipelines that turn documents and databases into decisions.

---

## Featured Project

### 🇺🇸 [USG Budget Analyzer](https://github.com/the1quadfather/usg-budget-analyzer)

A full end-to-end pipeline that cross-references 28 years of DoD unclassified R-1 RDT&E budget documents with National Defense Strategies, National Security Strategies, and NDAA legislation — answering the question: *did funding actually follow stated strategic priorities?*

- Parses 28 fiscal years of PDF budget justification books into a structured SQLite database
- 4-stage NLP matching pipeline: PE number lookup → acronym index → fuzzy matching → semantic similarity
- Cross-references 12,000 policy document chunks against 2,100 program elements using SentenceTransformers
- Deployed as a Streamlit app via Docker on Railway

**Stack:** Python · SQLite · SentenceTransformers · RapidFuzz · Streamlit · Docker

---

## Other Work

| Project | Description | Stack |
|---|---|---|
| [FireScout-SLAM](https://github.com/the1quadfather/FireScout-SLAM) | SLAM-based firefighting scout robot simulation | Python · ROS · Jupyter |
| [Drone-Landing-Vision](https://github.com/the1quadfather/Drone-Landing-Vision) | Precision drone landing using YOLOv8 Nano on the TEKNOFEST dataset | Python · YOLOv8 · OpenCV |
| [NFL Play Predictor](https://github.com/the1quadfather/nfl_play_predictor) | Next-play prediction from game state variables | Python · sklearn · Jupyter |
| [NASA Turbofan RUL](https://github.com/the1quadfather/NASA-Turbofan-Predictive-Modeling) | Remaining useful life prediction using LSTM on the NASA CMAPSS dataset | Python · PyTorch · Jupyter |

---

## Skills

`Python` `PyTorch` `NLP` `Computer Vision` `Predictive Modeling` `Docker` `SQLite` `Streamlit` `PDF Parsing` `Data Engineering` `Tensorflow` `Data Analysis` `Data Engineering` `LLM` `RAG` `Neural Networks`
