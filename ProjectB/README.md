ProjectB: IMDB Sentiment & Jena Climate Forecasting

Project Overview
This notebook uses two public datasets—IMDB Movie Reviews (text classification) and Jena Climate (time-series forecasting).
Key steps:
1. EDA on text (word counts, word clouds) and time series (temperature trends)
2. Data preprocessing: tokenization & padding for text; scaling for climate data
3. Build & train RNN and LSTM models for IMDB sentiment analysis
4. Build & train RNN and LSTM models for Jena climate forecasting
5. Evaluate performance (accuracy for text; MSE/MAE for forecasting)

Files
.
├── README.md                                          This overview file
├── IMDB Sentiment & Jena Climate Forecasting.ipynb    Main analysis and modeling notebook
├── data.zip                                           Contains Corona_NLP_test.csv &  Corona_NLP_train.csv
└── requirements.txt                                   Python dependencies



Main Results
- IMDB Text Models
  - RNN model: validation accuracy ≈ 77%
  - LSTM model: validation accuracy ≈ 83%
  - Test classification report (weighted avg): precision 0.85, recall 0.84, F1-score 0.84
- Jena Climate Forecasting
  - RNN/LSTM models achieved validation MSE ≈ 1.35×10⁻⁵ and MAE on the same order

(See notebook for full tables, plots, and metrics.)


Author & Contact
Author: ChanceyGuo
GitHub: https://github.com/ChanceyGuo
Email: ChanceyGuo@outlook.com

