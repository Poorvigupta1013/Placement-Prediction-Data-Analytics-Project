#  Placement Prediction – Data Analytics Project

## Overview

This project focuses on analyzing and predicting **student placements** using a real-world dataset from a college environment. By applying data cleaning, exploratory data analysis (EDA), and machine learning, we aim to uncover the key factors that contribute to successful placement outcomes.

---

##  Dataset used

-<a href= "https://github.com/Poorvigupta1013/Placement-Prediction-Data-Analytics-Project/commit/98fa571d40bb35ca193227da5ccfce19f023bbeb">Dataset</a>

## Key Features:
- `IQ`: Student's IQ score  
- `Prev_Sem_Result`: Previous semester results  
- `CGPA`: Final CGPA  
- `Academic_Performance`: Overall academic score  
- `Internship_Experience`: Internship experience (0 = No, 1 = Yes)  
- `Extra_Curricular_Score`: Score from non-academic activities  
- `Communication_Skills`: Communication skill rating  
- `Projects_Completed`: Number of completed academic projects  
- `Placement`: Target variable (0 = Not Placed, 1 = Placed)

---

## Objectives

- Clean and preprocess the data (remove nulls/outliers)
- Perform Exploratory Data Analysis (EDA)
- Visualize key trends and insights
- Train a machine learning model to predict placement
- Identify top features influencing placement outcomes

---

## Tools & Technologies

- Language: Python  
- Libraries: Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn  
- Model: Random Forest Classifier  
- IDE: Goggle collab Notebook / VS Code  

---

## Exploratory Data Analysis (EDA)

Key visualizations created:
- Placement distribution (Pie & Count Plots)
- CGPA and IQ comparisons by placement
- Boxplots of communication, GPA, extracurriculars
- Correlation heatmap of all numeric features
- Internship and project impact on placement

Combined visual summary of all plots saved as:  
<a herf ="https://github.com/Poorvigupta1013/Placement-Prediction-Data-Analytics-Project/blob/main/EDA%20image%20of%20Placement%20dataset">View visual</a>

---

## Model Training

- Features were encoded using `LabelEncoder` where necessary.
- Used `RandomForestClassifier` for classification.
- Model was evaluated using:
  - Accuracy
  - Confusion Matrix
  - Classification Report
  - Feature Importance Graph

---

## Results

- The model was able to accurately predict student placement.
- Key influencing factors identified:
  - CGPA
  - Communication Skills
  - Internship Experience
  - Projects Completed

---

## Project Structure

```
placement-prediction/
├── data/
│   └── college_student_placement_dataset.csv
├── notebooks/
│   └── placement_prediction_analysis.ipynb
├── plots/
│   └── placement_eda_combined_plot.png
├── README.md
└── requirements.txt
```

---

## Future Enhancements

- Try different ML models (Logistic Regression, XGBoost, etc.)
- Add Streamlit or Flask-based web app for interactive prediction
- Tune hyperparameters using GridSearchCV

---

## Contributions

Contributions are welcome! If you'd like to add new features, suggest improvements, or report bugs, feel free to open an issue or submit a pull request.

---


