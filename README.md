# 🚢 Exploratory Data Analysis (EDA) - Titanic Dataset

## 🎯 Objective:
Understand the Titanic dataset using statistics and visualizations.

## 🧰 Tools Used:
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **Plotly** (optional)

---

## 📊 Task Overview:

The goal of this EDA task is to extract meaningful insights from the Titanic dataset by using basic statistics and data visualization techniques.

---

## ✅ Steps Performed:

### 1. Summary Statistics
- Used `.info()` and `.describe()` to understand data types, mean, median, std, etc.
- Checked for missing values using `.isnull().sum()`

### 2. Visualizations
- **Histograms** to view distribution of numeric features
- **Boxplots** to detect outliers

### 3. Feature Relationships
- Created a **correlation matrix** using `seaborn.heatmap()`
- Built a **pairplot** to observe variable interactions

### 4. Pattern Identification
- Observed that females had higher survival rates
- Passengers in 1st class survived more than others
- Higher fares and younger age slightly increased survival chances

### 5. Feature-level Inference
- Inferences were made from visual patterns and statistical summaries

---

## ✨ Key Insights:

- 🚺 **Gender**: Females had a significantly higher survival rate.
- 🎟️ **Pclass**: Passengers in 1st class survived more than those in 2nd and 3rd.
- 💵 **Fare**: Passengers who paid higher fares had better survival odds.
- 📉 **Age**: Younger passengers had a higher chance of survival.
- ❗ **Missing Data**: Columns like `Cabin` and `Age` had missing values.

---

## 📁 Files Included:
- `Titanic_EDA.ipynb` – Complete notebook with code and output
- `Titanic-Dataset.csv` – Dataset used for analysis
- `README.md` – Project overview and documentation

