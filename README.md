# 💳 Credit Card Fraud Detection using Machine Learning

## 📌 Project Overview

This project focuses on detecting fraudulent credit card transactions using Machine Learning techniques.
The objective is to build a classification model capable of identifying fraud transactions accurately while handling the highly imbalanced nature of the dataset.

The project includes:

* Data cleaning and preprocessing
* Exploratory Data Analysis (EDA)
* Feature scaling
* Model training and evaluation
* Fraud vs Non-Fraud classification

---

# 🧠 Problem Statement

Credit card fraud is one of the major challenges in the financial industry. Since fraudulent transactions are extremely rare compared to genuine transactions, machine learning models must effectively handle class imbalance and identify suspicious activities with high precision.

This project aims to:

* Analyze transaction patterns
* Detect fraudulent transactions
* Build a predictive ML model
* Evaluate model performance using classification metrics

---

# 📂 Dataset Information

This project uses the **Credit Card Fraud Detection Dataset** from Kaggle.

## 🔗 Dataset Link

[https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

## 📊 Dataset Features

The dataset contains:

* `Time` – Seconds elapsed between each transaction
* `Amount` – Transaction amount
* `V1` to `V28` – Anonymized features obtained using PCA
* `Class` – Target variable

  * `0` → Non-Fraud Transaction
  * `1` → Fraud Transaction

⚠️ Due to GitHub file size limitations, the dataset file is not uploaded in this repository.

---

# ⚙️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

# 📈 Workflow

1. Import Libraries
2. Load Dataset
3. Perform Exploratory Data Analysis
4. Handle Class Imbalance
5. Feature Scaling
6. Train-Test Split
7. Train Machine Learning Model
8. Evaluate Model Performance

---

# 🔍 Exploratory Data Analysis

The project includes:

* Fraud vs Non-Fraud distribution analysis
* Transaction amount analysis
* Correlation analysis
* Data visualization using charts and plots

---

# 🧹 Data Preprocessing

Preprocessing steps performed:

* Feature scaling using `StandardScaler`
* Scaling `Amount` and `Time` columns
* Dropping unscaled columns
* Rearranging features for clarity

---

# 🤖 Machine Learning Model

The project uses:

* **Logistic Regression** for classification

Model evaluation includes:

* Accuracy Score
* Confusion Matrix
* Classification Report

---

# 📊 Model Evaluation

The trained model is evaluated using:

* Precision
* Recall
* F1-Score
* Accuracy

These metrics help measure the effectiveness of fraud detection.

---

# 📁 Project Structure

```bash
Credit-Card-Fraud-Detection_DS_MachineLearning_Internship2/
│
├── Credit_Card_Fraud_Detection_Structured_test.ipynb
├── README.md
└── creditcard.csv (not uploaded)
```

---

# 🚀 How to Run the Project

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/varshakalagudi/Credit-Card-Fraud-Detection_DS_MachineLearning_Internship2.git
```

## 2️⃣ Navigate to the Project Folder

```bash
cd Credit-Card-Fraud-Detection_DS_MachineLearning_Internship2
```

## 3️⃣ Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## 4️⃣ Download Dataset

Download the dataset from Kaggle and place the `creditcard.csv` file inside the project folder.

---

# 📌 Future Improvements

* Use advanced ML algorithms
* Apply SMOTE for imbalance handling
* Hyperparameter tuning
* Deploy using Streamlit or Flask
* Real-time fraud detection system

---

# 🙋‍♀️ Author

**Varsha Kalagudi**

* Aspiring Data Analyst / Data Scientist
* Passionate about Machine Learning and Analytics

---

# ⭐ If You Like This Project

If you found this project useful, consider giving this repository a ⭐ on GitHub.
