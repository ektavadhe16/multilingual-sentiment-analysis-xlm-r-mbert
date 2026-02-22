# Multilingual Sentiment Analysis using Transformer Models

##  Overview
This project performs sentiment analysis on multilingual Instagram posts using transformer-based models: mBERT and XLM-RoBERTa.

The system classifies posts into:
- Positive
- Neutral
- Negative

---

## Dataset
- 100,000 Instagram posts
- Training: 80,000
- Testing: 20,000
- Domain: COVID-19 related posts

---

## Models Used
- mBERT (bert-base-multilingual-cased)
- XLM-RoBERTa (xlm-roberta-base)

---

## Results

| Metric | mBERT | XLM-R |
|--------|--------|--------|
| Accuracy | 90.92% | 93.28% |
| Macro F1 | 0.8841 | 0.9161 |
| ROC-AUC | 0.96 | 0.98 |

XLM-RoBERTa outperformed mBERT across all major evaluation metrics.

---

## Tech Stack
- Python
- PyTorch
- HuggingFace Transformers
- Scikit-learn
- Matplotlib / Seaborn

---

## Applications
- Brand Monitoring
- Public Opinion Analysis
- Multilingual Social Media Analytics
