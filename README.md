# Fraud Transaction Detection

This project aims to develop a machine learning model that detects fraudulent financial transactions using a simulated dataset. The dataset replicates common fraud patterns, allowing for both baseline model evaluation and the application of more complex detection techniques.

## 📌 Objective

Build a system that can classify whether a transaction is **fraudulent** or **legitimate** using historical transaction data.

## 📂 Dataset

The dataset consists of simulated transactions, designed to mimic real-world fraud scenarios. It includes the following columns:

- `TRANSACTION_ID`: Unique identifier for each transaction.
- `TX_DATETIME`: Timestamp of the transaction.
- `CUSTOMER_ID`: Unique identifier for each customer.
- `TERMINAL_ID`: Unique identifier for each terminal or merchant.
- `TX_AMOUNT`: Transaction amount.
- `TX_FRAUD`: Binary label (1 for fraud, 0 for legitimate).

### 🧪 Fraud Scenarios Simulated

1. **High Amount Fraud**: Transactions with an amount > 220 are marked fraudulent.
2. **Terminal Compromise**: Random terminals are marked as fraudulent for 28 days.
3. **Customer Credential Theft**: 3 random customers per day have a fraction of their transactions marked fraudulent (amounts multiplied by 5) for 14 days.

These scenarios aim to reflect different types of fraud, such as phishing, card-not-present fraud, and anomalous spending patterns.

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas, NumPy
- Scikit-learn
- Matplotlib / Seaborn

## 📊 Model Approach

1. **Data Preprocessing**:
   - Handling timestamps
   - Feature engineering (e.g., rolling aggregates per customer/terminal)

2. **Modeling**:
   - Baseline classifier (e.g., logistic regression)
   - Advanced models (e.g., Random Forest, Gradient Boosting)

3. **Evaluation**:
   - Accuracy, Precision, Recall, F1 Score
   - ROC-AUC Curve

## 📈 Results

The model was evaluated on its ability to detect known fraudulent patterns and generalize to unseen data.


## 👨‍💻 Author

- [Lakshya jain] – [GitHub Profile]((https://github.com/lakshyajainLJ))



