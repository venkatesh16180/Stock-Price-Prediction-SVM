# Stock Price Prediction Using Support Vector Machines
**Undergraduate Final Year Project | Matrusri Engineering College**
**Published in IJCRT — International Journal of Creative Research Thoughts**

---

## 📌 Overview
A machine learning research project investigating the effectiveness of 
**Support Vector Machines (SVM)** for predicting stock price movements, 
benchmarked against Artificial Neural Networks (ANN) and Long Short-Term 
Memory (LSTM) networks. The full research methodology was co-authored and 
published in a **peer-reviewed international ML journal**.

---

## 📜 Publication
**Title:** Exploring the Benefits of Support Vector Machines for Stock Prediction

| Detail | Info |
|---|---|
| Journal | International Journal of Creative Research Thoughts (IJCRT) |
| ISSN | 2320-2882 |
| Impact Factor | 7.97 |
| UGC Approved | Yes |
| Volume/Issue | Volume 11, Issue 5 |
| Paper ID | IJCRT2305597 |
| Published | May 2023 |

📄 [View Published Paper](Publication/Publication_Soft_Copy.pdf)
🏆 [View Publication Certificate](Publication/Publication_Certificates.pdf)

---

## 📊 Dataset
**NSE Reliance Industries Stock Data**
- Source: Yahoo Finance
- Features: Open, High, Low, Close (OHLC) prices, Trading Volume
- File: `RELIANCE_NS.csv`

---

## 🧠 Approach
Built a full end-to-end ML pipeline for binary stock movement 
classification (price up vs. price down):

1. **Data Collection** — Historical OHLC data from Yahoo Finance
2. **Feature Engineering** — Daily returns, moving averages, 
   Open-Close differentials, High-Low differentials, technical indicators
3. **Preprocessing** — Missing value handling, feature normalization, 
   80/20 train-test split
4. **Modeling** — SVM (sklearn SVC) benchmarked against ANN and LSTM
5. **Evaluation** — Accuracy, confusion matrix, predicted vs. actual 
   price visualization

---

## 📊 Results

| Model | Accuracy |
|---|---|
| Random Baseline | 50% |
| ANN | Baseline comparison |
| LSTM | Baseline comparison |
| **SVM (Our Model)** | **56%** |

SVM outperformed the random baseline and demonstrated competitive 
performance against deep learning approaches for binary stock movement 
classification — with significantly lower computational cost.

---

## 🔑 Key Finding
SVM proved effective for short-term binary stock movement prediction 
while remaining computationally efficient compared to ANN and LSTM — 
making it a practical choice for real-time trading applications with 
limited computational resources.

---

## 🛠️ Tools & Technologies
| Category | Tools |
|---|---|
| Language | Python |
| ML Model | Scikit-learn (SVC) |
| Data Source | Yahoo Finance (yfinance) |
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib |
| Baseline Models | ANN, LSTM (for comparison) |
| Documentation | 38-page research report |

---

## 📁 Repository Structure
```
Stock-Price-Prediction-SVM/
│
├── Publication/
│   ├── Publication_Soft_Copy.pdf       # Published IJCRT paper
│   └── Publication_Certificates.pdf    # Publication certificate
│
├── Final_Review.pptx                   # Source code and methodology
├── Final_Report.pdf                    # Full 50-page research report
├── Base_Paper.pdf                      # Literature survey reference
├── RELIANCE_NS.csv                     # NSE Reliance stock dataset
└── README.md
```

---

## 🚀 How to Run
The source code is documented in `Final_Review.pptx`. To replicate:

1. Install dependencies:
```bash
   pip install pandas numpy scikit-learn matplotlib yfinance
```
2. Load the dataset:
```python
   import pandas as pd
   df = pd.read_csv('RELIANCE_NS.csv')
```
3. Follow the pipeline documented in `Final_Review.pptx` and 
   `Final_Report.pdf`

> **Note:** For best results, consider converting the source code from 
> the presentation into a standalone Jupyter notebook.

---

## 👥 Authors
**Venkateshwara Chowdary Tallapaneni** *(corresponding author)*
MS Information Sciences (Machine Learning) | University of Arizona
[LinkedIn](https://www.linkedin.com/in/venkateshwara-chowdary-tallapaneni) | 
[GitHub](https://github.com/venkatesh16180)

*Co-authored with team Batch 5, Matrusri Engineering College, 
Hyderabad, India (2023)*

---

## 📄 License
This repository is for portfolio and educational purposes. 
The published paper is the intellectual property of IJCRT and the authors.
