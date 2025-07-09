##📁 Folder Structure##

```fake-news-detector/
├── fake_news_detector.ipynb     ✅ Main Jupyter notebook
├── data/
│   └── README.md                ✅ Where to download data
├── requirements.txt             ✅ Python packages
├── .gitignore                   ✅ Ignore CSV/data files
└── README.md                    ✅ Full project doc
```

# 📰 Fake News Detector

A beginner-friendly machine learning project that detects fake news articles using text classification with TF-IDF and Logistic Regression.

## 📦 Dataset

Download from Kaggle:  
https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset

Place `True.csv` and `Fake.csv` inside the `/data` folder.

## 🚀 How to Run

```bash
pip install -r requirements.txt
jupyter notebook fake_news_detector.ipynb
```

## 🧠 What You'll Learn

- Text cleaning & feature extraction (TF-IDF)
- Binary classification with Logistic Regression
- Model evaluation (accuracy, precision, recall)
