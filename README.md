# ML & AI Assignments — YDTA Program

A collection of data analysis and Python programming notebooks completed during my AI & Machine Learning training at the **Yabatech Skills Development Center(SDC) (YDTA)**, facilitated by **Mr. Shuaib B. A.**

---

## About This Repo

This repository documents my hands-on learning journey through the YDTA Data Analysis & AI pre-coding program. Each notebook represents a real assignment — from cleaning messy datasets to visualising patterns that inform machine learning models.

**Tools & Libraries Used**

- Python 3
- Jupyter Notebook
- pandas, NumPy, Matplotlib

---

## Notebooks

### diabetes_analysis.ipynb

**Dataset:** [Pima Indians Diabetes Dataset](https://www.kaggle.com/datasets/mathchi/diabetes-data-set) — originally collected by the National Institute of Diabetes and Digestive and Kidney Diseases (NIDDK)

What I did:
- Loaded and inspected 768 patient records across 8 medical features
- Ran `.describe()` for statistical profiling
- Checked for missing and null values — dataset came back clean
- Plotted Age vs Glucose by Diabetes Outcome using a scatter plot in Matplotlib
- Found that diabetic patients (Outcome = 1) cluster noticeably higher on the glucose axis

> This dataset is one of the most studied in medical ML research. Models trained on it have achieved up to 98% accuracy in predicting diabetes onset.

---

### sales_record_analysis.ipynb

**Dataset:** sales_records_data.csv (cleaned version: sales_records_cleaned.xlsx)

What I did:
- Cleaned and profiled a sales dataset with multiple categorical columns
- Identified missing values across columns using a bar chart with a 5% threshold line
- Checked unique values in categorical columns — Gender, Region, Product Category, Payment Method, Sales Rep
- Detected and counted fully duplicate rows

---

### finance_transaction_analysis.ipynb

**Dataset:** Financial transactions dataset

What I did:
- Performed exploratory data analysis on financial transaction records
- Cleaned and structured data for further analysis
- Summarised key statistics and distributions

---

### contact.ipynb

A Python fundamentals exercise — building a contact and phonebook system using lists and dictionaries, with user input handling and loop-based output.

---

## How to Run

```bash
git clone https://github.com/coderhema/ML-AI-Assignments.git
cd ML-AI-Assignments
jupyter notebook
```

For the diabetes notebook, download the dataset from [Kaggle](https://www.kaggle.com/datasets/mathchi/diabetes-data-set) and place `diabetes.csv` in the root folder before running.

---

## Author

**Tolulope Timothy Olugbemi**  
Full-Stack Developer & Generative AI Engineer  
ND2 Computer Science — Yaba College of Technology

[LinkedIn](https://linkedin.com/in/timothyolu) · [Portfolio](https://coderhema.vercel.app) · [GitHub](https://github.com/coderhema)

---

*This repo is actively updated as the program progresses.*
