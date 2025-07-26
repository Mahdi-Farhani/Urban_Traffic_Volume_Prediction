# 🚦 Urban Traffic Volume Prediction
*Predicting City Traffic using Machine Learning (Metro Interstate Traffic Volume Dataset)*

## 📑 Overview

This repository contains a step-by-step educational project for **predicting urban traffic volume** using the [Metro Interstate Traffic Volume Dataset](https://archive.ics.uci.edu/ml/datasets/Metro+Interstate+Traffic+Volume).  
The project is designed as a reference for both **practical machine learning workflows** and **educational purposes**, including advanced topics such as:
- Feature Engineering (especially from date-time features)
- Outlier Detection & Handling
- Regularization techniques
- Model building & evaluation (Linear, Ridge, Lasso, Tree-based, XGBoost, etc.)
- Scientific documentation & reproducibility

> This repository can serve as a resource for colleagues, an ML teaching course, and even as the base for a book or advanced technical notes.

---


## Objectives

- How to perform practical machine learning on real-life tabular data
- Feature extraction from time-series and weather info
- Working with outliers, missing values, and categorical encodings
- Building, evaluating, and comparing regression models
- Understanding regularization for overfitting prevention

---
## 📚 Educational Roadmap

The project is organized as **a series of Jupyter Notebooks** covering practical steps:
1. **Introduction & Data Loading**  
2. **Exploratory Data Analysis (EDA)**  
3. **Feature Engineering (Time, Weather, Holidays, etc.)**  
4. **Outlier Detection & Handling**  
5. **Data Preprocessing**  
6. **Baseline Modeling (Linear Regression, Regularization)**  
7. **Tree-based Models (Random Forest, XGBoost, etc.)**  
8. **Model Evaluation, Visualization & Interpretation**  
9. **Summary & Further Explorations**  

Each notebook contains clear explanations (English, with Persian notes where needed), code, and visualizations suitable for learning and teaching.

---

## Dataset Description

- **Source**: [UCI Machine Learning Repository – Metro Interstate Traffic Volume Data Set](https://archive.ics.uci.edu/dataset/492/metro+interstate+traffic+volume)
- **Description**: Hourly measurements of road traffic volume and weather conditions captured from 2012 to 2018 on Interstate 94 in Minneapolis, Minnesota. The data enables regression modeling to predict traffic volume based on temporal, meteorological, and event/holiday features.  
- **Features:**
    - `holiday` — Name of holiday for the record, or None if not a holiday (categorical)
    - `temp` — Temperature in Kelvin (float)
    - `rain_1h` — Rainfall in the previous hour (mm, float)
    - `snow_1h` — Snowfall in the previous hour (mm, float)
    - `clouds_all` — Cloud coverage (% from 0 to 100, integer)
    - `weather_main` — Main weather category (Clear, Clouds, Rain, etc.)
    - `weather_description` — Detailed weather description (string)
    - `date_time` — Timestamp of data point (format: YYYY-MM-DD HH:MM:SS)
    - `traffic_volume` — Number of cars passing the site in an hour (target variable)

---

## Repository Structure
    ├── data/ # Raw and cleaned datasets   
    ├── notebooks/ # Jupyter notebooks for tutorials and analysis   
    ├── src/ # Source code (feature engineering, models, utils)   
    ├── docs/ # Additional documentation, reports, or slides    
    ├── README.md    
    └── requirements.txt # Python dependencies


## 📝 Getting Started

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Mahdi-Farhani/Urban_Traffic_Volume_Prediction.git
   cd automobile-MPG-prediction
2. **Install required packages:**
   ```bash
   pip install -r requirements.txt
3. **Run jupyter Notebook:**   
    ```bash
    jupyter notebook
    ```
    ### or

    ```bash
    jupyter lab
    ```

4. **Open the main notebook in the notebooks/ directory.**

## Prerequisites
    Python 3.8+
    Jupyter Notebook / Jupyter Lab
    Data science libraries: numpy, pandas, scikit-learn, matplotlib, seaborn, etc.

## 🎯 Learning Goals
Understand the End-to-End ML Workflow on Tabular Real-World Data

Load, inspect, and explore the Metro Interstate Traffic Volume dataset.
Identify real-world challenges in urban traffic prediction.
Master Feature Engineering for Time-Series and Categorical Data

Convert timestamps into meaningful time-based features (hour, day of week, holidays, season, etc.).
Integrate weather and road condition information into the feature set.
Develop Skills for Outlier Detection and Data Cleaning

Identify and handle outliers and anomalies in traffic data.
Address missing values and inconsistent entries.
Apply Advanced Preprocessing Techniques

Encode categorical variables for modeling.
Scale or transform features to improve model performance.
Build, Regularize, and Compare Regression Models

Train baseline models (Linear Regression) and regularized versions (Ridge, Lasso).
Understand how regularization helps prevent overfitting.
Explore and Evaluate Nonlinear Models

Implement and compare tree-based models such as Random Forest and XGBoost.
Analyze feature importances for model interpretability.
Perform Model Evaluation and Result Visualization

Use appropriate regression metrics (MAE, RMSE, R² Score).
Visualize predictions, residuals, and error distributions.
Document, Present, and Communicate Results Effectively

Practice best practices in scientific and educational documentation.
Prepare code, analysis, and insights suitable for sharing with peers or including in a book.

## License
This project is licensed under the MIT License.


## Author
    Name : Mahdi Farhani  
    Position : Senior Software Developer, Ph.D. student (AI)

## 🤝 Contribution
    Feel free to fork, star, or open issues/pull requests.

## Acknowledgements
    UCI Machine Learning Repository   
    scikit-learn, pandas, matplotlib, seaborn contributors   
    Workshop participants and reviewers   