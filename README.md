
# Consumer Complaints Analysis

This project analyzes a dataset of consumer complaints using Python. The primary focus is on loading the dataset, performing exploratory data analysis (EDA), and preparing the data for further machine learning or statistical modeling.

## 📁 Dataset

- **Source:** Google Drive
- **File Used:** `complaints.csv`
- **Contents:** Consumer complaint records including product categories and issues.

## 📊 Features

1. **Data Loading:**
   - Loads data from Google Drive using `pandas`.
   - Verifies if the file exists.

2. **Exploratory Data Analysis (EDA):**
   - Displays basic dataset info.
   - Checks for missing values.
   - Analyzes complaint distribution by product.
   - Uses visualizations (`matplotlib`, `seaborn`).

3. **Data Cleaning & Filtering:**
   - Filters to focus on specific product categories.
   - Prepares dataset for deeper analysis.

## 🛠️ Libraries Used

- `pandas`
- `matplotlib`
- `seaborn`
- `os`
- Google Colab's `drive` module for file access

## 🚀 How to Run

1. Upload the notebook to [Google Colab](https://colab.research.google.com/).
2. Ensure the `complaints.csv` file is located in your **My Drive**.
3. Execute the cells in order for EDA and insights.

## 📌 Notes

- The analysis assumes that only four key product categories are of interest.
- Visualization and insights help understand consumer behavior and complaint trends.
