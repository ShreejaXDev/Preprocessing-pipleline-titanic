# 🧹 Preprocessing Pipeline for Data Cleaning, Imputation, and Encoding

> **Internship Project – Brainybeam Info-Tech Pvt Ltd**
> **Domain:** Data Science & Machine Learning

---

## 📌 Project Overview

Data preprocessing is one of the most critical stages in any machine learning workflow. Raw datasets often contain missing values, outliers, inconsistent data types, and categorical variables that require transformation before they can be used for model training.

This project focuses on building a **robust, reusable, and end-to-end preprocessing pipeline** using the Titanic dataset. The pipeline automates common data cleaning tasks, making datasets more reliable and suitable for machine learning applications.

The implementation demonstrates multiple preprocessing techniques, compares different approaches, and produces a clean, optimized dataset ready for predictive modeling.

---

## 🎯 Objectives

* Handle missing values using multiple imputation techniques.
* Detect and treat outliers using statistical methods.
* Optimize memory usage through efficient data type conversion.
* Encode categorical variables into machine-learning-friendly formats.
* Build a reusable preprocessing workflow applicable to real-world datasets.

---

## ✨ Features

### ✅ Missing Value Imputation

* Mean Imputation
* Median Imputation
* K-Nearest Neighbors (KNN) Imputation

### ✅ Outlier Detection & Treatment

* Z-Score Method
* Interquartile Range (IQR) Method
* Outlier Removal

### ✅ Memory Optimization

* Downcasting numeric data types
* Converting object columns to category datatype
* Memory usage comparison before and after optimization

### ✅ Categorical Encoding

* One-Hot Encoding
* Target Encoding

### ✅ Data Visualization

* Missing Value Heatmap
* Boxplots
* Distribution Plots
* Statistical Summaries

### ✅ Final Output

* Cleaned Dataset
* Optimized Dataset
* Machine Learning Ready Dataset

---

## 📂 Project Structure

```text
Preprocessing-Pipeline/
│
├── data/
│   └── Titanic_Preprocessed.csv
│
├── notebooks/
│   └── preprocessing_pipeline.ipynb
│
├── src/
│   ├── imputation.py
│   ├── outlier_detection.py
│   ├── encoding.py
│   ├── memory_optimization.py
│   └── preprocessing_pipeline.py
│
├── images/
│   ├── missing_values.png
│   ├── boxplot_before.png
│   ├── boxplot_after.png
│   └── distribution.png
│
├── requirements.txt
├── README.md
└── LICENSE
```

---

## 🗂 Dataset

**Dataset Used:** Titanic Dataset (Seaborn)

The dataset contains passenger information including:

* Passenger Class
* Age
* Sex
* Fare
* Embarked Port
* Number of Siblings/Spouses
* Number of Parents/Children
* Survival Status

It provides an excellent example of real-world preprocessing challenges such as missing values, outliers, mixed data types, and categorical features.

---

## ⚙️ Technologies Used

* Python 3.x
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* SciPy
* Jupyter Notebook

---

## 📚 Preprocessing Workflow

```text
Load Dataset
      │
      ▼
Dataset Inspection
      │
      ▼
Missing Value Analysis
      │
      ▼
Mean Imputation
      │
      ▼
Median Imputation
      │
      ▼
KNN Imputation
      │
      ▼
Outlier Detection
(Z-Score & IQR)
      │
      ▼
Outlier Treatment
      │
      ▼
Memory Optimization
      │
      ▼
One-Hot Encoding
      │
      ▼
Target Encoding
      │
      ▼
Save Final Dataset
```

---

## 📊 Methods Implemented

### 1. Missing Value Imputation

Different strategies are implemented to handle incomplete data.

* Mean Imputation
* Median Imputation
* KNN Imputation

This allows comparison between simple statistical methods and a distance-based imputation technique.

---

### 2. Outlier Detection

Two statistical techniques are used:

* **Z-Score Method**
* **Interquartile Range (IQR) Method**

Detected outliers are analyzed and removed to improve data quality.

---

### 3. Memory Optimization

Memory consumption is reduced by:

* Downcasting integer columns
* Downcasting float columns
* Converting object columns into category datatype

This improves computational efficiency, especially for larger datasets.

---

### 4. Categorical Encoding

Categorical features are transformed using:

* One-Hot Encoding
* Target Encoding

These techniques prepare categorical variables for machine learning algorithms.

---

## 📈 Visualizations

The notebook includes:

* Missing Value Heatmap
* Boxplots Before Outlier Removal
* Boxplots After Outlier Removal
* Distribution Plots
* Dataset Statistics

---

## 🚀 How to Run

### Clone the Repository

```bash
git clone https://github.com/yourusername/preprocessing-pipeline.git
```

### Navigate to the Project

```bash
cd preprocessing-pipeline
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
preprocessing_pipeline.ipynb
```

Run all cells sequentially.

---

## 📋 Output

After execution, the project generates:

* Cleaned Dataset
* Optimized Dataset
* Encoded Dataset
* `Titanic_Preprocessed.csv`

---

## 📌 Learning Outcomes

Through this project, the following concepts are demonstrated:

* Data Cleaning
* Missing Value Handling
* Feature Engineering
* Outlier Analysis
* Memory Optimization
* Data Transformation
* Categorical Encoding
* Data Visualization
* Building Reusable Data Pipelines

---

## 🔮 Future Improvements

* Modular preprocessing package
* Automated preprocessing configuration
* Pipeline serialization using Pickle/Joblib
* Support for multiple datasets
* Interactive dashboard using Streamlit
* Automated preprocessing reports
* Integration with machine learning model training

---

## 👨‍💻 Author

**Shreeja Upadhyay**

B.Tech Student
CHARUSAT University

Internship Project completed at **Brainybeam Info-Tech Pvt Ltd**

---

## 📄 License

This project is developed for educational and internship purposes.

Feel free to use and modify it for learning and research.
