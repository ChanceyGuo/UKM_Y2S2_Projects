ProjectB: IMDB Sentiment & Jena Climate Forecasting

Project Overview
This notebook uses two public datasets for two tasks:  
1. **IMDB Movie Reviews** (binary sentiment classification)  
2. **Jena Climate** (time-series forecasting of temperature)
Key steps:
1. Exploratory Data Analysis (word counts, word clouds for text; trend plots for climate)  
2. Data preprocessing: tokenization & padding for text; scaling & windowing for climate  
3. Build & train simple RNN and LSTM models on each dataset  
4. Evaluate performance (accuracy & classification report for IMDB; MSE/MAE for Jena)

Files
.
├── README.md                                          This overview file
├── IMDB Sentiment & Jena Climate Forecasting.ipynb    Main analysis and modeling notebook
├── data.zip                                           jena_climate_2009_2016.csv
└── requirements.txt                                   Python dependencies

Data
- **IMDB reviews**: automatically downloaded by TensorFlow Datasets (`tfds.load('imdb_reviews')`)  
- **Jena climate**: download the file `jena_climate_2009_2016.csv` from https://www.kaggle.com/datasets and put it into the `data/` folder  

Setup & Usage
1. Clone repo and enter ProjectB folder  
2. Install dependencies:
   pip install -r requirements.txt  
3. Ensure `data/jena_climate_2009_2016.csv` exists  
4. Run notebook:
   jupyter notebook group2_final_version.ipynb  
   Execute cells in order to reproduce results


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

