# 🏥 Healthcare Analytics: Stroke Risk Factor & Clinical EDA

An Exploratory Data Analysis project investigating clinical, demographic, and lifestyle determinants associated with cerebrovascular stroke events using patient health records.

---

## 📌 Project Overview

According to the World Health Organization (WHO), stroke is the second leading cause of death globally, responsible for approximately 11% of total deaths. Early identification of modifiable risk factors (e.g., blood glucose levels, hypertension, body mass index) and non-modifiable demographic markers (age, cardiovascular history) is critical for preventative medicine. This project performs comprehensive statistical analysis and data visualization on 5,100+ clinical patient records to evaluate stroke predictors.

---

## 📊 Dataset Overview

The dataset (`healthcare-dataset-stroke-data.csv`) includes 11 clinical and demographic attributes:

* **Patient Demographics:** `gender`, `age`, `ever_married`, `work_type` (Private, Self-employed, Govt_job, Children, Never_worked), `residence_type` (Urban vs. Rural).
* **Clinical Conditions:** `hypertension` (0 = No, 1 = Yes), `heart_disease` (0 = No, 1 = Yes).
* **Biometric & Lifestyle Markers:** `avg_glucose_level` (mg/dL), `bmi` (Body Mass Index), `smoking_status` (formerly smoked, never smoked, smokes, Unknown).
* **Target Outcome:** `stroke` (1 if patient had a stroke, 0 otherwise).

---

## 🔍 Key Findings & Clinical Insights

1. **Age as the Primary Risk Factor:**
   * Stroke incidence increases sharply in cohorts aged 55 and older. While younger populations exhibit low stroke frequency, comorbid conditions (hypertension and elevated glucose) drastically amplify risk even in mid-career adults.

2. **Glucose Level & Cardiovascular Interactions:**
   * Patients exhibiting elevated average glucose levels (>140 mg/dL) alongside pre-existing hypertension or heart disease demonstrate substantially higher stroke rates compared to normoglycemic peers.

3. **Work Type & Lifestyle Correlations:**
   * Self-employed and private sector cohorts exhibit higher reported levels of hypertension and heart conditions compared to government workers and non-working groups, highlighting the potential influence of occupational stress and sedentary habits.

4. **Residence Type Analysis:**
   * Comparative evaluation between Urban and Rural cohorts shows relatively minor differences in stroke prevalence, indicating that physiological and behavioral health metrics outweigh geographical classification alone.

---

## 📈 Visualizations in the Notebook

* **Demographic Proportions:** Pie charts depicting patient gender distribution and marital status.
* **Work Type Distribution:** Count plots of occupational backgrounds across the sample population.
* **Age & Gender Distributions:** FacetGrid comparative histograms tracking patient age dispersion by gender.
* **Biometric Comparisons:** Bar plots evaluating average BMI and blood glucose levels across marital status cohorts.
* **Comorbidity Analysis:** Grouped bar charts examining hypertension and heart disease prevalence by employment type and residence.
* **Correlation Heatmap:** Multi-variable correlation matrix examining health biomarkers against stroke occurrence.

---

## 🛠️ Tech Stack

* **Language:** Python 3.x
* **Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`, `jupyter`
* **Dataset:** `healthcare-dataset-stroke-data.csv`

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/Zelarq/stroke-risk-prediction-eda.git
cd stroke-risk-prediction-eda
```

### 2. Set Up Virtual Environment
```bash
python -m venv venv
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook
```bash
jupyter notebook storke_dataanalysis_project.ipynb
```

---

## 👤 Author

* **Sayanth N K**
* GitHub: [@Zelarq](https://github.com/Zelarq)
* Email: [sayanthnk32@gmail.com](mailto:sayanthnk32@gmail.com)
