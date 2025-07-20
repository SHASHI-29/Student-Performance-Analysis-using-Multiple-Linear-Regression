# 📊 Student Performance Analysis using Multiple Linear Regression

This project uses **Multiple Linear Regression** to analyze and predict student performance based on various academic, personal, and social factors. The dataset includes attributes such as study hours, sleep time, extracurricular activities, and more, with the goal of predicting the **Performance Index** of a student.

## 🧰 Built With
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 📁 Dataset
The dataset is sourced from the repository:
[`Student_Performance.csv`](https://github.com/SHASHI-29/Student-Performance-Analysis-using-Multiple-Linear-Regression/blob/main/Student_Performance.csv)

## 📌 Features Used
- Study Hours
- Sleep Time
- Previous Scores
- Extracurricular Activities
- Sample Question Papers Practiced
- Performance Index (Target)

## 📈 Workflow

1. **Data Preprocessing**
   - Loaded dataset using `pandas`
   - Encoded categorical features (e.g., *Extracurricular Activities*)
   - Visualized relationships between features and target using `matplotlib` and `seaborn`

2. **Correlation Analysis**
   - Generated a heatmap to observe feature correlations
   - Selected features with correlation > 0.2 with the Performance Index

3. **Feature Scaling**
   - Applied `MinMaxScaler` to normalize feature values

4. **Model Training & Evaluation**
   - Trained a **Linear Regression** model using Scikit-learn
   - Evaluated with:
     - `R² Score`
     - `Mean Absolute Error (MAE)`

## 📊 Visualizations

### 🔍 Feature vs Performance Index
Scatter plots to observe trends between features and performance.

### 🔥 Correlation Heatmap
Shows how strongly each feature correlates with the target.

## 🧪 Results

- **R² Score**: _[Varies based on random split]_
- **Mean Absolute Error**: _[Depends on data sample]_

## 🚀 Future Improvements
- Try **Polynomial Regression** or **Random Forest** for better accuracy.
- Include more features like socioeconomic factors, family background, etc.
- Deploy using Streamlit or Flask.
