#  COVID-19 Data Analysis  

##  Project Overview  
This project analyzes a COVID-19 dataset containing patient symptoms, health conditions, travel/contact history, and infection status.  
The goal is to **explore patterns, visualize trends, and identify key risk factors** related to COVID-19.  

Using **Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)**, the dataset is cleaned, encoded, and visualized with multiple statistical and correlation plots.  

---

##  Dataset  
- **File name:** `Covid Dataset.csv`  
- **Main columns include:**  
  - Symptoms: *Breathing Problem, Fever, Dry Cough, Sore throat, Headache, Fatigue, Gastrointestinal*  
  - Medical history: *Asthma, Diabetes, Heart Disease, Hyper Tension, Chronic Lung Disease*  
  - Exposure: *Abroad travel, Contact with COVID Patient, Large Gathering, Public Exposed Places*  
  - Safety measures: *Wearing Masks, Sanitization from Market*  
  - Target: **COVID-19 (Positive / Negative)**  

---

##  Tools & Libraries  
- **Python**  
- **Pandas** – data cleaning & analysis  
- **NumPy** – numerical operations  
- **Matplotlib & Seaborn** – visualizations  
- **Scikit-learn** – Label Encoding categorical features  

---

##  Exploratory Data Analysis (EDA)  
✔ Missing values analysis (heatmap & summary table)  
✔ Distribution of COVID-19 positive/negative cases  
✔ Symptom correlation with COVID-19 status (e.g., Fever, Cough, Breathing Problem)  
✔ Safety measures (Wearing Masks, Sanitization) frequency analysis  
✔ Correlation heatmap between all features  

---

##  Key Visualizations  
- **Countplots** showing frequency of symptoms vs COVID status  
- **Pie chart** for overall COVID-19 positive vs negative cases  
- **Heatmaps** for missing values and feature correlations  
- **Histograms** for all features  

---
## Insights

- Breathing problems & fever are highly correlated with positive COVID cases.

- Contact with COVID patients and attending gatherings increase infection likelihood.

- Preventive measures (mask usage, sanitization) are strong indicators of lower infection rates.

- Few features show high correlation, which may help build a prediction mode
