# CaseStudy-Automatidata
# 🚖 Automatidata: Predicting Generous Tippers (Course 6 ML Project)

## 📖 Project Overview
I completed the **Course 6 End-of-Course Project** in the Google Advanced Data Analytics program.  
In this project, I acted as a **data professional** at **Automatidata**, a data consulting firm.  

My client, the **New York City Taxi & Limousine Commission (TLC)**, requested a machine learning model to **predict customers who will leave generous tips (≥20%)**.  
The model is intended to help drivers optimize their earnings without unfairly denying rides to customers.

---

## 🏢 Background
**Client:** New York City Taxi & Limousine Commission (TLC)  
- Manages ~200,000 taxi and for-hire vehicle licenses  
- Handles ~1 million trips daily  

**Business Goal:**  
Use data-driven insights to help taxi drivers maximize tips and revenue.  

**Original Request:**  
Predict customers who will **not** leave tips.  

**Ethical Issue:**  
- Predicting non-tippers could result in drivers avoiding certain passengers  
- This could lead to **discrimination** and **reduced accessibility** to taxi services  

**Adjusted Objective:**  
I decided to **predict generous tippers instead**, which:  
- Motivates drivers without excluding any passengers  
- Supports fair and ethical business practices  

---

## 🎯 Project Goals
1. **Ethical Analysis:**  
   - Evaluated the impact and risks of predicting non-tippers  
   - Modified the objective to predict **generous tippers**  

2. **Feature Engineering:**  
   - Selected, transformed, and prepared features for modeling  
   - Considered pickup/dropoff times, locations, fare amounts, and payment methods  

3. **Machine Learning Modeling:**  
   - Built **tree-based classification models** (Decision Trees, Random Forests)  
   - Evaluated models using **accuracy, precision, recall, F1-score, and ROC-AUC**  

4. **Deliver Insights:**  
   - Provided recommendations to Automatidata and TLC stakeholders  
   - Summarized results in an **Executive Summary** for non-technical users  

---

## 📂 Project Structure
```plaintext
├── data/
│   └── taxi_data.csv                 # Synthetic TLC dataset
├── notebooks/
│   └── generous_tippers_model.ipynb  # Analysis and ML workflow
├── reports/
│   └── executive_summary.pdf         # Stakeholder-friendly summary
├── PACE_planner.pdf                  # Project planning document
└── README.md                         # Project overview (this file)
---


## 🛠 Tools & Skills
- **Python:** Pandas, NumPy, Matplotlib, Seaborn  
- **Machine Learning:** Scikit-learn (Decision Trees, Random Forest, Model Evaluation)  
- **Feature Engineering:** Feature selection, transformation, and encoding  
- **Classification Metrics:** Accuracy, Precision, Recall, F1-score, ROC-AUC  
- **Ethical ML Practices:** Aligning objectives to avoid harm and bias  

---


## 📈 Workflow (PACE Framework)
1. **Plan**  
   - Defined objectives and identified ethical concerns  
   - Adjusted modeling goal to focus on **generous tippers**  

2. **Analyze**  
   - Cleaned and explored taxi trip data  
   - Identified key features affecting tipping behavior  

3. **Construct**  
   - Engineered features for classification  
   - Built and evaluated **tree-based ML models**  

4. **Execute**  
   - Selected the best-performing model  
   - Delivered an **Executive Summary** to stakeholders  

---

## ✅ Key Takeaways
- Predicting **generous tippers** is a more **ethical and practical approach** than predicting non-tippers  
- **Tree-based models** are effective for binary classification on structured tabular data  
- Communicating findings differently for **technical** and **non-technical** audiences is critical  
- This project is **portfolio-ready**, demonstrating my end-to-end machine learning skills  

---

## ⚠️ Disclaimer
All data, characters, and scenarios in this project are **fictitious**.  
The dataset was **created for educational purposes** and does not represent actual NYC taxi rider behavior.

