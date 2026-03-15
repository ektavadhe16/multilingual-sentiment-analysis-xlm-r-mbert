# Results

This folder contains the evaluation outputs and visualizations generated during the experimentation phase of the **Multilingual Sentiment Analysis** project. The goal of these experiments was to compare the performance of transformer-based multilingual models for sentiment classification.

## Experiment Overview

The experiments evaluate the effectiveness of pretrained multilingual transformer models in classifying sentiments from multilingual social media text. The models were fine-tuned on labeled sentiment data and evaluated using standard classification metrics.

Models evaluated:

* mBERT (Multilingual BERT)
* XLM-RoBERTa

---

## Evaluation Metrics

The following metrics were used to evaluate model performance:

* **Accuracy** – Overall correctness of predictions
* **Precision** – Proportion of correctly predicted positive observations
* **Recall** – Ability of the model to identify all relevant instances
* **F1 Score** – Harmonic mean of precision and recall

These metrics help assess both the correctness and balance of predictions across sentiment classes.

---

## Model Performance
| Model       | Accuracy | Precision | Recall | F1 Score |
| ----------- | -------- | --------- | ------ | -------- |
| mBERT       |   90.92  | 88.90     | 87.98  | 88.41    |
| XLM-RoBERTa | 93.28    |  91.33    |  93.31 | 91.61    |


---

## Visual Results

This folder also contains visual representations of the evaluation results.

Examples include:

* **Confusion Matrix** – Shows how well the model classified each sentiment category.
* **ROC Curve** – Demonstrates the model's ability to distinguish between classes.



---

## Key Observations

* XLM-RoBERTa demonstrated stronger cross-lingual understanding compared to mBERT.
* Transformer-based models effectively handled multilingual sentiment classification.
* Performance varied slightly when processing informal or code-mixed social media text.

---

## Conclusion

The results indicate that multilingual transformer models are effective for sentiment analysis across multiple languages. Among the evaluated models, **XLM-RoBERTa showed improved performance due to stronger multilingual representations and larger pretraining data.**

---


