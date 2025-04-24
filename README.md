# 🧹 Data Cleaning & Preprocessing – Titanic Dataset

This project focuses on learning and applying fundamental data preprocessing techniques using the Titanic dataset. It's a core step in building effective machine learning models by ensuring the data is clean, consistent, and suitable for analysis.

---

## 📌 Objectives

- Handle missing data
- Encode categorical variables
- Standardize numerical features
- Detect and remove outliers

---

## 🛠 Tools Used

- **Python**
- **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn**
- **scikit-learn**

---

## 📊 Dataset

The classic Titanic dataset from Kaggle:
- 891 passenger records
- Mixture of numerical and categorical features
- Common ML tasks: survival prediction, feature engineering

---

## 📂 Steps Performed

### 1. Handle Missing Values
- Imputed `Age` with the median
- Imputed `Embarked` with the mode
- Dropped `Cabin` due to excessive missing data
- Created `HasCabin` binary indicator

### 2. Encode Categorical Variables
- Encoded `Sex` using label encoding (`male` = 0, `female` = 1)
- Applied one-hot encoding to `Embarked`

### 3. Standardize Numerical Features
- Scaled `Age`, `Fare`, `SibSp`, and `Parch` using `StandardScaler` (mean = 0, std = 1)

### 4. Visualize and Remove Outliers
- Visualized with boxplots
- Removed outliers using IQR method for `Fare`, `SibSp`, and `Parch`

---

## 📁 Project Structure

├── data/ │ └── titanic.csv ├── notebooks/ │ └── preprocessing.ipynb ├── src/ │ └── preprocess.py └── README.md



---

## 🚀 Getting Started

1. Clone the repo:
```bash
git clone https://github.com/Harsh374/titanic-preprocessing.git

2. Run the notebook
https://colab.research.google.com/drive/1cK3PD5Y-DQIftFaJyP6jx_FXEWk0V7VR

---


🤝 Contributing
Pull requests and suggestions are welcome. For major changes, please open an issue first to discuss.

📜 License
This project is licensed under the MIT License.

✨ Acknowledgements
Kaggle Titanic Competition

Scikit-learn, Pandas, and Seaborn communities

---

