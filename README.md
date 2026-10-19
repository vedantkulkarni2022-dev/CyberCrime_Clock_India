# 🕒 Cybercrime Clock: Emerging Cybercrime Patterns Across Indian Cities

A data science mini project that groups Indian cities by their cybercrime "fingerprint" (K-Means clustering) and tests whether the size of a financial loss can be predicted (classification).

**Dataset:** [Cybersecurity Incidents in India – Kaggle](https://www.kaggle.com/datasets/saisimha203/cybersecurity-cases-india) (`cybersecurity_cases_india_combined.csv`, 1,200 incidents, 2019–2024)

## What's inside
- Data cleaning (duplicates, missing values, Z-score outliers)
- EDA with 4 simple figures
- Hypothesis testing (one-sample t-test)
- Clustering: K-Means + PCA visualisation
- Classification: Logistic Regression, Decision Tree, Random Forest, with confusion matrix, precision, recall and F1

## How to run
1. Put `cybersecurity_cases_india_combined.csv` in the same folder as the notebook.
2. `pip install pandas numpy matplotlib seaborn scipy scikit-learn jupyter`
3. `jupyter notebook Cybercrime_Clock_India.ipynb` then Run All.

## Note
The dataset is simulated and meant for education, so results demonstrate the method rather than real-world facts.
