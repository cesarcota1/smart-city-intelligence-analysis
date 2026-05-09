# Smart City Intelligence Analysis

## Project Overview

This project explores global smart city performance using data analysis, clustering techniques, and machine learning models.

The objective is to identify the key dimensions that contribute most strongly to smart city success and uncover patterns among high-performing cities worldwide.

---

## Dataset

The dataset contains smart city indicators for more than 100 cities worldwide, including:

- Smart Mobility
- Smart Environment
- Smart Government
- Smart Economy
- Smart People
- Smart Living
- Overall Smart City Index

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Project Workflow

### 1. Data Cleaning & Exploration
- Loaded and explored the dataset
- Checked data types and summary statistics
- Cleaned column names

### 2. Exploratory Data Analysis (EDA)
- Correlation analysis
- Heatmaps and visualizations
- Statistical summaries

### 3. Clustering Analysis
- Standardized features
- Applied PCA for dimensionality reduction
- Used KMeans clustering to group cities with similar smart city profiles

### 4. Machine Learning Model
- Built a Random Forest Regressor model
- Predicted Smart City Index scores
- Evaluated performance using:
  - Mean Absolute Error (MAE)
  - R² Score

### 5. Feature Importance Analysis
- Identified which smart city dimensions most strongly influence overall smart city performance

---

## Key Insights

- Smart Living was the strongest predictor of overall Smart City Index performance.
- Smart Mobility showed lower predictive importance than expected.
- Nordic cities tended to dominate in government and environmental indicators.
- Different city clusters revealed distinct development priorities and urban strategies.

---

## Model Performance

- MAE: ~193
- R² Score: ~0.89

The model explained approximately 89% of the variance in smart city performance.

---

## Visualizations

### Correlation Heatmap
![Correlation Heatmap](images/correlation_heatmap.png)

### Smart City Clusters
![Clusters](images/city_clusters.png)

### Feature Importance
![Feature Importance](images/feature_importance.png)

---

## Future Improvements

- Add interactive dashboards using Plotly or Tableau
- Include time-series smart city datasets
- Compare regional smart city strategies
- Deploy as a web dashboard

---

## Author

César Adrián Cota Lugo
