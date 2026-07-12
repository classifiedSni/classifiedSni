# Hi, I'm Siddharth Munagala

Machine Learning Engineer working on production ML systems and LLM applications. MS in Data Science (UMass Dartmouth, 2025). I care about models that survive contact with real data, not just clean leaderboard numbers.

Currently open to ML Engineer, AI Engineer, and Data Scientist roles.

---

## What I build

**LLM and RAG systems.** Retrieval pipelines that ground model output in real documents: embeddings, vector stores, chunking strategy, and the evaluation work that tells you whether retrieval is actually helping.

**Production ML.** End-to-end pipelines from raw multi-table data to a deployed API. ETL, feature engineering, gradient boosting, experiment tracking, containerized serving.

**Honest evaluation.** I spend as much time trying to break my own results as producing them. On my churn project, I traced a suspiciously high ROC-AUC (0.9950) to a leaked feature, removed it, and reported the real number (0.9686). The lower score is the useful one.

---

## Selected projects

| Project | What it does | Stack |
|---|---|---|
| **[ClinicalBridge](#)** | LLM-powered clinical handoff assistant over MIMIC-IV. RAG retrieval over clinical notes plus an XGBoost risk model with SHAP explanations, served through a FastAPI backend and React frontend. | BioBERT, ChromaDB, LangChain, Claude API, medspaCy, XGBoost, SHAP, FastAPI, React |
| **[churn-prediction](#)** | End-to-end customer churn system on the KKBox dataset. Multi-table ETL across user logs, transactions, and member records, with temporal validation and a Dockerized inference API. | LightGBM, XGBoost, MLflow, SHAP, FastAPI, Docker |
| **[Parking Occupancy Detection](#)** | Image-based parking space occupancy detection on the PKLot dataset. Compared one-stage and two-stage detectors across accuracy and inference cost. | Detectron2, Faster R-CNN, RetinaNet, YOLOv8 |
| **[Portfolio](#)** | Personal site with live demos of the projects above. | Next.js, Tailwind, FastAPI, Vercel |

---

## Tools I actually use

**Languages:** Python, SQL
**ML:** LightGBM, XGBoost, scikit-learn, PyTorch, SHAP
**LLM / RAG:** LangChain, ChromaDB, BioBERT, Claude API
**Data:** PySpark, Pandas, ETL pipeline design
**Deployment:** FastAPI, Docker, AWS, MLflow

---

## Writing

I write about applied ML and where the AI industry is heading, on [Medium](https://medium.com/@sidsblog).

---

## Reach me

[Email](mailto:munagalasiddharth@gmail.com) · [LinkedIn](https://www.linkedin.com/in/siddharth-munagala/) · [Medium](https://medium.com/@sidsblog)
