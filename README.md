# 🧠 Stroke Prediction & Rehabilitation Outcomes

This Beginner level project applies **machine learning and data analysis** to stroke prediction and rehabilitation outcomes.  
It is part of my research preparation for a Master's in **Neuroscience** with a focus on **neuroplasticity** and **stroke rehabilitation**.  

---

## 📌 Objectives
- Explore stroke risk factors and their correlations.
- Build predictive models for stroke occurrence.
- Evaluate model performance using clinical metrics.
- Discuss implications for **stroke rehabilitation** and **neuroplasticity**.

---

## 📊 Dataset
This project uses the [Stroke Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset) (Kaggle).  
It contains clinical variables such as age, hypertension, glucose, BMI, and smoking status, with stroke occurrence as the target label.

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
NB : code snippets from https://www.coursera.org/learn/data-analysis-with-python/home/info
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
## Acknowledgements
- Parts of the analysis workflow and code structure were adapted from IBM's "Data Analysis with Python" course. https://www.coursera.org/learn/data-analysis-with-python/home/info
- Dataset: [Stroke Prediction Dataset on Kaggle](https://www.kaggle.com/fedesoriano/stroke-prediction-dataset).


## 🚀 How to Run
### Requirements
- Python 3.x
- pandas, numpy, matplotlib, seaborn
- scikit-learn

### Run Notebook
```bash
jupyter notebook Stroke_Prediction_&_Rehabilitation_Outcomes.ipynb


