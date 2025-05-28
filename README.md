# Diabetes Prediction Using XGBoost

This project predicts diabetes risk using the Pima Indians Diabetes Dataset and an XGBoost classifier. It includes data exploration, model training, evaluation, and a prediction function.

## Project Overview
- **Dataset**: Pima Indians Diabetes Dataset (768 samples, 8 features, binary outcome).
- **Model**: XGBoost classifier with ~73.4% test accuracy.
- **Features**: Data preprocessing, confusion matrix, custom prediction function with 0.4 threshold.
- **Tools**: Python, pandas, scikit-learn, XGBoost, matplotlib, seaborn.

## How to Run
1. Clone the repository: `git clone https://github.com/your-username/DiabetesPrediction.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Open `Untitled2.ipynb` in Jupyter Notebook and run all cells.

## Dataset
The dataset (`diabetes (1).csv`) is required. Place it in the project directory or download from [Kaggle](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database).

## Results
- Test accuracy: ~73.4%
- Training accuracy: ~79.6%
- Challenges: Class imbalance, zero values in features.

## Future Improvements
- Impute zero values.
- Address class imbalance (e.g., SMOTE).
- Tune XGBoost hyperparameters.

## License
MIT License