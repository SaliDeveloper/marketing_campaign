# Customer Analytics with Machine Learning

This project presents a comprehensive approach to customer data analysis using machine learning techniques. By processing and analyzing key features in a customer dataset, this project demonstrates the use of regression and classification models to understand customer behavior and predict outcomes.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Feature Engineering](#feature-engineering)
- [Modeling](#modeling)
- [Evaluation](#evaluation)
- [Privacy and Sensitivity Analysis](#privacy-and-sensitivity-analysis)
- [Installation](#installation)
- [Usage](#usage)
- [Contributions](#contributions)
- [License](#license)

---

## Project Overview

This project aims to perform a thorough analysis of a customer dataset, including feature engineering, data preprocessing, and building predictive models. The analysis provides insights into customer behaviors, key correlations, and significant features affecting customer actions. Additionally, advanced privacy-preserving techniques are used to ensure data security.

## Dataset

The dataset includes 20 features representing various customer attributes, both numerical and categorical. Key attributes are explored to understand their relationships with the target variable.

## Data Preprocessing

Data preprocessing steps involve handling missing values, scaling, encoding categorical features, and normalizing numerical features:

- **Missing Data Handling**: Missing values were handled through various imputation methods, including mean, median, and advanced techniques like K-Nearest Neighbors (KNN) imputation.
- **Normalization and Standardization**: To ensure uniformity in data scales, numerical features were normalized and standardized, aiding in model convergence and performance.
- **Categorical Encoding**: Categorical variables were encoded using Label Encoding and One-Hot Encoding methods.

## Exploratory Data Analysis (EDA)

Exploratory Data Analysis provided insights into the relationships between features and the target variable, identifying patterns and significant correlations. Visualizations of data distributions and pairwise feature interactions helped in feature selection and model building.

## Feature Engineering

Key engineered features include:
- **Correlations**: Notable correlations were identified, such as between `MntCoffee` and the target variable, to enhance model predictability.
- **Data Imputation**: Missing data imputation methods varied depending on the amount and type of missing data for each feature.

## Modeling

### Regression
- **Simple Linear Regression**: Used to predict the target variable based on individual features like `MntCoffee` and `Income`.
- **Multiple Regression**: Enhanced prediction accuracy by including multiple features simultaneously. The models were evaluated using RMSE, MSE, and R-squared scores.

### Classification
- **Decision Trees**: Built for classification tasks, leveraging features that are most predictive of customer actions.
- **Boosting and Bagging Techniques**: Techniques like Gradient Boosting were applied to improve model robustness and performance.

### Model Validation
Cross-validation (K-Fold) was used to validate model accuracy and prevent overfitting.

## Evaluation

Models were evaluated based on several metrics:
- **Regression Models**: RMSE, MSE, and R-squared scores were used to measure accuracy.
- **Classification Models**: Precision, Recall, and Confusion Matrix were used for performance analysis in predicting customer classes.

## Privacy and Sensitivity Analysis

To protect data privacy, techniques like Laplace and Gaussian noise were applied, ensuring the privacy of sensitive attributes. These methods helped add noise while maintaining data patterns essential for analysis.

## Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/marketing_campaign.git
   cd customer-analytics-ml
   ```

2. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Open and run the Jupyter Notebook (`AI_CA4.ipynb`) to see the data processing steps, exploratory data analysis, feature engineering, and model building.
2. To test the models, execute each cell in the notebook and observe the output in each stage.

## Contributions

Contributions, suggestions, and improvements are welcome. Feel free to open issues or submit pull requests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
