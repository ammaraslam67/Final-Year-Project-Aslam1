# Final-Year-Project-Aslam1
**Overview**

The goal of this study is to employ machine learning algorithms on clinical data to predict breast cancer recurrence, or relapse. Early detection of high-risk individuals can facilitate more effective treatment planning and enhance survival rates.
In order to reduce false negatives, the study employs a variety of classification models and assesses them using important performance indicators, with a focus on recall (sensitivity).

**Goals**
Forecast Relapse-Free Status (recurrence vs. non-recurrence)
Determine which patients are most likely to experience a cancer recurrence.
Examine several machine learning models.
Use hyperparameter adjustment to maximise model performance.

**The dataset**
METABRIC Breast Cancer Dataset is the source.
Records: 15,054 individuals
Features: 34 biological and clinical characteristics
comprises:
Age and sex demographics
Features of the tumour (Size, Stage, Grade)
Details of the treatment (hormone therapy, chemotherapy)
Information on relapse and survival

**Technologies Used**
Python
Pandas, NumPy
Matplotlib, Seaborn
Scikit-learn
Imbalanced-learn (SMOTE)
Optuna (Hyperparameter tuning)

**Key Insights**
Recall was greatly enhanced by addressing class imbalance.
Random Forest and other ensemble techniques performed well.
After adjusting with ideal kernel values, SVM behaved effectively.
To lower false negatives (missing high-risk patients), recall is given top priority.

**Project Structure**
Data/
  Breast_Cancer_METABRIC_Epic_Hospital.csv
Notebooks/
  Topic_05_Jan_26_HyperParameter_final.ipynb
Readme.teXT

**Future Improvements**
Make use of deep learning models (ANN, CNN).
Techniques for choosing features
Using Flask/Streamlit for deployment
Combining clinical decision-making systems

👨‍🎓** Author**
Ammar Aslam
University of Hertfordshire
Title : Predicting Breast Cancer Recurrence: Identifying High Risk Patients Using Machine Learning Models
📜 License

This project is for academic and research purposes only.

