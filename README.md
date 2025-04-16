# customer-transaction-presiction
python-mini-project
# 🧠 Customer Transaction Prediction (PRCP-1003)

This project predicts whether a customer will make a transaction based on historical data. It's implemented using Python in a **Jupyter Notebook** environment (via Anaconda), applying machine learning models like **Logistic Regression** and **LightGBM** with data visualization and performance evaluation.

---

## 📊 Problem Statement

The goal is to classify customers into two categories:
- **1**: Will make a transaction
- **0**: Will not make a transaction

The dataset contains anonymized features derived from customer behavioral patterns.

---

## 🛠️ Tools & Libraries Used

- **Python 3.8+**
- **Pandas**: Data handling
- **NumPy**: Numerical operations
- **Matplotlib & Seaborn**: Visualization
- **scikit-learn**: ML models and metrics
- **LightGBM**: Gradient boosting framework
- **Jupyter Notebook** (via Anaconda)

---

## 📁 Dataset

- **train(1).csv** – Training dataset  
  *(Ensure this file is located at: `D:/python project/PRCP-1003-CustTransPred/Data/train(1).csv` or update the path accordingly in your notebook.)*

---

## ⚙️ How to Run the Project

Step 1: Open Jupyter Notebook (via Anaconda)
jupyter notebook
Then open the .ipynb file or paste the Python script into a new notebook.

Step 2: Install Required Libraries (if not already installed)
pip install pandas numpy matplotlib seaborn scikit-learn lightgbm
Step 3: Run the Notebook
Execute all the cells in order to:

Load and preprocess data

Visualize patterns

Train Logistic Regression model

Evaluate accuracy, precision, recall, F1-score, and AUC

Plot confusion matrix and correlation heatmap

📈 Key Techniques
StandardScaler for feature normalization

Train-Test Split (70-30)

Logistic Regression as a baseline classifier

Confusion Matrix & Classification Report for evaluation

Correlation Analysis & Heatmaps for feature exploration



