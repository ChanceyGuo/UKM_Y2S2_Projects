ProjectC: COVID-19 Tweet Sentiment & Topic Modeling

Project Overview
This project loads the Corona_NLP dataset (Corona_NLP_train.csv & Corona_NLP_test.csv), cleans and preprocesses tweet text, labels each tweet as Positive / Negative / Neutral using TextBlob sentiment polarity, visualizes sentiment distribution and word clouds, and performs LDA topic modeling separately on Positive and Negative tweets to discover key themes.

Files
.
├── README.txt                       This overview file  
├── projectC_notebook.ipynb          Main analysis & modeling notebook  
├── data/
│   ├── Corona_NLP_train.csv         Labeled tweets for training  
│   └── Corona_NLP_test.csv          Unseen tweets for evaluation  
└── requirements.txt                 Python dependencies

Setup & Usage
1. Clone this repo and navigate to ProjectC folder:  
   cd UKM_Y2S2_Projects/ProjectC  
2. Install dependencies:  
   pip install -r requirements.txt  
3. Download / ensure the two CSV files are in the data/ folder.  
4. Launch the notebook:  
   jupyter notebook projectC_notebook.ipynb  
   Run cells in order to reproduce data loading, preprocessing, visualization, sentiment labeling, and topic modeling.

Main Results
- **Sentiment Distribution**  
  - Positive, Negative and Neutral counts (see bar chart in notebook)  
- **Word Clouds**  
  - Top terms for each sentiment group  
- **LDA Topic Modeling**  
  - Positive tweets topics example:  
    - Topic 0: “stay, safe, thank, ...”  
    - Topic 1: “hope, good, health, ...”  
  - Negative tweets topics example:  
    - Topic 0: “cases, hospital, death, ...”  
    - Topic 1: “virus, spread, quarantine, ...”

(Refer to notebook output for full tables and plots.)


Author & Contact
Author: ChanceyGuo
GitHub: https://github.com/ChanceyGuo
Email: ChanceyGuo@outlook.com

