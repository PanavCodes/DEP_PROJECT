# 🧠 Data Extraction & Processing Project — Payment Card Fraud Detection (2025)

## 📘 Overview
This project focuses on **data extraction, cleaning, processing, and visualization** using the [Payment Card Fraud Detection Dataset (2025)](https://www.kaggle.com/datasets/pratyushpuri/payment-card-fraud-detection-with-ml-models-2025/data).

The main objective is to analyze payment transaction data, identify key patterns of fraudulent activity, and develop a reliable **machine learning pipeline** to classify transactions as *fraudulent* or *legitimate*.  
In addition, a **Power BI dashboard** provides an interactive visualization of fraud trends and model results, accompanied by a **comprehensive analytical report**.

---

## 📂 Repository Structure

| File / Folder | Description |
|----------------|--------------|
| `DEP_Mini.ipynb` | Jupyter Notebook containing the entire project workflow — data extraction, preprocessing, EDA, model building, and evaluation. |
| `DEP_Mini.pbix` | Power BI Dashboard visualizing transaction patterns, fraud detection metrics, and feature importance. |
| `DEp_Mini.pdf` | Final report summarizing methodologies, visualizations, and conclusions. |
| `README.md` | Project documentation file (this one). |

---

## ⚙️ Tools & Technologies

**Languages & Libraries**
- Python (Jupyter Notebook)
  - `pandas` — Data manipulation  
  - `numpy` — Numerical operations  
  - `matplotlib`, `seaborn` — Data visualization  
  - `scikit-learn` — Machine Learning models & evaluation  

**Visualization & Reporting**
- Power BI — Interactive dashboards and insights  

**Dataset Source**
- [Kaggle: Payment Card Fraud Detection with ML Models 2025](https://www.kaggle.com/datasets/pratyushpuri/payment-card-fraud-detection-with-ml-models-2025/data)

---

## 🔍 Project Workflow

### 1. Data Extraction
- Downloaded dataset from Kaggle.  
- Loaded the data into Jupyter Notebook using `pandas`.

### 2. Data Cleaning & Preprocessing
- Handled missing values and data inconsistencies.  
- Encoded categorical variables for model readiness.  
- Normalized numerical columns to improve model performance.

### 3. Exploratory Data Analysis (EDA)
- Investigated transaction patterns by type and amount.  
- Visualized fraud vs. non-fraud transaction distribution.  
- Identified feature correlations and outlier behavior.

### 4. Model Building
- Implemented multiple classification algorithms:
  - Logistic Regression  
  - Random Forest Classifier  
  - XGBoost  
- Performed train-test split and model evaluation.  
- Compared models using **Accuracy**, **Precision**, **Recall**, and **F1-Score**.

### 5. Visualization & Reporting
- Built a **Power BI Dashboard** to present fraud insights interactively.  
- Compiled a **final PDF report** summarizing workflow, results, and recommendations.

---

## 📊 Power BI Dashboard Features
- Transaction and fraud detection trends over time  
- Fraud vs. non-fraud transaction comparison  
- Feature-wise fraud likelihood visualization  
- Model performance comparison charts  
- Interactive filters for transaction types and time periods  

---

## 🧩 Key Insights
- Fraudulent transactions form a **minority class** but show clear behavioral patterns.  
- Feature scaling and data balancing techniques improved prediction accuracy.  
- **Random Forest** delivered the best trade-off between recall and precision.  
- Visualization dashboards help identify suspicious transaction clusters effectively.  

---

## 🚀 How to Run the Project

1. **Clone the Repository**
   ```bash
   git clone https://github.com/<your-username>/Data-Extraction-Processing.git
   cd Data-Extraction-Processing
