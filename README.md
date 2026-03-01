# Heart Disease Prediction

**Organization:** DevelopersHub Corporation  
**Domain:** Artificial Intelligence & Machine Learning  

## Objective
The objective of this project is to build a classification model that predicts whether a person is at risk of heart disease based on their medical history and health metrics. This task utilizes the **Heart Disease UCI Dataset**.

## Tech Stack & Libraries
* **Language:** Python
* **Data Manipulation:** Pandas
* **Data Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn

## Key Skills & Methodologies Demonstrated
* **Data Cleaning & Preprocessing:** Handled missing values and converted categorical text variables into dummy/indicator variables (`get_dummies`) for machine learning compatibility.
* **Exploratory Data Analysis (EDA):** Visualized the distribution of the target variable and mapped relationships between health metrics (e.g., Age vs. Max Heart Rate).
* **Binary Classification:** Trained a **Decision Tree Classifier** to categorize patients into "At Risk" (1) or "No Risk" (0).
* **Model Evaluation:** * Calculated overall prediction **Accuracy**.
  * Generated a **Confusion Matrix** to analyze true positives, true negatives, false positives, and false negatives.
  * Plotted the **ROC Curve** and calculated the **AUC (Area Under the Curve)** to evaluate the model's diagnostic ability.
* **Feature Importance:** Extracted and visualized the top health metrics that the decision tree relied on most heavily to make its predictions.
