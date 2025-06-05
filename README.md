# Milan Airbnb Price Prediction Project

This project analyzes Airbnb listings in Milan to uncover pricing patterns and build predictive models using real-world data. Conducted as part of a Data Science and AI course at NTU, the goal was to explore how factors like location, availability, and room type affect price.

## 🔍 Objectives
- Perform Exploratory Data Analysis (EDA) to understand listing behavior and outliers  
- Identify geographic pricing clusters using KMeans  
- Build regression and classification models to predict price or price category  
- Evaluate model performance and identify most influential features

## Technologies & Libraries
- Python, Jupyter Notebook  
- pandas, numpy  
- matplotlib, seaborn  
- scikit-learn (KMeans, LinearRegression, DecisionTreeClassifier/Regressor)  

## Key Steps
- Data cleaning, transformation (e.g., date parsing, feature engineering)  
- Outlier detection using IQR method  
- Clustering (KMeans) on location data to create regional segments  
- Regression models (Linear Regression, Decision Tree) to predict price  
- Classification to categorize listings into high vs low price groups

## Results
- Classification models outperformed regression, achieving 70.3% accuracy  
- Location and room type were key predictors; numerical features had weak correlations  
- Price prediction was limited by dataset constraints (no apartment size, amenities)

## Files
- `project_current.ipynb` – Jupyter Notebook with all code and analysis  
- `Report.pdf` – Final project report

## Contributors
- **Dalia Betinjaneh** – EDA, data cleaning, outlier analysis, regression models  
- **Emma Anastassova** – Clustering, feature selection, classification models
