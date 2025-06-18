# House Prices - Advanced Regression Techniques

Welcome to my first machine learning project!
This repository contains my implementation of a regularized linear regression model (Ridge Regression) from scratch to predict house prices for the Kaggle competition [House Prices - Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques).

---

## Files

* `House_Prices_Notebook.ipynb`: The full Kaggle notebook containing data preprocessing, model training, evaluation, and submission code.
* `submission.csv`: My final prediction file submitted to Kaggle.

---

## Techniques Used

* Data cleaning & preprocessing (handling missing values, encoding categorical variables)
* Feature normalization
* Manual implementation of **Ridge Regression**

  * Gradient descent with L2 regularization
  * Cost function with regularization term
* Log transformation of target (`SalePrice`)
* Evaluation via **RMSE (Root Mean Squared Error)**
* Submission to Kaggle leaderboard

---

## Result

* **Validation RMSE**: \~30,426
* **Public Kaggle Score**: 0.19353
  *(First successful submission!)*

---

## Getting Started

To run this notebook:

1. Open the `.ipynb` file in Jupyter, Kaggle, or Google Colab.
2. Follow along from data loading to final submission generation.

---

## ✍Author

**Ayub Yusuf**
Machine Learning Enthusiast | First project in ML portfolio

---

## Future Improvements

* Implement other models (e.g., Lasso, ElasticNet)
* Add automated feature selection
* Hyperparameter tuning

---

Thanks for viewing my project! 

Feel free to fork or star this repo if you'd like to follow my machine learning journey!
