💳🔍 Online Payment Fraud Detection

Online transactions have become a part of everyday life—but with convenience comes risk.
Online Payment Fraud Detection is a machine learning-based project aimed at identifying fraudulent financial transactions in digital payment systems. Utilizing a dataset of transaction records, this model analyzes patterns and key attributes such as transaction type, amount, and account balances to classify whether a transaction is potentially fraudulent. The project leverages data preprocessing, visual analysis, and a Decision Tree Classifier to achieve predictive insights. This solution provides a foundational approach for enhancing online transaction security through intelligent fraud detection.

---

Workflow
Data Loading & Preprocessing
Handling missing values
Understanding the distribution of transaction types
Visualization
Pie chart showing transaction type proportions
Use of Plotly for interactive plots
Feature Selection
Selected columns: type, amount, oldbalanceOrg, newbalanceOrig 
Model Training
Algorithm: DecisionTreeClassifier
Split: 80% training, 20% testing
Evaluation
Accuracy score printed using .score() method
Prediction example included for custom input

---

📈 Results
The implemented model exhibits reliable performance in identifying irregularities within transactional data, effectively distinguishing between legitimate and potentially fraudulent activity. Leveraging the interpretability of the Decision Tree algorithm, the solution provides transparency in decision-making, making it well-suited for initial deployment in fraud detection frameworks where explainability is crucial.
