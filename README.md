💳 Credit Card Fraud Detection Model
🎯 Overview
This project focuses on building and evaluating a machine learning model to accurately detect fraudulent credit card transactions. The core challenge addressed is the high class imbalance—where legitimate transactions vastly outnumber fraudulent ones.

The model utilizes anonymized transactional data, focusing on features like time, transaction amount, and principal components of other sensitive features (V1 to V28).

🛠️ Key Techniques & Technologies
Language: Python

Machine Learning: Scikit-learn (Logistic Regression, Decision Trees), Isolation Forest (often strong for anomaly detection).

Imbalance Handling: Oversampling (e.g., SMOTE), Undersampling, or Class Weighting.

Evaluation: Focus on Recall (Sensitivity) and the Area Under the Precision-Recall Curve (AUPRC) to ensure high detection rates for rare fraudulent cases.

Exploration: Jupyter Notebook (Fraud detection model (1).ipynb).

Libraries: Pandas, NumPy, Matplotlib, Seaborn.

📊 Performance Summary
Due to the critical nature of catching fraud (minimizing False Negatives), the model was optimized for high Recall.

Metric

Target Optimization

Result (Example)

Recall

Maximize

~92%

Precision

Balance

~85%

The final selected model (often Logistic Regression or a specialized Anomaly Detection algorithm like Isolation Forest after balancing) provides a strong capability to flag suspicious activity with minimal operational overhead.

🚀 Quick Setup
To explore the data analysis, balancing techniques, and model training:

# Clone the repository
git clone [YOUR_REPO_URL_HERE]

# Install required libraries (Example list - update for your actual requirements.txt)
pip install pandas numpy scikit-learn matplotlib jupyter imbalanced-learn

# Run the notebook for full analysis
jupyter notebook "Fraud detection model (1).ipynb"

🤝 Contact
Aditya Dusane
www.linkedin.com/in/aditya-dusane
