# IBM-Project

---

## 📌 Problem Statement

The PMGSY program has multiple sub-schemes (e.g., PMGSY-I, PMGSY-II, RCPLWEA), each with distinct funding rules and implementation criteria. Manually classifying thousands of road and bridge projects is time-consuming and error-prone.

The goal of this project is to build a **multi-class classification model** that can automatically predict the correct **PMGSY_SCHEME** based on physical and financial project characteristics.

---

## 📊 Dataset

**Source:** [AI Kosh – Government of India](https://aikosh.indiaai.gov.in/web/datasets/details/pradhan_mantri_gram_sadak_yojna_pmgsy.html)

**Key Features:**
- `STATE_NAME`, `DISTRICT_NAME`
- `NO_OF_ROAD_WORK_SANCTIONED`
- `LENGTH_OF_ROAD_WORK_SANCTIONED`
- `NO_OF_BRIDGES_SANCTIONED`
- `COST_OF_WORKS_SANCTIONED`
- `NO_OF_ROAD_WORKS_COMPLETED`
- `EXPENDITURE_OCCURED`
- and others...

**Target Variable:**  
- `PMGSY_SCHEME` (multi-class)

---

## ⚙️ Technologies Used

- IBM Watsonx.ai & AutoAI
- IBM Cloud Machine Learning Deployment


---

## 🚀 Output

- Model deployed on IBM Cloud with a public REST endpoint
- Achieved **92.4% accuracy** using XGBoost classifier
- Ready for real-time classification and integration into dashboards

---
