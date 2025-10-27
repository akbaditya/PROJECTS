OVERVIEW:
- This project uses machine learning and deep learning techniques to identify fraudulent credit card transactions.
The dataset is highly imbalanced, so SMOTE (Synthetic Minority Oversampling Technique) is used to balance it.
The model was trained with multiple optimizers (Adam, RMSprop, SGD) and activation functions (ReLU, Tanh) to find the best-performing combination.

MODEL PERFORMANCE:📊
- Below is a graphical comparison of the model’s performance across different optimizers and activations.
Figure: Comparison of Precision, Recall, F1-Score, and Accuracy across optimizers and activations.

KEY NOTES:🧠
- The Adam optimizer with ReLU activation performed best overall.
- The model achieved a strong F1-score, showing effective fraud detection.
- SMOTE successfully balanced the dataset and improved learning outcomes.

TECHNICAL DETAILS:⚙️
- Frameworks: TensorFlow, scikit-learn, imblearn, matplotlib, seaborn
- Dataset: Credit Card Fraud Detection Dataset
- Techniques Used: Feature Scaling, SMOTE, Neural Networks
- Evaluation Metrics: Accuracy, Precision, Recall, F1-Score

DATASET:📘
- Credit Card Fraud Detection | Kaggle
Link🔗- [https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

