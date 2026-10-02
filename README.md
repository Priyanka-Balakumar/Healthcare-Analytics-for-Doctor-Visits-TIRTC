# Healthcare Analytics for Doctor Visits

A comprehensive exploratory data analysis and patient behavior profiling project developed as part of the **TIRTC , VOIS & Edunet Foundation Internship** program.

---

## 📌 Project Overview
Healthcare utilization and patient doctor visits are influenced by a combination of demographic factors, financial status, illness severity, and underlying chronic health conditions. As a result, medical consultation rates and healthcare resource demands can vary significantly from one patient profile to another.

However, raw patient data does not clearly explain how these factors interact to drive doctor visits or what underlying patterns characterize high-utilization patients. 

This project performs an end-to-end Exploratory Data Analysis (EDA) on a healthcare dataset comprising 5,190 patient records to investigate patient behavior, identify meaningful patterns, trends, relationships, and variations in doctor visits, illnesses, and demographics within the available data.

---

## 🛠️ Tech Stack & Libraries Used
* **Programming Language:** Python
* **Data Manipulation & Analysis:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Development Environment:** Google Colab / Jupyter Notebook
* **Version Control:** Git & GitHub

---

## 📊 Key Analytical Steps & Features Explored
1. **Data Preprocessing & Cleaning:** Inspected and verified dataset structure (5,190 rows, 13 columns), confirming zero missing values and zero duplicate records. Removed redundant index columns.
2. **Univariate Analysis:** Evaluated distributions of doctor visits, illness counts, age, and income brackets. Discovered that the majority of patients record zero visits, while illness counts heavily concentrate between 0 and 2.
3. **Bivariate Analysis:** Investigated relationships such as age vs. doctor visit frequency and mean illness count by visit frequency, showing that high-utilization patients present with higher average underlying health complications.
4. **Outlier Investigation:** Utilized Interquartile Range (IQR) box plots to identify right-skewed distributions and upper-bound outliers across visit frequencies, activity reduction days (`reduced`), and health metrics.
5. **Multivariate & Subgroup Analysis:** Combined demographic, clinical, and financial features to isolate high-need patient archetypes and chronic condition subgroups.
6. **Correlation Matrix Heatmap:** Mapped linear interdependencies across numerical variables, highlighting strong associations between illness counts, activity reduction days, and medical consultation demands.

---

## 📂 Repository Structure
```text
📦 Healthcare-Analytics-Doctor-Visits
│
├── 📜 README.md                     # Project Documentation
├── 📓 Healthcare_Analytics_EDA.ipynb  # Main Jupyter Notebook with code & visualizations
└── 📄 requirements.txt              # Required Python packages
