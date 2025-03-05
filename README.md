# Diamond Price Prediction

## Project Overview

This project aims to predict the price of diamonds based on various features using data analysis and machine learning techniques. By leveraging **Exploratory Data Analysis (EDA)** and machine learning models, I built an effective pricing model that can assist in determining diamond prices accurately.

---

## Dataset

The dataset used in this project consists of various attributes of diamonds, including:

- **carat**: Weight of the diamond (0.2–5.01)
- **cut**: Quality of the cut (Fair, Good, Very Good, Premium, Ideal)
- **color**: Diamond color, from J (worst) to D (best)
- **clarity**: Measurement of how clear the diamond is (I1 (worst), SI2, SI1, VS2, VS1, VVS2, VVS1, IF (best))
- **x**: Length in mm (0–10.74)
- **y**: Width in mm (0–58.9)
- **z**: Depth in mm (0–31.8)
- **depth**: Total depth percentage = z / mean(x, y) = 2 * z / (x + y) (43–79)
- **table**: Width of the top of the diamond relative to the widest point (43–95)

---

## Methodology

### 1. Data Preprocessing
- Handled missing values (if any).
- Converted categorical features into numerical values using encoding techniques.
- Normalized and scaled numerical data where necessary.

### 2. Exploratory Data Analysis (EDA)
- Performed univariate and multivariate analysis to understand feature distributions.
- Visualized correlations using heatmaps and scatter plots.
- Identified outliers using boxplots and statistical methods.

### 3. Machine Learning Models
- **Linear Regression**: To understand the linear relationship between features and price.
- **Random Forest Regressor**: To capture non-linear relationships and improve accuracy.
- **Gradient Boosting Regressor**: To enhance predictions using boosting techniques.
- **XGBoost**: To optimize performance with an advanced boosting algorithm.

### 4. Model Evaluation
- Used metrics like **Mean Squared Error (MSE)** and **R-squared** to assess model performance.
- Compared the results of different models to determine the best-performing one.

---

## Technologies Used

- **Python**
- **Pandas**, **NumPy**
- **Seaborn**, **Matplotlib**
- **Scikit-learn**
