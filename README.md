# 🧠 Stroke Prediction & Rehabilitation Outcomes

This project applies **machine learning and data analysis** to stroke prediction and rehabilitation outcomes.  
It is part of my research preparation for a Master's in **Neuroscience** with a focus on **neuroplasticity** and **stroke rehabilitation**.  

---

## 📌 Objectives
- Explore stroke risk factors and their correlations.
- Build predictive models for stroke occurrence.
- Evaluate model performance using clinical metrics.
- Discuss implications for **stroke rehabilitation** and **neuroplasticity**.

---

## 📊 Dataset
The dataset contains patient-level clinical features relevant to stroke (e.g., age, hypertension, glucose, BMI, smoking status).  
Target variable: **Stroke occurrence (yes/no)**.

---

## 🔬 Methods
1. **Data Preprocessing**  
   - Handling missing values and normalization.  
   - Feature encoding for categorical variables.  

2. **Exploratory Data Analysis (EDA)**  
   - Distribution of risk factors.  
   - Correlation analysis between clinical variables and stroke.  

3. **Modeling**  
   - Logistic Regression  
   - Random Forest Classifier  
   - Evaluation with **Accuracy, Precision, Recall, F1-score, ROC-AUC**.  

4. **Model Refinement**  
   - Train/test split to avoid overfitting.  
   - Hyperparameter tuning.  
   - Comparison of performance across models.  

---

## 📈 Key Results
- Identified top stroke risk predictors (age, hypertension, glucose levels, BMI).  
- Random Forest achieved higher ROC-AUC compared to baseline models.  
- Models demonstrated potential for **early intervention planning** in stroke rehabilitation.  

---

## 🧩 Relevance to Neuroscience
This project aligns with my academic interest in:  
- **Neuroplasticity** → Understanding how stroke recovery depends on modifiable risk factors.  
- **Rehabilitation** → Applying predictive models to design patient-specific rehabilitation strategies.  
- **Data Science in Neuroscience** → Leveraging machine learning to improve outcomes in neurological disorders.  

---

## 🚀 How to Run
### Requirements
- Python 3.x
- pandas, numpy, matplotlib, seaborn
- scikit-learn

### Run Notebook
```bash
jupyter notebook Stroke_Prediction_&_Rehabilitation_Outcomes.ipynb
