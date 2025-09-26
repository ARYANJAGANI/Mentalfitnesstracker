# 🧠 Mental Fitness Tracker

AICTE–IBM AI internship project applying supervised machine learning (Linear Regression, Random Forest) to model **mental fitness burden across countries** from public health indicators.

---

## 🔍 Overview
This project analyzes how mental and substance use disorders contribute to disease burden worldwide. Using country-level datasets, it builds regression models to improve understanding of trends and enable data-driven forecasting.

---

## ✨ Features
- End-to-end analysis in a **Jupyter Notebook**  
- Data preprocessing and cleaning of country-level health datasets  
- Regression models: **Linear Regression** (baseline) and **Random Forest** (non-linear)  
- Evaluation metrics: MAE, RMSE, R²  
- Visualizations for insights and comparisons across countries  

---

## 📂 Project Structure
Mentalfitnesstracker/
├─ MENTAL_HEALTHTRACKER_.ipynb # Main analysis notebook
├─ mental-and-substance-use-as-share-of-disease.csv
├─ prevalence-by-mental-and-substance-use-disorder.csv
└─ AICTE IBM PPT.pptx # Presentation slides
---

## 🧰 Tech Stack
- Python (Jupyter Notebook)
- Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn
- Data: WHO / Global Burden datasets (CSV format)

---

## ⚙️ Setup & Installation

1. Clone the repo:
   ```bash
   git clone https://github.com/ARYANJAGANI/Mentalfitnesstracker.git
   cd Mentalfitnesstracker
2. Create & activate a virtual environment (recommended):

python -m venv .venv
source .venv/bin/activate   # Linux / macOS
.venv\Scripts\activate      # Windows
3. Intsall Dependencies
pip install -r requirements.txt
4. Launch Jupyter Notebook
jupyter notebook MENTAL_HEALTHTRACKER_.ipynb


## 🚀 How to Use

Run the notebook step-by-step:

Load CSV data

Clean & preprocess

Train Linear Regression and Random Forest models

Evaluate using metrics

Visualize and interpret results

## 📊 Results

Random Forest improves performance over Linear Regression by capturing non-linear patterns.

Insights can guide better understanding of global mental health burden.

Presentation slides (AICTE IBM PPT.pptx) summarize the project.

## 🛡️ Limitations

Dataset is limited to country-level aggregates (not individual data).

Results are correlational; causation cannot be inferred.

Model accuracy depends on data quality and completeness.

## 🙌 Acknowledgments

Developed under the AICTE–IBM AI Internship Program.

Data sources: Global health burden datasets.
