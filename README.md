# Titanic Dataset - Data Cleaning & Preprocessing

This project focuses on cleaning and preprocessing the Titanic dataset to make it suitable for machine learning. It includes handling missing values, outlier detection/removal, feature encoding, normalization, and visual exploration.

## Dataset
- **Source:** `task1_Titanic-Dataset.csv` (standard Titanic dataset)
- **Features Used:** Pclass, Age, SibSp, Parch, Fare, Sex, Embarked, Survived

## Cleaning & Preprocessing Steps

1. **Initial Inspection**  
   - Displayed dataset info and summary statistics
   - Dropped irrelevant columns: `PassengerId`, `Name`, `Ticket`, `Cabin`

2. **Outlier Handling**  
   - Visualized and removed outliers using the IQR method on numerical columns (`Age`, `Fare`, etc.)

3. **Missing Values**  
   - Imputed missing numerical values with **median**
   - Imputed missing categorical values with **mode**

4. **Visualization**  
   - Pie charts for categorical distributions
   - Histograms and boxplots before & after outlier handling
   - Correlation heatmap

5. **Encoding & Normalization**  
   - Categorical columns encoded using `LabelEncoder`
   - Numerical columns normalized using `StandardScaler`

6. **Export**  
   - Saved cleaned dataset as `cleaned_titanic.csv`

## Libraries Used
- `pandas`, `numpy`, `matplotlib`, `seaborn`
- `sklearn.preprocessing`: `LabelEncoder`, `StandardScaler`

## Output
- `cleaned_titanic.csv`: Cleaned and preprocessed dataset ready for machine learning.

## Author
- **Madhavendra Singh**
