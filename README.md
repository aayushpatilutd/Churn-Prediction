# Telecom Customer Churn Prediction

This project aims to predict customer churn for a telecom company using machine learning techniques. The dataset contains customer usage data and demographic information to analyze factors contributing to churn.

## Dataset

The dataset consists of two main CSV files:

1. `telecom_usage.csv`: Contains customer usage data including:
   - Customer ID
   - Number of calls made
   - Number of SMS sent
   - Data used (in MB)
   - Churn status (1 for churned, 0 for retained)

2. `telecom_demographics.csv`: Contains customer demographic information including:
   - Customer ID
   - Telecom partner
   - Gender
   - Age
   - State
   - City
   - Pincode
   - Registration date
   - Number of dependents
   - Estimated salary


```

## Getting Started

1. Clone this repository:
   ```
   git clone https://github.com/your-username/telecom-churn-prediction.git
   ```

2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Open and run the Jupyter notebook `Churn_Prediction_Logistic-Regression-and-Random-Forest.ipynb` to see the analysis and model development process.

## Models

The project uses two main models for churn prediction:

1. Logistic Regression
2. Random Forest

These models are trained on the combined dataset of usage and demographic information to predict customer churn.

## Contributing

Contributions to improve the project are welcome. Please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Make your changes
4. Commit your changes (`git commit -am 'Add some feature'`)
5. Push to the branch (`git push origin feature/your-feature`)
6. Create a new Pull Request

