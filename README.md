<h1 align="center">Hi, I'm Hamza Alhabashnah 👋</h1>
 
<p align="center">
  <b>Machine Learning Engineer focused on building production-ready recommendation systems and scalable ML pipelines.</b>
</p>
<p align="center">
  <a href="https://linkedin.com/in/hamza-kheir"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:hamzaalhabashnah@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://github.com/HamzaKheir04"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
</p>
---
 
## 👨‍💻 About Me
 
I'm a Data Science & AI graduate from Mu'tah University (GPA: 3.6/4.0, 2026) with hands-on experience building and deploying end-to-end machine learning systems.
 
- 🔭 **Led ML development** on a Hybrid Recommendation System using a sampled subset of the 100M+ Alibaba UserBehavior dataset, achieving a **5.6× improvement in F1@5** over a popularity baseline
- 🚀 Deployed ML models to production using **Flask REST APIs**, Firebase, and Render
- 📊 Experienced with large-scale data pipelines — cleaned and analyzed **1.48M+ real-world records**
- 🌍 Based in Jordan &nbsp;|&nbsp; Willing to Relocate
---
 
## 🎯 Featured Skills
 
`Machine Learning` `Recommendation Systems` `Feature Engineering` `Data Pipelines`
`Large-scale Data Processing` `Deployment` `Hyperparameter Tuning`
 
---
 
## 🛠️ Tech Stack
 
**Languages**
 
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
 
**Machine Learning & Data**
 
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-AA4A44?style=flat-square)
![LightGBM](https://img.shields.io/badge/LightGBM-2BAF2B?style=flat-square)
![CatBoost](https://img.shields.io/badge/CatBoost-FFCC00?style=flat-square&logoColor=black)
![Optuna](https://img.shields.io/badge/Optuna-4A90D9?style=flat-square)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
 
**Deployment & Tools**
 
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=black)
 
---
 
## 🚀 Featured Projects
 
### 🤝 [Donation Platform — AI Recommendation & Assistant System](https://github.com/HamzaKheir04/donation-rec-api)
> Hybrid recommendation engine deployed as a production REST API — Team Project
 
**Led the machine learning development within a multidisciplinary team**, owning model design, evaluation, and deployment while collaborating on backend integration.
 
```
Alibaba/Taobao Dataset (100M+ interactions)
              ↓
     Smart Sampling Pipeline
              ↓
   Hybrid Recommender Engine
   ┌──────────────────────────────────────┐
   │  Collaborative (TruncatedSVD)        │
   │  +  Content-Based Filtering          │
   └──────────────────────────────────────┘
              ↓
        Flask REST API
              ↓
     Firebase Integration
              ↓
    Client (Real-time Recommendations)
```
 
- Built a **Hybrid Recommendation System** (Collaborative Filtering with TruncatedSVD + Content-Based) on a sampled subset of the 100M+ Alibaba/Taobao UserBehavior dataset, achieving a **5.6× improvement in F1@5** over a popularity-based baseline (0.2015 vs. 0.0357)
- Designed a **sampling pipeline** that reduced data sparsity while preserving representative user-item interactions for model training at scale
- Evaluated using **time-based validation** and baseline comparison to assess recommendation relevance and personalization quality
- Deployed as a **Flask REST API** on Render with Firebase integration for real-time cold-start recommendations
- Developed a **bilingual AI Donation Assistant** using DeepSeek API with intent-based category routing and recommendation-aware responses
`Python` `TruncatedSVD` `Flask` `Firebase` `DeepSeek API` `Render`
 
---
 
### 🔬 [Skin Lesion Classification — Handcrafted Features + Classical ML](https://github.com/HamzaKheir04/skin-lesion-classifier)
> End-to-end pattern recognition pipeline for skin cancer detection
 
- Classified **3,297 dermoscopic images** (benign vs. malignant) using 44 handcrafted features per image (HSV histograms, LBP texture, GLCM, statistical moments)
- Benchmarked **6 classical classifiers** (Random Forest, SVM, AdaBoost, LDA, Logistic Regression, KNN)
- Achieved best **AUC of 0.943** with Optuna-tuned Random Forest using handcrafted image descriptors and classical ML methods
- Applied rigorous ML practices: no data leakage, stratified 5-fold CV, class imbalance handling
`Python` `Scikit-Learn` `OpenCV` `Scikit-Image` `Optuna` `GLCM` `LBP`
 
---
 
### 🌦️ [Sub-Seasonal Weather Forecasting](https://github.com/HamzaKheir04/WiDS-Datathon-2023)
> End-to-end ML regression pipeline on NOAA climate data
 
- Engineered weather and climate features from NOAA observations before benchmarking gradient boosting models
- Forecasted sub-seasonal temperatures (15–45+ days ahead) with rigorous train/validation/test separation to prevent data leakage
- Benchmarked **XGBoost, CatBoost, and LightGBM** with Optuna hyperparameter optimization, achieving best test **RMSE of 0.284**
`Python` `XGBoost` `CatBoost` `LightGBM` `Optuna` `Scikit-Learn`
 
---
 
### 🚗 [NYC Motor Vehicle Collisions Analysis](https://github.com/HamzaKheir04/NYC-Collisions-Analysis)
> Large-scale EDA and data cleaning on 2.2M+ real-world records
 
- Built **reusable preprocessing pipelines** for large-scale structured data cleaning and validation
- Cleaned and analyzed **1.48M+ records** (from 2.2M raw) from NYC Open Data, handling missing values, correcting data types, and standardizing inconsistent fields
- Identified **Driver Inattention/Distraction** as the leading crash factor (280K+ incidents) and found **23.5% of crashes resulted in injuries**
- Exported validated datasets in JSON and Parquet formats
`Python` `Pandas` `NumPy` `Statistical Analysis` `EDA`
 
---
 
## 🌱 Currently Learning
 
| Tool | Why |
|------|-----|
| 🐳 Docker | Containerizing ML models for portable deployment |
| ☁️ AWS | Cloud infrastructure for scalable ML pipelines |
| ⚙️ MLflow | Experiment tracking and model lifecycle management |
| 🚀 CI/CD | Automating testing and deployment workflows |
 
> *As I learn each tool, it moves from here to the Tech Stack above.*
 
---
 
## 🎓 Education & Certifications
 
- 🎓 **B.Sc. in Data Science and Artificial Intelligence** — Mu'tah University, Jordan (2026) | GPA: 3.6/4.0
- 📜 **Python Essentials & Data Science Essentials with Python** — Cisco Networking Academy (2026)
- 🏢 **AI & Data Science Field Trainee** — SHAI Company, Amman (90-hour onsite program, 2025)
---
 
<p align="center">
  📌 Open to &nbsp;<b>Junior ML Engineer</b>&nbsp;·&nbsp;<b>Junior Data Scientist</b>&nbsp;·&nbsp;<b>AI Engineer</b>&nbsp; roles &nbsp;|&nbsp; Willing to Relocate
</p>
 
