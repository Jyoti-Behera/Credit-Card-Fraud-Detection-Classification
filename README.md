<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Credit Card Fraud Detection</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 30px;
      line-height: 1.6;
      background-color: #f5f5f5;
    }
    h1, h2 {
      color: #2c3e50;
    }
    section {
      background: #ffffff;
      padding: 15px 20px;
      margin-bottom: 20px;
      border-radius: 6px;
    }
  </style>
</head>
<body>

<h1>💳 Credit Card Fraud Detection</h1>

<section>
  <h2>🔍 Problem Statement</h2>
  <p>
    Credit card fraud is a major concern in the banking and financial sector.
    Fraudulent transactions are rare compared to legitimate ones, making the dataset
    highly imbalanced. This project addresses this challenge using machine learning
    classification models.
  </p>
</section>

<section>
  <h2>📊 Dataset</h2>
  <ul>
    <li>Anonymized credit card transaction data</li>
    <li>Numerical features (PCA transformed)</li>
    <li>Target variable:</li>
    <ul>
      <li>0 → Legitimate transaction</li>
      <li>1 → Fraudulent transaction</li>
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
    Models are evaluated with a focus on recall and precision, as detecting fraud
    correctly is more important than overall accuracy in imbalanced datasets.
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
    This project shows how machine learning classification models can effectively
    detect fraudulent credit card transactions and handle imbalanced data.
  </p>
</section>

</body>
</html>

