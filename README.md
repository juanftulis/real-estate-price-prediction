# Real Estate Price Prediction Using Machine Learning

## Project Overview

This project aims to predict real estate prices in Buenos Aires, Argentina, using Machine Learning regression algorithms.

The main objective is to compare different predictive models, evaluate their performance, and explore how property characteristics and feature engineering contribute to price prediction.

## Dataset

The project uses a real estate dataset from Properati, containing approximately **79,755 property records** from Buenos Aires (CABA).

The target variable is the property price expressed in US dollars (USD).

## Methodology

The project includes:

- **Exploratory Data Analysis (EDA):** Descriptive statistics, data visualization, and analysis of property characteristics.
- **Data Preprocessing:** Data cleaning, transformation, and preparation for predictive modeling.
- **Feature Engineering:** Incorporation and transformation of features, including information extracted from property descriptions.
- **Model Training:** Implementation and comparison of Machine Learning regression algorithms.
- **Model Evaluation:** Evaluation using Root Mean Squared Error (RMSE).
- **Cross-Validation:** 10-fold cross-validation to compare model performance.

## Machine Learning Models

The following regression algorithms were evaluated:

1. Linear Regression
2. Random Forest Regressor
3. Gradient Boosting Regressor
4. Stacking Regressor

## Model Comparison

The following results were obtained using 10-fold cross-validation:

| Model | RMSE (USD) |
|---|---:|
| Stacking Regressor | 32,192 |
| Random Forest | 32,245 |
| Gradient Boosting | 38,317 |
| Linear Regression | 51,170 |

**Stacking Regressor achieved the lowest average RMSE**, although its performance was very similar to Random Forest.

These results suggest that ensemble methods can be effective for predicting property prices.

## Technologies Used

- Python
- pandas
- NumPy
- scikit-learn
- Matplotlib
- Seaborn
- Google Colab

## Conclusions

This project demonstrates the application of supervised Machine Learning techniques to a real-world regression problem.

The comparison highlights the value of feature engineering, ensemble methods, and cross-validation when developing predictive models.

Although Stacking achieved the lowest RMSE, its improvement over Random Forest was small, suggesting that model complexity should also be considered when selecting a final solution.

## Future Improvements

Potential improvements include:

- Incorporating additional geographic and neighborhood-level features.
- Exploring more advanced text-based feature extraction.
- Evaluating additional regression algorithms.
- Testing model performance on newer real estate data.
- Developing an interactive price prediction application.

## Author

**Juan Cruz Ftulis**

Mathematics Graduate | Data Analytics & Machine Learning
