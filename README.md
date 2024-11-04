

# Credit Card Fraud Detection with R

Welcome to the **Credit Card Fraud Detection** project repository! This project aims to detect fraudulent credit card transactions using machine learning techniques implemented in R. The goal is to build and evaluate models that identify fraudulent activities to minimize potential losses and enhance security.

## Table of Contents

- [Project Overview](#project-overview)
- [Installation](#installation)
- [Dataset](#dataset)
- [Usage](#usage)
- [Model Training](#model-training)
- [Evaluation](#evaluation)
- [License](#license)

## Project Overview

This project uses machine learning algorithms to detect credit card fraud by analyzing a dataset of transaction records. Various classification models are trained and evaluated to accurately predict fraudulent transactions. The project is implemented in R and leverages libraries such as `tidymodels`, `ggplot2`, and `dplyr` for data manipulation, visualization, and model building.

## Installation

To run this project locally, ensure you have R installed. You will also need to install the following R packages:

```R
install.packages(c("tidymodels", "ggplot2", "dplyr", "data.table", "caret", "xgboost"))
```

Clone the repository:

```bash
git clone https://github.com/Jencheng1/CreditCardFraudR.git
cd CreditCardFraudR
```

## Dataset

The dataset used for this project contains credit card transaction records, including information on whether each transaction is fraudulent or legitimate. The dataset is imbalanced, with a higher proportion of legitimate transactions compared to fraudulent ones.

> **Note**: The dataset is not included in this repository. Please refer to [Kaggle's Credit Card Fraud Detection dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud) to download the dataset.

## Usage

1. Clone the repository and navigate to the project directory.
2. Open the provided Jupyter Notebook (`CreditCardFraudwithR_CapstoneProject_JenniferCheng.ipynb`) to explore the project workflow.
3. Follow the notebook's instructions to preprocess data, train models, and evaluate performance.

```bash
# Run Jupyter Notebook
jupyter notebook CreditCardFraudwithR_CapstoneProject_JenniferCheng.ipynb
```

## Model Training

The project explores several machine learning algorithms, including:

- Logistic Regression
- Decision Trees
- Random Forests
- XGBoost

Each model is trained and optimized using cross-validation to ensure robustness. The notebook provides detailed explanations of each step in the process, from data preprocessing to model selection.

## Evaluation

Model performance is evaluated using metrics such as:

- Accuracy
- Precision
- Recall
- F1 Score
- Area Under the Curve (AUC)

Confusion matrices and ROC curves are also plotted to visualize model performance and handle the imbalance in data effectively.

## License

This project is licensed under the MIT License. See the [LICENSE](https://www.mit.edu/~amini/LICENSE.md) file for more details.
