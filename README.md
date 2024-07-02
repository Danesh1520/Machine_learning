
# Wind Power Prediction using Machine Learning, Deep Learning, Explainable AI

This project aims to predict wind power generation using various machine learning and deep learning models and enhance the model interpretability with Explainable AI (XAI) techniques. 

## Project Structure

- **Mini_Project_XAI.ipynb**: The Jupyter notebook containing all the code, analysis, and visualizations related to the wind power prediction project.

## Prerequisites

- Python 3.7+
- Jupyter Notebook
- Required libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn
  - tensorflow (or keras)
  - xgboost
  - shap (for explainable AI)

You can install the necessary libraries using the following command:

\`\`\`bash
pip install pandas numpy matplotlib seaborn scikit-learn tensorflow xgboost shap
\`\`\`

## Contents

### 1. Data Loading and Preprocessing
- Load the dataset
- Handle missing values
- Feature engineering
- Data normalization and scaling

### 2. Exploratory Data Analysis (EDA)
- Visualize the distribution of the data
- Analyze correlations between features

### 3. Model Building
- Train various machine learning models (e.g., Linear Regression, Decision Trees, XGBoost)
- Train deep learning models (e.g., Neural Networks)

### 4. Model Evaluation
- Evaluate models using appropriate metrics (e.g., MAE, RMSE, R²)
- Compare performance of different models

### 5. Explainable AI (XAI)
- Use SHAP (SHapley Additive exPlanations) to explain model predictions
- Visualize feature importance and contributions to predictions

## Usage

To run the notebook, execute the cells in order. Ensure that the dataset is correctly loaded and all necessary libraries are installed.

## Results

The notebook provides detailed results of the model performance and the interpretability of the predictions. Visualizations and metrics are included to help understand the effectiveness of the models.

## Acknowledgements

This project is inspired by the need for accurate and interpretable predictions in the field of renewable energy, specifically wind power generation.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.
