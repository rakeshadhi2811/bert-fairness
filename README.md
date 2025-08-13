# bert-fairness
A BERT-based pipeline combines text and numeric data to predict customer churn. It fine-tunes BERT with numeric features, uses adversarial debiasing to reduce bias on sensitive attributes, and monitors fairness metrics during training. The model outputs predictions saved as CSV files, implemented in PyTorch with Hugging Face.
