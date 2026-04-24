# Final-Year-Project-Aslam1
Predicting Breast Cancer Recurrence
Identifying High-Risk Patients Using Machine Learning Classifiers
📌 Project Overview

This project focuses on predicting breast cancer recurrence (relapse) using machine learning techniques applied to clinical data. Early identification of high-risk patients can support better treatment planning and improve survival outcomes.

The study uses multiple classification models and evaluates them based on key performance metrics, with special emphasis on recall (sensitivity) to minimize false negatives.

🎯 Objectives
Predict Relapse Free Status (recurrence vs non-recurrence)
Identify patients at high risk of cancer recurrence
Compare multiple machine learning models
Optimize model performance using hyperparameter tuning
📊 Dataset
Source: METABRIC Breast Cancer Dataset
Records: 15,054 patients
Features: 34 clinical and biological attributes
Includes:
Demographics (Age, Sex)
Tumor characteristics (Size, Stage, Grade)
Treatment details (Chemotherapy, Hormone Therapy)
Survival and relapse information
⚙️ Technologies Used
Python
Pandas, NumPy
Matplotlib, Seaborn
Scikit-learn
Imbalanced-learn (SMOTE)
Optuna (Hyperparameter tuning)
🔍 Project Workflow
1. Data Loading
Dataset loaded using pandas.read_csv()
2. Exploratory Data Analysis (EDA)
Dataset structure and summary statistics
Missing value analysis
Target variable distribution
Correlation heatmap of numerical features
3. Data Preprocessing
✔ Handling Missing Values
Numerical features → filled with median
Categorical features → filled with mode
✔ Encoding
Categorical variables converted to numeric using Label Encoding
✔ Feature & Target Split
Features (X) and target variable (y) separated
✔ Handling Imbalanced Data
Applied SMOTE (Synthetic Minority Oversampling Technique)
✔ Feature Scaling
Standardization using StandardScaler
4. Model Training

The following models were implemented:

Logistic Regression
Random Forest Classifier
Support Vector Machine (SVM)
5. Model Evaluation

Each model was evaluated using:

Accuracy
Precision
Recall (Sensitivity) ⭐ (Primary focus)
F1-score
ROC-AUC score
Confusion Matrix
ROC Curve
6. Model Comparison
Performance metrics summarized in a DataFrame
Visualization using bar plots for comparison
7. Hyperparameter Tuning
Used Optuna for automated optimization
Tuned:
Random Forest (depth, estimators)
Logistic Regression (regularization)
SVM (kernel, C parameter)
Objective: maximize recall score
📈 Key Insights
Handling class imbalance significantly improved recall
Ensemble methods like Random Forest showed strong performance
SVM performed well after tuning with optimized kernel parameters
Recall is prioritized to reduce false negatives (missed high-risk patients)
🚀 How to Run the Project
1. Clone Repository
git clone https://github.com/your-username/breast-cancer-recurrence.git
cd breast-cancer-recurrence
2. Install Dependencies
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn optuna
3. Run the Notebook / Script
Open Jupyter Notebook or Google Colab
Update dataset path:
df = pd.read_csv("your_dataset_path.csv")
📁 Project Structure
├── data/
│   └── Breast_Cancer_METABRIC_Epic_Hospital.csv
├── notebooks/
│   └── model_analysis.ipynb
├── README.md
└── requirements.txt
⚠️ Important Notes
SMOTE is applied only on training data to avoid data leakage
Scaling is done after train-test split
ROC-AUC is applicable for binary classification
🧪 Future Improvements
Use deep learning models (ANN, CNN)
Feature selection techniques
Deployment using Flask/Streamlit
Integration with clinical decision systems
👨‍🎓 Author
Your Name
University Name
Course / Project Title
📜 License

This project is for academic and research purposes only.

If you want, I can also:

Make a short 1-page README (for quick submission)
Add badges (accuracy, license, Python version)
Or tailor it exactly to your university format 👍
