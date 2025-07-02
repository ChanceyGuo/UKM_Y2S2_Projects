ProjectA: Stroke Prediction with ML & DL

Project Overview
This project uses a Jupyter notebook to build and evaluate both traditional machine learning models and a simple neural network for predicting stroke risk.
Data comes from the Kaggle “Healthcare Stroke Dataset” (healthcare-dataset-stroke-data.csv).
Key steps include data cleaning, exploratory analysis, feature engineering, SMOTE balancing, model training and evaluation.

Files
.
├── README.md                                 Main overview file
├── Stroke_Prediction_with_ML_and_DL.ipynb    Main analysis and modeling notebook
├── data.zip                                  Contains healthcare-dataset-stroke-data.csv
└── requirements.txt                          Python dependencies

Setup & Usage
1. Unzip the data:
   unzip data.zip -d data
2. Install dependencies:
   pip install -r requirements.txt
3. Run the notebook:
   jupyter notebook Stroke_Prediction_with_ML_and_DL.ipynb
   Execute cells in order to reproduce data processing, model training, and results.

Main Results
- Traditional ML models (Logistic Regression, Random Forest, XGBoost) achieved test accuracies up to ~0.92 and F1-scores around 0.85.
- MLP neural network reached ~0.90 accuracy and ~0.82 F1-score on the test set.
- SMOTE balancing improved recall on the minority (stroke) class by approximately 15%.

(See the notebook for full performance tables, ROC curves, and confusion matrices.)



Author & Contact
Author: ChanceyGuo
GitHub: https://github.com/ChanceyGuo
Email: ChanceyGuo@outlook.com
