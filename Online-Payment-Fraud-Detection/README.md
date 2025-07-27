# 💳🔍 Online Payment Fraud Detection

**Online transactions have become a part of everyday life, but with convenience comes risk.**

Online Payment Fraud Detection is a machine learning-based project aimed at identifying fraudulent financial transactions in digital payment systems. Utilizing a dataset of transaction records, this model analyzes patterns and key attributes such as transaction type, amount, and account balances to classify whether a transaction is potentially fraudulent. The project leverages data preprocessing, visual analysis, and a Decision Tree Classifier to achieve predictive insights. This solution provides a foundational approach for enhancing online transaction security through intelligent fraud detection.

---

## 🔄 Workflow

1. **Data Loading & Preprocessing**
    - Handling missing values
    - Understanding the distribution of transaction types

3. **Visualization**
    - Pie chart showing transaction type proportions
    - Use of Plotly for interactive plots
   
4. **Feature Selection**
    - Selected columns: type, amount, oldbalanceOrg, newbalanceOrig
    
5. **Model Training**
    - Algorithm: DecisionTreeClassifier
    - Split: 80% training, 20% testing

6. **Evaluation**
    - Accuracy score printed using .score() method
    - Prediction example included for custom input

---

## 📈 Results

The implemented model exhibits reliable performance in identifying irregularities within transactional data, effectively distinguishing between legitimate and potentially fraudulent activity. Leveraging the interpretability of the Decision Tree algorithm, the solution provides transparency in decision-making, making it well-suited for initial deployment in fraud detection frameworks where explainability is crucial.
