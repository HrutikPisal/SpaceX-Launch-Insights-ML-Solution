# SpaceX Launch Insights ML Solution

> **End-to-End Machine Learning Pipeline for Predicting Falcon 9 First Stage Landing Success**

An end-to-end Machine Learning project that predicts the landing success of SpaceX Falcon 9 first-stage boosters using historical launch data collected from the SpaceX REST API and Wikipedia. The project demonstrates the complete data science lifecycle—from data collection and preprocessing to model training, evaluation, and interactive visualization.

---

# Overview

Reusable Falcon 9 boosters have significantly reduced the cost of space launches. Predicting whether a booster will successfully land can help estimate mission costs and success probabilities.

This project builds an end-to-end machine learning workflow to analyze historical SpaceX launch data and predict first-stage landing outcomes.

---

# Objectives

* Collect launch data from multiple public sources.
* Clean and preprocess real-world datasets.
* Perform exploratory data analysis (EDA).
* Engineer meaningful features.
* Train and compare multiple classification models.
* Evaluate model performance.
* Build interactive dashboards for launch analytics.

---

# Dataset

Data was collected from:

* SpaceX REST API
* Wikipedia (BeautifulSoup Web Scraping)
* Launch site information
* Booster versions
* Payload information
* Orbit information
* Landing outcomes

---

# Project Workflow

```text
SpaceX API + Wikipedia
            │
            ▼
     Data Collection
            │
            ▼
   Data Cleaning & Wrangling
            │
            ▼
 Exploratory Data Analysis
            │
            ▼
 Feature Engineering
            │
            ▼
 Machine Learning Models
            │
            ▼
 Hyperparameter Tuning
            │
            ▼
 Model Evaluation
            │
            ▼
Interactive Dashboards
```

---

# Technologies Used

## Programming

* Python
* SQL

## Machine Learning

* Scikit-learn
* Logistic Regression
* Support Vector Machine (SVM)
* Decision Tree
* K-Nearest Neighbors (KNN)

## Data Analysis

* Pandas
* NumPy

## Visualization

* Plotly Dash
* Folium
* Matplotlib

## Data Collection

* SpaceX REST API
* BeautifulSoup
* Requests

---

# Exploratory Data Analysis

Performed detailed analysis on:

* Launch success trends
* Payload mass
* Flight number
* Launch site performance
* Orbit analysis
* Booster versions
* Landing outcomes

SQL queries were used to generate business insights from launch datasets.

---

# Machine Learning

Implemented and compared multiple supervised learning algorithms:

* Logistic Regression
* Support Vector Machine (SVM)
* Decision Tree Classifier
* K-Nearest Neighbors (KNN)

Used GridSearchCV for hyperparameter optimization and model selection.

---

#  Model Evaluation

Evaluation metrics:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix
* Cross Validation

# Visualizations

The project includes:

* Interactive Plotly Dash Dashboard
* Launch Success Analysis
* Payload Mass Trends
* Orbit Analysis
* Launch Site Comparison
* Folium Geospatial Maps

---

# Skills Demonstrated

* Machine Learning
* Predictive Analytics
* Classification Algorithms
* Feature Engineering
* Exploratory Data Analysis
* SQL
* REST API Integration
* Web Scraping
* Data Visualization
* Hyperparameter Tuning
* Model Evaluation
* Python Development

---

# Key Outcomes

* Built an end-to-end Machine Learning pipeline.
* Achieved **88% prediction accuracy** on Falcon 9 landing prediction.
* Applied feature engineering to improve predictive performance.
* Developed interactive dashboards for launch analytics.
* Gained practical experience with real-world data collection, preprocessing, visualization, and model evaluation.

---

# 🔮 Future Improvements

* Deploy the trained model using FastAPI.
* Containerize the application with Docker.
* Implement MLOps using MLflow.
* Add ensemble models such as Random Forest and XGBoost.
* Deploy the dashboard on Streamlit or Hugging Face Spaces.

---

# 🧰 Tech Stack

Python • SQL • Pandas • NumPy • Scikit-learn • Plotly Dash • Folium • BeautifulSoup • Requests • Jupyter Notebook

---

## 👨‍💻 Author

**Hrutik Pisal**

AI Engineer | Machine Learning Engineer | Generative AI Enthusiast

* GitHub: https://github.com/HrutikPisal
* LinkedIn: https://linkedin.com/in/hrutik-p
# IBM-Applied Data Science Capstone
