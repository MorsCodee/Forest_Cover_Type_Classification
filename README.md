
# Multi-Class Classification with Random Forest & XGBoost 🌳⚡

This project is part of my internship task where I learned how to train and evaluate **multi-class classification models** using **Random Forest** and **XGBoost**.

---

## Project Overview
The main goals of this project were:
1. Train and evaluate multi-class classification models.  
2. Visualize confusion matrix and feature importance.  
3. Bonus: Compare Random Forest vs. XGBoost.  
4. Bonus: Perform hyperparameter tuning for better results.  

---

## Dataset
- The dataset contains **features (columns)** describing samples and a **target column** with multiple classes (labels).
- Features = first 54 columns  
- Target = last column (multi-class labels)  

---

## Steps Performed

### 1. Data Preprocessing
- Loaded dataset into Pandas DataFrame.  
- Assigned proper column names (`feature_1`, `feature_2`, …, `feature_54`, `target`).  
- Split data into **features (X)** and **target (y)**.  
- Train-test split (80% train, 20% test).  

### 2. Model Training
- Trained a **Random Forest Classifier**.  
- Trained an **XGBoost Classifier**.  

### 3. Model Evaluation
- Calculated **Accuracy**.  
- Generated **Classification Report** (Precision, Recall, F1-score).  
- Plotted **Confusion Matrix**.  
- Visualized **Feature Importance**.  

### 4. Model Comparison
- Compared Random Forest vs. XGBoost side by side.  
- Observed differences in accuracy, precision, and F1-score.  

### 5. Hyperparameter Tuning
- Used **GridSearchCV** and **RandomizedSearchCV** to find better parameters for XGBoost.  
- Improved performance by tuning parameters like `n_estimators`, `max_depth`, `learning_rate`.  

---

## Results

- **Random Forest**: Simple to train, decent accuracy.  
- **XGBoost**: Higher accuracy and better overall performance after tuning.  

| Model          | Accuracy | Notes                           |
|----------------|----------|---------------------------------|
| Random Forest  | XX%      | Faster but less accurate        |
| XGBoost        | XX%      | Slightly slower, higher accuracy|

---

## Technologies Used
- Python 🐍  
- Pandas & NumPy  
- Scikit-learn  
- Matplotlib & Seaborn (for visualization)  
- XGBoost  

---

## How to Run
1. Clone this repo:
   ```bash
   git clone https://github.com/MorsCodee/Forest_Cover_Type_Classification.git
````

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook / Python script to train and evaluate models.

---

## Learnings

* Understood **boosting** and how **XGBoost** works internally.
* Learned the importance of **confusion matrices** and **feature importance** in classification.
* Practiced **hyperparameter tuning** to improve model performance.
* Compared different ML models to see their strengths and weaknesses.

---

## Contributing

This is a learning project — suggestions and improvements are always welcome!
```
