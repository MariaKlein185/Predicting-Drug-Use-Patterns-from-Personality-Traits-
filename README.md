# Predicting Drug Use Patterns from Personality Traits
This project explores whether personality traits and demographic information can help predict drug use patterns. I used the Drug Consumption dataset, which includes participant demographics, personality scores, impulsivity, sensation-seeking, and reported substance use.

## Project Overview
I cleaned and processed the dataset, explored relationships between participant traits and drug consumption, and built machine learning models to predict substance use across different drug categories. The goal was to understand how psychological and behavioral traits relate to drug-use patterns.

## Built With
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- PyTorch
- SHAP
- Jupyter Notebook

## Files
- `data-processing.ipynb` — cleans, encodes, scales, and prepares the dataset
- `eda-and-visuals.ipynb` — explores demographics, personality traits, and drug-use trends
- `Midterm Logistic Regression Analysis.ipynb` — builds and evaluates logistic regression models
- `mlp-neural-network.ipynb` — trains and evaluates a neural network model
- `Participant_Drug_Usage.ipynb` — analyzes participant-level drug usage
- `drug_consumption.csv` — original dataset
- `processed_drug_consumption.csv` — cleaned dataset
- `model.pth` — saved PyTorch model

## Usage
Install the required packages:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn torch shap

Run the notebooks in this order:

1. data-processing.ipynb
2. eda-and-visuals.ipynb
3. Midterm Logistic Regression Analysis.ipynb
4. mlp-neural-network.ipynb
5. Participant_Drug_Usage.ipynb
Results

The models showed that personality and behavioral traits can provide useful signals for predicting drug-use patterns, though performance varies by substance category. Features such as impulsivity, sensation-seeking, and personality scores were especially important in understanding the predictions.

Note

This project is exploratory and should not be used for diagnosis or individual risk assessment. It is meant to demonstrate how psychological and demographic data can be cleaned, analyzed, and modeled with machine learning.
