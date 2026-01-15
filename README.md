# Credit-Card-Fraud-Detection-Classification
A machine learning classification project that detects fraudulent credit card transactions using imbalanced data. It applies preprocessing, feature scaling, and models like Logistic Regression and Random Forest. Performance is evaluated using precision, recall, F1-score, and ROC-AUC for reliable fraud detection.
<!DOCTYPE html>

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Credit Card Fraud Detection</title>
    <style>
        body {
            font-family: Arial, Helvetica, sans-serif;
            margin: 40px;
            line-height: 1.6;
            background-color: #f9f9f9;
            color: #333;
        }
        h1, h2 {
            color: #2c3e50;
        }
        ul {
            margin-left: 20px;
        }
        section {
            background: #ffffff;
            padding: 20px;
            margin-bottom: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
    </style>
</head>
<body>

```
<h1>💳 Credit Card Fraud Detection</h1>

<section>
    <h2>🔍 Problem Statement</h2>
    <p>
        Credit card fraud is a major concern in the banking and financial sector. Fraudulent transactions are rare compared to legitimate ones, making the dataset highly imbalanced. This project addresses the challenge by applying appropriate preprocessing techniques and machine learning classification models.
    </p>
</section>

<section>
    <h2>📊 Dataset</h2>
    <ul>
        <li>Anonymized credit card transaction data</li>
        <li>Numerical features (PCA transformed)</li>
        <li>Target variable:</li>
        <ul>
            <li><strong>0</strong> → Legitimate transaction</li>
            <li><strong>1</strong> → Fraudulent transaction</li>
        </ul>
    </ul>
</section>

<section>
    <h2>⚙️ Approach</h2>
    <h3>Data Preprocessing</h3>
    <ul>
        <li>Handling class imbalance</li>
        <li>Feature scaling</li>
        <li>Train–test split</li>
    </ul>

    <h3>Model Building</h3>
    <ul>
        <li>Logistic Regression</li>
        <li>Decision Tree</li>
        <li>Random Forest</li>
        <li>(Optional) SVM / XGBoost</li>
    </ul>

    <h3>Evaluation Metrics</h3>
    <ul>
        <li>Accuracy</li>
        <li>Precision</li>
        <li>Recall</li>
        <li>F1-Score</li>
        <li>ROC–AUC Curve</li>
    </ul>
</section>

<section>
    <h2>🚀 Results</h2>
    <p>
        The models are evaluated with a focus on <strong>recall and precision</strong>, as correctly identifying fraudulent transactions is more important than overall accuracy when working with imbalanced datasets.
    </p>
</section>

<section>
    <h2>🛠️ Technologies Used</h2>
    <ul>
        <li>Python</li>
        <li>NumPy</li>
        <li>Pandas</li>
        <li>Scikit-learn</li>
        <li>Matplotlib / Seaborn</li>
    </ul>
</section>

<section>
    <h2>📌 Conclusion</h2>
    <p>
        This project demonstrates how machine learning classification models can effectively detect fraudulent credit card transactions and highlights the importance of handling imbalanced data in real-world financial applications.
    </p>
</section>
```

</body>
</html>
