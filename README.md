# effective-titanic
Preprocessing And Data Cleaning of Titanic Dataset


# 🚀 Data Cleaning & Preprocessing Task

## 🧾 Objective

Learn how to clean and prepare raw data for machine learning using basic data preprocessing techniques.

## 🛠 Tools Used

* Python
* Pandas
* NumPy
* Matplotlib / Seaborn

## 📂 Dataset

**Titanic Dataset**
[Download Link (Kaggle)](https://www.kaggle.com/c/titanic/data](https://www.kaggle.com/c/titanic/data))

---

## 🔍 Steps Performed

### 1. Data Exploration

* Loaded the dataset using Pandas
* Explored data types and missing values using `.info()` and `.isnull().sum()`

### 2. Handling Missing Values

* **Embarked**: Filled missing values using **mode**
* **Age**: Used **SimpleImputer** with strategy = `'mean'`
* **Cabin**: Dropped the column because over 75% of values were missing

### 3. Encoding Categorical Data

* **Sex**: Used **LabelEncoder** to convert to numerical values

### 4. Outlier Detection and Removal

* Used **boxplots** to visualize outliers
* Removed outliers from relevant numerical features based on visual inspection

---

## 💡 Key Concepts Learned

* Filling missing data using statistical methods
* Converting categorical features into numerical
* Identifying and handling columns with too many nulls
* Detecting and removing outliers using boxplots


---

## 📁 Project Files

```
├── data/
│   └── titanic.csv
├── preprocessing.ipynb
├── README.md

