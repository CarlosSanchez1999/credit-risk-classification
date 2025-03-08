# Credit Risk Classification

## Overview
This project uses logistic regression to classify loan applications as either **healthy loans (0)** or **high-risk loans (1)**. The model is trained on a dataset of loan records and evaluates performance using precision, recall, and F1-score.

## Dataset
The dataset used for this project is stored in the `Resources` folder:
- **File:** `lending_data.csv`
- **Description:** This dataset contains loan application records with features that help determine whether a loan is **high risk (1)** or **healthy (0)**.

## Project Structure
```
📂 Credit Risk Classification
│── 📂 Resources
│   ├── lending_data.csv  # Dataset used for training and testing
│── credit_risk_classification.ipynb  # Jupyter Notebook with model implementation
│── README.md  # Project documentation (this file)
│── .jupyter_checkpoints/  # Auto-generated Jupyter notebook checkpoints
```

## Methodology
1. **Data Preprocessing**: Handling missing values, feature selection, and data scaling.
2. **Model Selection**: Logistic regression is used for classification.
3. **Evaluation Metrics**:
   - **Precision**: Measures the accuracy of positive predictions.
   - **Recall**: Measures the ability to identify high-risk loans.
   - **F1-Score**: Balances precision and recall.
   - **Accuracy**: Overall correctness of the model.

## Results
The model achieves **high accuracy (~99%)**, with excellent performance in predicting healthy loans. However, there is a small trade-off in precision for high-risk loans, which may require further tuning.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/credit-risk-classification.git
   cd credit-risk-classification
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open and run the Jupyter Notebook:
   ```bash
   jupyter notebook credit_risk_classification.ipynb
   ```
4. Ensure the dataset (`lending_data.csv`) is in the `Resources` folder before running the notebook.


