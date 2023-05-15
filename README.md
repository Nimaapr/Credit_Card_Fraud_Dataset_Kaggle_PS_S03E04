# Credit Card Fraud Detection - Kaggle Playground Series S3E4

## Project Description
This project is based on the Kaggle Playground Series S3E4, which involves building a model to predict fraudulent credit card transactions. The data is highly imbalanced and anonymized for privacy. This project is a great opportunity to apply and improve skills in data preprocessing, exploratory data analysis (EDA), and binary classification modeling.

## Getting Started

### Dependencies
- Python 3.x
- Libraries: numpy, pandas, matplotlib, seaborn, scikit-learn, xgboost

### Installation
1. Clone this repository.
2. Install required packages.


### Usage
1. Load the data (ensure the data is in the correct path or adjust the path accordingly).
2. Run the Jupyter notebook for data preprocessing, EDA, and modeling.

## Project Structure
This project consists of:
1. Data Preprocessing: Time feature is dropped from the dataset. Outliers are detected and removed using the IQR method. Duplicated values are also removed.
2. Exploratory Data Analysis: The distribution of features is visualized, class imbalance is checked, and correlations between features are explored.
3. Modeling: Several binary classification models are implemented, including Logistic Regression, Random Forest Classifier, Gradient Boosting Classifier, and XGBoost.

## Results
The results and performance of the models are evaluated using the classification report from the scikit-learn library.

## Acknowledgments
This project is based on the [Kaggle Playground Series S3E4](https://www.kaggle.com/c/playground-series-s3e4).

## License
This project is licensed under the MIT License.
