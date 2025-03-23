
# 🧠 End-to-End ML Project Using AWS SageMaker: Titanic Survival Prediction

This project walks through a real-world ML workflow on **Amazon SageMaker** — from data to deployment and automation — with certification alignment for AWS ML Associate and AI Practitioner.

---

## 👨🏽‍💻 Author

**Samuel Ogah**  
_Principal DevSecOps, Security & AI Engineer_  
🔗 [LinkedIn](https://www.linkedin.com/in/samuelogah)  
📫 [GitHub](https://github.com/sogah2023)

---

## 🖼️ Architecture Diagram
![image](https://github.com/user-attachments/assets/8fd1bd48-36a4-4641-bb8c-1fae208713eb)

  
> Includes: S3 → Data Wrangler → Training → HPO → Endpoint → Monitor → Pipelines → IAM → GuardDuty

📌 **[Insert Stage-Specific Diagrams Below]**  
- Stage 1: Data Ingestion & Cleaning [Insert Diagram]  
- Stage 2: Model Dev with Studio/Autopilot [Insert Diagram]  
- Stage 3: Training & HPO Infrastructure [Insert Diagram]  
- Stage 4: Real-time & Batch Deployment Setup [Insert Diagram]  
- Stage 5: Monitoring & SHAP Bias Flow [Insert Diagram]  
- Stage 6: CI/CD Automation with IAM/VPC

---

## 🧭 Learning Map: Beginner to Advanced

| Level        | What to Focus On                                   | Tools & Keywords                          |
|--------------|----------------------------------------------------|-------------------------------------------|
| Beginner     | Notebooks, JumpStart, Endpoints                    | Studio IDE, Autopilot, Deploy             |
| Intermediate | Data Wrangler, Estimator, HPO, Clarify             | Experiments, Model Monitor, Feature Store |
| Advanced     | Pipelines, IAM, CI/CD, VPC, Security Guardrails    | Step Functions, KMS, GuardDuty            |

---

## 🧩 Project Scenario: Real-World Simulation

🧙🏽‍♂️ Imagine this:

> “You’re hired to build a machine learning system that predicts Titanic survival, but your manager demands:
>
> ✅ Automation  
> ✅ Monitoring & Bias Reports  
> ✅ Endpoint deployment & Explainability  
> ✅ Audit compliance & security readiness”

Your task is to bring it to life using **SageMaker’s end-to-end tools**!

---

## 📁 Dataset

🎯 Titanic Dataset  
🔗 [Click to Download (from GitHub)](https://github.com/sogah2023/AI-ML/blob/main/Titanic%20Dataset.csv?raw=true)

Upload to S3 before launching the notebook.

---

## 🚀 Project Stages

| Stage      | Tools & Services                                                                 | Output                                      |
|------------|-----------------------------------------------------------------------------------|---------------------------------------------|
| 📥 Data Prep  | Data Wrangler, Processing Jobs, Feature Store                                    | Cleaned S3 data or features in Feature Store |
| 🔧 Dev        | Notebooks, JumpStart, Autopilot                                                  | Model candidates & EDA                      |
| 🎯 Training   | Estimator, Spot Training, Hyperparameter Tuner, Debugger, Experiments            | model.tar.gz, tuning reports                |
| 🚀 Deployment | Real-time Endpoints, Batch Transform, Neo                                        | Live endpoint or batch prediction files     |
| 🧠 Monitoring | Clarify, Model Monitor, CloudWatch                                                | SHAP reports, bias logs, CloudWatch alerts  |
| 🔁 Automation | Pipelines, Step Functions, IAM, VPC, KMS, GuardDuty                               | Automated pipeline, secure audit trail      |

---

## 📘 How to Use This Repo

1. Clone this repo into SageMaker Studio or local environment
2. Upload the Titanic dataset to S3
3. Open and run the Jupyter Notebook: `SageMaker_ML_Titanic_Complete.ipynb`
4. Follow each stage — Data Prep → Dev → Train → Deploy → Monitor → Automate
5. Insert diagrams where noted to visualize architecture

---

## 🧠 Certification Readiness

### Covered for AWS ML Associate & Practitioner:

- ✅ SageMaker Studio IDE, Autopilot, and Pipelines
- ✅ HPO, Debugger, Spot Training
- ✅ Feature Store, Batch Transform, Endpoints
- ✅ SHAP & Clarify for explainability
- ✅ IAM, KMS, GuardDuty for security
- ✅ End-to-end ML workflow understanding

---

## 📜 License

MIT License — free to use, adapt, and improve.

---

> 📌 Want visual diagrams or Terraform templates added?  
> ✉️ [Open an issue or contact me on LinkedIn](https://www.linkedin.com/in/samuelogah)  
> ⭐ Star this repo to follow updates!
