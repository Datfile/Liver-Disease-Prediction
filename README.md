🩺 Liver Disease Prediction
This project focuses on predicting liver disease using machine learning techniques. It leverages patient data to train and evaluate a classification model that can assist medical professionals in early diagnosis.

📁 Project Structure
├── Liverpatients.ipynb     # Jupyter notebook with EDA, preprocessing, and model
├── README.md               # Project documentation
├── liver_patient.csv       # (Expected) Dataset file
└── models/                 # (Optional) Trained models and artifacts
📊 Dataset

Attributes:

Age

Gender

Total Bilirubin

Direct Bilirubin

Alkaline Phosphotase

Alamine Aminotransferase

Aspartate Aminotransferase

Total Proteins

Albumin

Albumin and Globulin Ratio

Target: Liver disease diagnosis (1 = Yes, 0 = No)

🧠 ML Approach
Libraries Used:

pandas, numpy, seaborn, matplotlib

scikit-learn

Steps:

Exploratory Data Analysis (EDA)

Data Cleaning and Imputation

Label Encoding

Feature Scaling

Model Training (e.g., Logistic Regression, Random Forest)

Evaluation (Accuracy, Precision, Recall, Confusion Matrix)

✅ Results
Achieved 72% accuracy using XGBoost Model After hyperparametre tune

Confusion matrix and classification report included
