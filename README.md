🍷 Red & White Wine Quality Analysis

Exploratory Data Analysis (EDA) & Visualization Project

📌 Overview

This project focuses on performing Exploratory Data Analysis (EDA) and visualization on the Red & White Wine Quality Dataset.
The goal is to understand the relationship between chemical properties and wine quality, identify key patterns, and visualize important trends that influence wine rating.

📂 Dataset

The dataset contains physicochemical properties of red and white wine samples along with their quality rating.

Feature Type	Description
🔢 Numerical	Examples: pH, alcohol %, sulphates, residual sugar, fixed acidity
📌 Target Variable	Wine Quality (Score range: 0–10)
🧪 Category	Wine Type (Red / White)
🛠️ Tools & Libraries Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Plotly (optional for interactive charts)

🔍 Key Steps Performed

✔ Data Cleaning
✔ Removing duplicates
✔ Detecting and handling missing values
✔ Outlier analysis
✔ Descriptive statistics

✔ Feature correlations
✔ Visual exploration of distributions

📊 Visualizations Included

Histogram distribution of features

Boxplots for detecting outliers

Correlation heatmap

Scatter plots (Alcohol vs Quality, pH vs Acidity, etc.)

Pairplots to explore relationships

Bar chart showing average quality by wine type

All plots are stored in the folder:

/visuals

📝 Insights & Findings

🔹 Alcohol content shows a positive correlation with wine quality
🔹 Higher sulphates and citric acid levels are associated with better quality
🔹 White wine has more variation in residual sugar compared to red
🔹 Some features require scaling for better machine learning use

📁 Project Structure
📦 wine-quality-analysis
 ┣ 📂 dataset
 ┣ 📂 visuals
 ┣ 📜 Wine_EDA.ipynb
 ┣ 📜 README.md
 ┗ 📜 requirements.txt

🚀 Future Improvements

Feature Engineering

Predictive modeling using ML (Random Forest, XGBoost, etc.)

Model tuning & comparison

Deployment using Streamlit/Dashboard

🙌 Acknowledgements

Dataset Source: UCI Machine Learning Repository (Wine Quality Dataset)

📧 Contact

If you'd like to connect or give feedback, feel free to reach out!

Would you like me to:

Add a badges section (Python version, license, etc.)?

Convert this into a markdown file with working links and image placeholders?

Add a live preview section if you plan to publish visuals?

🙂
