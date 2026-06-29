# Hi, I'm Tuhin Das 👋

MS Student in Electrical & Computer Engineering (Machine Learning & Data Science) at the **University of Southern California**. I build production-grade ML systems — from raw data pipelines to containerized APIs deployed on cloud infrastructure.

📢 **Open to full-time roles in ML Engineering, AI Engineering, MLOps, and Data Science.**

---

## 🎓 Research Experience

### USC Iovine and Young Academy — HTI Lab *(Nov 2025 – May 2026)*
- Designed and containerized a clinical prediction pipeline (FastAPI + Docker) serving real-time surgical complication risk assessments for **J&J MedTech Ethicon** — sub-200ms inference latency
- Engineered distributed ETL pipelines across **58k+ patients, 83k+ surgeries** (MOVER dataset) using Apache Airflow, accelerating preprocessing by **34%**
- Fine-tuned BioBERT & ClinicalBERT for cross-modal retrieval across EHR text and surgical images — **Top-5 retrieval accuracy: 89%**

### Valero Lab, USC — Research Intern *(Jun 2025 – Aug 2025)*
- Scaled RL models (PPO) in TensorFlow across AWS SageMaker and EC2 multi-GPU clusters, accelerating policy evaluation by **42%**
- Built real-time hardware control systems with Arduino and Python serial drivers — sub-15ms telemetry latency for live ML inference

### Aerospace & Mechanical Engineering, USC — Research Intern *(Feb 2025 – Mar 2025)*
- Benchmarked YOLOv8 and YOLO-NAS; integrated DVC + DagsHub to version a 12,000-image dataset, reducing experiment tracking latency by **28%**
- Designed dual-task architecture for concurrent image segmentation and monocular depth estimation

---

## 📄 Publication

**"A2IPPG: A Machine Learning Assisted Real-time Standalone Continuous Authorization to Identification Using Photoplethysmogram Features"**
*IEEE Sensors Letters, 2025*

---

## 📂 Projects

### 🛡️ [PhishOps](https://github.com/Aspect661/PhishOps) — Phishing Detection MLOps Pipeline
Production-style network security system classifying URLs as phishing or legitimate using 31 features.

- **Best model:** Gradient Boosting — F1: 0.978 | Precision: 0.981 | Recall: 0.975
- **Stack:** FastAPI · scikit-learn · MongoDB Atlas · MLflow + DagsHub · Docker · AWS (EC2, ECR, S3)
- **CI/CD:** 3-job GitHub Actions workflow — lint/test → build & push to ECR → zero-downtime redeploy on EC2
- KS drift detection, KNN imputation, versioned artifact storage on S3

---

### 🍷 [End-to-End MLOps Pipeline](https://github.com/Aspect661/End-to-End-MLOps-Pipeline) — Wine Quality Predictor
Production-ready 5-stage ML pipeline with experiment tracking and a live Flask interface.

- **Stack:** Flask · scikit-learn · MLflow + DagsHub · YAML config
- Schema validation, centralized config, no hardcoded values anywhere

---

### 💬 [SamSum Dialogue Summarizer](https://github.com/Aspect661/SamSum-Dialogue-Summarizer) — NLP Fine-Tuning Pipeline
Fine-tunes Google's PEGASUS on the SAMSum dialogue dataset for abstractive summarization.

- **Stack:** HuggingFace Transformers · FastAPI · Docker
- Evaluated via ROUGE-1, ROUGE-2, ROUGE-L; gradient accumulation for memory-efficient training

---

### 📊 [PerformanceOps](https://github.com/Aspect661/PerformanceOps) — Student Score Predictor
End-to-end ML pipeline evaluating 8 regression models via GridSearchCV, deployed on AWS Elastic Beanstalk.

- **Stack:** Flask · scikit-learn · XGBoost · CatBoost

---

## 🛠️ Tech Stack

| Area | Tools |
|------|-------|
| **Languages** | Python, C++, SQL |
| **ML / DL** | PyTorch, TensorFlow, scikit-learn, XGBoost, CatBoost, HuggingFace |
| **NLP / CV** | Transformers, BioBERT, YOLOv8, SRCNN, SRGAN |
| **MLOps** | MLflow, DVC, Apache Airflow, DagsHub, GitHub Actions |
| **APIs** | FastAPI, Flask |
| **Cloud** | AWS (SageMaker, EC2, ECR, S3), Azure (ML Studio, Blob Storage) |
| **Databases** | MongoDB Atlas, PostgreSQL |
| **DevOps** | Docker, Git |

---

## 📫 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Tuhin%20Das-blue?logo=linkedin)](https://www.linkedin.com/in/tuhin-das-912a08271)
[![GitHub](https://img.shields.io/badge/GitHub-Aspect661-black?logo=github)](https://github.com/Aspect661)
[![Email](https://img.shields.io/badge/Email-tuhindas01.official@gmail.com-red?logo=gmail)](mailto:tuhindas01.official@gmail.com)
