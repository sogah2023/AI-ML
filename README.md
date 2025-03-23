
# 🧠 End-to-End ML Project Using AWS SageMaker: Titanic Survival Prediction

This project walks through a real-world ML workflow on **Amazon SageMaker** — from data to deployment and automation — with certification alignment for AWS ML Associate and AI Practitioner.

---

## 👨🏽‍💻 Author

**Samuel Ogah**  
_Principal DevSecOps, Security & AI Engineer_  
🔗 [LinkedIn](https://www.linkedin.com/in/sogah)  
📫 [GitHub](https://github.com/sogah2023)

---

## 🖼️ Architecture Diagram
![image](https://github.com/user-attachments/assets/8fd1bd48-36a4-4641-bb8c-1fae208713eb)

  
> Includes: S3 → Data Wrangler → Training → HPO → Endpoint → Monitor → Pipelines → IAM → GuardDuty
 
- Stage 1: Data Ingestion & Cleaning 
- Stage 2: Model Dev with Studio/Autopilot   
- Stage 3: Training & HPO Infrastructure  
- Stage 4: Real-time & Batch Deployment Setup  
- Stage 5: Monitoring & SHAP Bias Flow
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

---

## 🧠 Certification Readiness

### Covered for AWS ML Associate & Practitioner:

- ✅ SageMaker Studio IDE, Autopilot, and Pipelines
- ✅ HPO, Debugger, Spot Training
- ✅ Feature Store, Batch Transform, Endpoints
- ✅ SHAP & Clarify for explainability
- ✅ IAM, KMS, GuardDuty for security
- ✅ End-to-end ML workflow understanding

💻 **Notebook Reference**:  
🔗 [SageMaker_ML_Titanic_Complete.ipynb](https://github.com/sogah2023/AI-ML/blob/main/SageMaker_ML_Titanic_Complete.ipynb)

---

💻 **Notebook Reference for each stage 1-6**  
🔗 [SageMaker_ML_Titanic_Complete.ipynb](https://github.com/sogah2023/AI-ML/blob/main/SageMaker_ML_Titanic_Complete.ipynb)


## 🧱 Step-by-Step ML Lifecycle (Titanic Survival Prediction)

### ✅ Stage 1: Data Ingestion & Cleaning
1. Download Titanic dataset from GitHub.
2. Upload it to your S3 bucket using SageMaker SDK.
3. Launch SageMaker **Data Wrangler** in Studio.
4. Connect to your S3 source and import the dataset.
5. Clean null values (drop or impute).
6. Encode `Sex`, `Embarked`, and other categorical variables.
7. Normalize `Fare`, `Age`.
8. Save the cleaned data to S3 or register it to Feature Store.

🧪 Code Reference: See notebook section **“Stage 1 – Data Preparation”**

---

### ✅ Stage 2: Model Development
1. Open SageMaker Studio notebook.
2. Perform Exploratory Data Analysis (EDA) with Seaborn and Pandas.
3. Visualize correlations, distributions, and identify features.
4. Use **JumpStart** to run sample models (optional).
5. Launch **Autopilot** to test AutoML pipelines.
6. Evaluate candidate model accuracy, precision, recall.

🧪 Code Reference: See notebook section **“Stage 2 – Model Development”**

---

### ✅ Stage 3: Training & Hyperparameter Tuning
1. Choose **XGBoost** or custom training script.
2. Set up Estimator in SageMaker.
3. Use **Pipe Mode** or **File Mode** to load data from S3.
4. Configure and launch a **Training Job** on `ml.m5.large`.
5. Define hyperparameter ranges for tuning.
6. Run a **Hyperparameter Tuner** to find optimal configuration.
7. Use **Experiments** to track trials and metadata.
8. Integrate **Debugger** to monitor training metrics and avoid overfitting.

🧪 Code Reference: See notebook section **“Stage 3 – Model Training & Optimization”**

---

### ✅ Stage 4: Deployment
1. Register best model to **SageMaker Model Registry**.
2. Deploy the model to a real-time **SageMaker Endpoint**.
3. Create predictor and test prediction requests with sample JSON or array input.
4. For batch predictions, use **Batch Transform** with CSV from S3.
5. Confirm inference latency and success metrics.

🧪 Code Reference: See notebook section **“Stage 4 – Deployment”**

---

### ✅ Stage 5: Monitoring & Explainability
1. Enable **Model Monitor** for real-time endpoint.
2. Create a monitoring schedule to capture data and statistics.
3. Use **Clarify Processor** to run SHAP explainability jobs.
4. Analyze bias across gender, class, or age fields.
5. Output all reports to **S3**.
6. View metrics and logs in **CloudWatch** for alerts.

🧪 Code Reference: See notebook section **“Stage 5 – Monitoring & Explainability”**

---

### ✅ Stage 6: Automation & Security
1. Build a **SageMaker Pipeline** for end-to-end orchestration:
   - Data Wrangler → Processing → Training → Evaluation → Deployment
2. Use **Step Functions** to trigger re-training cycles (e.g., weekly).
3. Create and attach **IAM roles** for least-privilege access.
4. Configure **VPC** for isolated compute resources.
5. Apply **KMS** for encryption of data at rest.
6. Enable **GuardDuty** and **CloudTrail** for logging and threat detection.

🧪 Code Reference: See notebook section **“Stage 6 – Automation & Security”**

---
## 📜 License

MIT License — free to use, adapt, and improve.

---
 
> ✉️ [Open an issue or contact me on LinkedIn](https://www.linkedin.com/in/sogah)  
> ⭐ Star this repo to follow updates!
