AI vs Human Text Classifier

A machine learning project to classify whether a given text is written by a human or AI.
This project uses Python, Pandas, NumPy, and Scikit-learn, along with multiple ML models such as Logistic Regression, Decision Tree, and Naive Bayes to compare performance.

📌 Features

Preprocessing of text data (cleaning, tokenization, vectorization).

Multiple classification models:

Logistic Regression

Decision Tree Classifier

Naive Bayes Classifier

Performance comparison using accuracy, precision, recall, and F1-score.

Easy-to-extend modular code structure.

🛠️ Technologies Used

Python 🐍

Pandas – Data handling & preprocessing.

NumPy – Numerical computations.

Scikit-learn – ML models, vectorization, and evaluation.

📊 Model Evaluation

The models are evaluated using:

Accuracy

Precision

Recall

F1-score

Sample output :

| Model               | Accuracy | Precision (H, AI)   | Recall (H, AI)      | F1-Score |
| ------------------- | -------- | ------------------- | ------------------- | -------- |
| Logistic Regression | 1.000    | H = 0.99, AI = 1.00 | H = 1.00, AI = 0.99 | 1.00     |
| Decision Tree       | 0.987    | H = 0.97, AI = 0.99 | H = 0.99, AI = 0.97 | 0.98     |
| Naive Bayes         | 0.997    | H = 0.99, AI = 1.00 | H = 1.00, AI = 0.99 | 0.99     |

Conclusion:
This project demonstrates the development of a binary text classification model to distinguish between human-written and AI-generated text. Using a custom dataset (2,500 samples per class), I applied TF-IDF vectorization and evaluated multiple machine learning models to balance accuracy, interpretability, and deployment readiness.

Best Performing Model
The top model was Logistic Regression, which achieved:

Perfect test accuracy: 1.00

AUC: 1.00 (flawless ROC curve)

F1-score: 1.00
