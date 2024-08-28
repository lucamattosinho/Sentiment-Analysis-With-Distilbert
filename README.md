---
license: apache-2.0
language:
- en
metrics:
- accuracy
---

This model is a fine-tuned version of distilbert-base-uncased on the twitter-entity-sentiment-analysis dataset (from Kaggle).

# Training hyperparameters
- batch_size: 16
- num_epochs: 4
- learning_rate: 2e-5
- optimizer: AdamW
- scheduler_type: linear

# Results achieved
- accuracy: 97.8%
- f1_score: 97.8%