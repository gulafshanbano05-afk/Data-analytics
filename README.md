# Google Play Store Data Analysis

## 📌 Project Overview

This project analyzes the Google Play Store dataset to explore app categories, ratings, installations, pricing, and free vs. paid applications.

Using Python, the project performs data cleaning, exploratory data analysis (EDA), and visualization to identify patterns in Android applications.

## 🎯 Objectives

- Analyze app categories and ratings.
- Compare free and paid applications.
- Explore relationships between prices, ratings, reviews, and installations.
- Clean missing values and remove duplicates.
- Create visualizations to communicate insights.

## 🛠️ Technologies Used

- **Python** — Data analysis
- **Pandas, NumPy** — Data manipulation
- **Matplotlib, Seaborn** — Visualization
- **KaggleHub** — Dataset download
- **Google Colab / Jupyter Notebook** — Development environment

## 📂 Dataset

**Source:** [Google Play Store Apps — Kaggle](https://www.kaggle.com/datasets/lava18/google-play-store-apps)

The original dataset contains 10,841 records and 13 columns, including app names, categories, ratings, reviews, installations, prices, and Android versions.

## ⚙️ Project Workflow

### 1. Data Collection and Exploration
- Downloaded the dataset using KaggleHub.
- Examined data types, descriptive statistics, missing values, and duplicates.

### 2. Data Cleaning
- Filled missing ratings with the mean.
- Removed duplicate records.
- Converted prices, installations, and reviews into numeric formats.
- Created an `isPaid` feature.
- Saved the cleaned dataset as `cleaned_data.csv`.

### 3. Exploratory Data Analysis (EDA)
Created visualizations to analyze:
- Top app categories and average ratings
- Free vs. paid app distribution
- Rating distribution
- Price vs. rating
- Installations vs. rating
- Correlations among ratings, reviews, installations, and prices

### 4. Exporting Results
- `cleaned_data.csv` — Cleaned dataset
- `eda_summary.csv` — Statistical summary

## 🚀 How to Run

1. Clone or download this repository.
2. Open `Data_Analytics.ipynb` in Google Colab or Jupyter Notebook.
3. Install dependencies if required:

   ```bash
   pip install pandas numpy matplotlib seaborn kagglehub
   ```

4. Run the notebook cells in order.

**Note:** Kaggle access may need to be configured when running locally.

## 📚 Learning Outcomes

- Data cleaning and preprocessing
- Handling missing values and duplicates
- Exploratory data analysis
- Data visualization and correlation analysis
- Exporting cleaned datasets and summaries

## 👩‍💻 Author

**Gulafshan Bano**

- [GitHub](https://github.com/gulafshanbano05-afk)
- [LinkedIn](https://www.linkedin.com/in/gulafshan-bano-337602380/)

## 📄 Dataset Attribution

Dataset credited to Lavanya Gupta. Refer to the [Kaggle dataset page](https://www.kaggle.com/datasets/lava18/google-play-store-apps) for licensing and attribution requirements.
