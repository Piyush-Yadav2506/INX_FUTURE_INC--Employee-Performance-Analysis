# INX Future Inc - Employee Performance Analysis

This project aims to analyze and predict employee performance at INX Future Inc using machine learning on real-world HR data. The workflow covers data preparation, modeling, and actionable business recommendations.

## Project Structure

* **Project_Summary**: Contains summary notebooks with problem statement, methodology, and recommendations.
* **artifacts**: Includes saved models (`xgb_model.pkl`), encoders, and metrics.
* **data**: Datasets for EDA, training, and evaluation.
* **src**: Modular code for cleaning, feature engineering, and modeling.
* **requirements.txt**: Required Libraries to run this project.

## Steps to Use

### 1. Clone the Repository
```bash
git clone https://github.com/Piyush-Yadav2506/INX_FUTURE_INC--Employee-Performance-Analysis
cd INX_FUTURE_INC--Employee-Performance-Analysis
```

### 2. Understand Project Approach

* Review the notebooks in `Project_Summary` for problem background, EDA, and recommendations.
* Key business drivers: Salary hike, satisfaction, work-life balance, promotion history.

### 3. Data Preparation

* Dataset cleaned and processed for outliers, missing values, and feature encoding.
* Tools used: Label Encoding, OneHot Encoding, Standard Scaling with `ColumnTransformer`.

### 4. Model Training

* Several algorithms evaluated (Logistic Regression, SVM, Random Forest, XGBoost).
* XGBoost selected for best predictive power and robustness.
* Artifacts like `xgb_model.pkl` and preprocessor objects saved in `artifacts`.

### 5. Evaluation & Recommendation

* Business insights and actionable suggestions for HR/Management are provided in the summary notebook.
* Visualizations available in the notebooks to compare model performances and feature importance.

## Highlights

* Automated EDA with Sweetviz.
* Modular and reproducible Jupyter notebooks.
* Emphasis on actionable recommendations for stakeholders.

## Author

**Piyush Yadav**  
Aspiring Data Scientist  
📧 Email: piyushyadav416@gmail.com  
📍 Location: Pune, Maharashtra, India  
💼 LinkedIn: [Piyush-Yadav2506](https://linkedin.com/in/Piyush-Yadav2506)
