# ⚽ Comprehensive Analysis of EPL Match Data

## 🌟 Project Overview

This project delves into the rich dataset of English Premier League (EPL) matches to uncover insights using statistical analysis and machine learning models. The analysis covers factors such as team formations, home advantage, shooting efficiency, and match outcomes. The ultimate aim is to enhance strategic decision-making and contribute to the growing field of football analytics.

## 📂 Repository Content

### 1. **Data/**
   - **📊 Raw Data:** Contains the original data scraped from the `fbref` website and `Stathead` platform.
   - **🧹 Processed Data:** Includes cleaned and feature-engineered datasets used for analysis and model training.

### 2. **Docs/**
   - Includes detailed project documentation, the final report, and research notes explaining methods and findings.

### 3. **Models/**
   - Python notebooks implementing machine learning models like Logistic Regression, Random Forest, Gradient Boosting, and Neural Networks. Each notebook provides performance metrics and comparative analysis.

### 4. **Scripts/**
   - **🛠️ Data Collection:** Scripts using web scraping tools like BeautifulSoup to extract data from `fbref` and handle API interactions with `Stathead`.
   - **📈 EDA:** Notebooks for exploratory data analysis, including visualizations and initial insights into the dataset.
   - **🔍 Hypothesis Testing:** Code to validate hypotheses such as the impact of formations on win rates or the statistical significance of home advantage.

## 🚀 Key Highlights

### 📥 Data Collection
- Data was collected using web scraping techniques from the `fbref` website. Initial scraping was limited by rate limits, prompting the use of a paid subscription to `Stathead` for extended access.
- The dataset comprises over 5,000 matches, covering seven EPL seasons, with over 27 columns of data, including team stats, results, and match metadata.
- Features such as `Avg_Goals_Scored_3`, `Goal_Efficiency`, and `Shooting_Accuracy` were engineered for deeper analysis.

### 🤖 Machine Learning Models
- **Gradient Boosting:** The top-performing model, achieving the highest accuracy and effectively capturing complex relationships.
- **Random Forest:** A close second, offering robust performance and feature importance insights.
- **Neural Networks:** Demonstrated potential but required more computational resources and fine-tuning.
- Other models included Logistic Regression, SVM, Naive Bayes, and Decision Trees, each offering unique strengths and limitations.

### 📊 Statistical Analysis
- Hypotheses tested included:
  - Teams with higher shooting accuracy have higher win rates.
  - Home advantage plays a statistically significant role in match outcomes.
- Tools like t-tests and binomial tests were used for hypothesis validation.

### 📌 Visualizations
- 📡 Radar charts to compare performance metrics across top teams.
- 🗺️ Heatmaps showing correlations between match statistics.
- 🟠 Scatter plots highlighting relationships like xG (expected goals) vs. GF (goals for).
- 📊 Bar charts depicting winning percentages and other key trends.

## 🛠️ Tools Used

- **Data Collection:** BeautifulSoup, Requests
- **Data Analysis:** Pandas, Numpy
- **Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn, TensorFlow
- **Documentation:** Jupyter Notebooks, Markdown

## ✅ Results

- Gradient Boosting emerged as the top-performing model, with an accuracy of 61.46%, highlighting its ability to model complex relationships.
- Hypothesis tests confirmed significant factors, including the critical role of shooting efficiency and the value of certain formations.
- Visualizations provided actionable insights into team strategies and match outcomes.

## 🔧 How to Use the Repository

1. **📝 Account Setup:**
   - Create an account on `Stathead` for extended data access if you plan to replicate the data collection process.
   - Use the scripts in `Scripts/Data Collection` to scrape and preprocess data.

2. **📉 Run Analysis:**
   - Notebooks in the `Scripts/EDA` folder provide initial insights and visualizations.
   - Use hypothesis testing scripts for statistical validations.

3. **🤖 Train Models:**
   - The `Models/` folder contains training scripts for various machine learning models.
   - Modify parameters as needed to explore different configurations.

4. **📑 Review Results:**
   - Refer to the `Docs/` folder for a comprehensive project report and summarized findings.

## 🙏 Acknowledgments

- Special thanks to `fbref` and `Stathead` for providing access to EPL match data.
- Appreciation to the University of Illinois at Chicago (UIC) for resources and guidance in CS418.
