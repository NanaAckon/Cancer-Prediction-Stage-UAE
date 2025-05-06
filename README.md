# Cancer-Prediction-Stage-UAE
EDA, ML Model And Clustering Analysis On Cancer Patients in UAE


# Cancer Patient Analysis and Predictive Modeling (UAE Dataset)

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Jupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange)

A comprehensive analysis of cancer patient data from the UAE, featuring exploratory data analysis, predictive modeling for cancer staging, and patient clustering for personalized treatment strategies.

![XL-1170x780](https://github.com/user-attachments/assets/7285f1d4-d7ac-437b-8964-b8c7042f433e)


## 📌 Project Overview

This project analyzes anonymized cancer patient records from UAE hospitals to:
- Identify trends in recovery rates and risk factors
- Predict cancer stages (I-IV) using machine learning
- Discover patient subgroups through clustering analysis

**Key Features:**
- EDA with temporal and demographic insights
- Random Forest classifier (85% accuracy)
- K-means clustering revealing 4 distinct patient groups
- Interactive visualizations

## 🚀 Installation

1. **Clone Repository**
```bash
git clone https://github.com/yourusername/cancer-analysis-uae.git
cd cancer-analysis-uae

pip install -r requirements.txt
```

## Requirements:

- Python 3.8+

- pandas

- scikit-learn

- matplotlib

- seaborn

- jupyter

## 🔍 Data Sources
Primary Dataset:
_cancer_dataset_uae.csv (10,000 anonymized records)
Features Include:

- Demographic data (Age, Gender, Nationality)

- Medical history (Cancer Type, Stage, Comorbidities)

- Treatment details (Hospital, Treatment Type)

- Lifestyle factors (Smoking Status)

💻 Usage
Run Jupyter Notebook

bash
jupyter notebook notebooks/ML_on_Cancer.ipynb
Main Components

Data preprocessing pipeline

EDA visualizations

Random Forest classifier

K-means clustering implementation

PCA visualization

Note: Update file paths in the notebook if needed

## 📊 Key Results
#### EDA Highlights
- 23% higher recovery rate in non-smokers
![image](https://github.com/user-attachments/assets/1d485842-8a7b-42e3-9aed-74ecea8bf8ab)

- Leukemia shows highest recovery rate (68%)
![image](https://github.com/user-attachments/assets/75c73d49-abd1-4b77-8195-57ffe4fffb69)

- 15% YoY improvement in recovery rates since 2015
![image](https://github.com/user-attachments/assets/06e2adba-0562-49f7-98a1-0c2fa0332b58)


### Predictive Model

| Metric    | Score |
|-----------|-------|
| Accuracy  | 0.85  |
| Precision | 0.83  |
| Recall    | 0.84  |


### Top Predictive Features:

- Age (0.32 feature importance)

- Cancer Type (0.28)

- Weight/Height Ratio (0.18)


🔍 **Key Findings**  
### Clustering Analysis Results

| Cluster | Avg Age | Predominant Cancer | Smoking Status | Comorbidities |
|---------|---------|--------------------|----------------|----------------|
| 0       | 36.75   | Leukemia           | Non-Smoker     | None           |
| 1       | 68.45   | Ovarian            | Non-Smoker     | None           |
| 2       | 71.68   | Pancreatic         | Non-Smoker     | None           |
| 3       | 37.25   | Ovarian            | Non-Smoker     | None           |


## Clustering Insights
#### Identified Groups:

- Young Leukemia Patients (36±5 years)

- Elderly Ovarian Cancer (68±8 years)

- Late-stage Pancreatic (72±6 years)

- Young Ovarian Cases (37±4 years)

## 🧠 Key Insights
- Age is the strongest predictor of cancer stage

- Non-smoking paradox in high-risk groups warrants investigation

- Distinct treatment response patterns across clusters

- Data quality opportunities in comorbidity reporting

---

- 📊 Critical Insights
- Age Disparity: 20-year age gap between youngest (Cluster 0) and oldest (Cluster 2) groups

- Ovarian Cancer: Appears in both young (37) and elderly (68) clusters

- Data Paradox: All clusters show non-smokers despite known smoking-cancer links

- Comorbidity Gap: No reported comorbidities across all groups

---

## 🏥 Clinical Recommendations
- Prioritize genetic screening for young leukemia patients

- Develop age-specific diagnostic protocols

- Implement cluster-based treatment pathways

- Enhance comorbidity data collection

## 🤝 Contributing
- Fork the repository

- Create your feature branch (git checkout -b feature/yourfeature)

- Commit changes (git commit -m 'Add some feature')

- Push to branch (git push origin feature/yourfeature)

- Open a Pull Request

## 📄 License
- Distributed under MIT License. See LICENSE for details.

## 📧 Contact
[Joseph Prince Nana-Ackon] - [jprince364@gmail.com]
Project Link: (https://github.com/NanaAckon/Cancer-Prediction-Stage-UAE)
