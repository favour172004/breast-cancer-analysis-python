# 🎗️ Breast Cancer Diagnosis Analysis (Wisconsin Dataset)

## 📌 Project Overview

This project explores the Wisconsin Breast Cancer Dataset using Python, Pandas, Matplotlib, and Seaborn.

The objective is to perform Exploratory Data Analysis (EDA) to identify the characteristics that are most strongly associated with malignant (cancerous) and benign (non-cancerous) tumors.

Rather than building a machine learning model, this project focuses on understanding the data through statistical analysis and visualizations.

---

## 📂 Dataset

Dataset: Wisconsin Breast Cancer Dataset

The dataset contains measurements extracted from digitized images of breast tissue samples.

Each record is labelled as either:

- **Malignant** (Cancerous)
- **Benign** (Non-cancerous)

---

## 🎯 Analysis Questions

This project answers the following questions:

1. How many tumors are malignant and how many are benign?
2. Which tumour characteritics differ the most between malignant and benign tumors?
3. Which features are closely correlated with breastcancer diagnosis ?
4. which tumor features are most related to one another?

---

## 📊 Key Findings

- Benign tumors were more common than malignant tumors.
- Malignant tumors generally had larger radius, perimeter and area values.
- Malignant tumors also showed much higher concavity and concave point measurements.
- Concave points, perimeter and radius showed the strongest relationship with malignant diagnosis.
- Radius, perimeter and area were highly correlated, meaning larger tumors tend to have larger measurements across multiple dimensions.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📁 Files

- `cancer.ipynb` — Complete exploratory data analysis.
- `wisconsin_breast_cancer.csv` — Dataset used for the analysis.

---

## ▶️ How to Run

1. Clone this repository.
2. Install the required libraries listed in `requirements.txt`.
3. Open `cancer.ipynb` in Jupyter Notebook or VS Code.
4. Run all cells to reproduce the analysis.

---

## 📌 Conclusion

This exploratory analysis shows that several tumor measurements are strongly associated with breast cancer diagnosis. Features such as concave points, perimeter, radius, and area consistently distinguish malignant tumors from benign ones.

The project demonstrates how Exploratory Data Analysis can uncover meaningful patterns that support medical research and prepare data for future machine learning applications.