# Analysis and Prediction of Arterial Abnormalities in CABG Patients

This repository contains code and analysis for a consulting project focused on predicting radial artery medial calcification and internal thoracic artery intimal abnormality in patients undergoing coronary artery bypass graft (CABG) surgery. Machine learning techniques are employed to assess associations between patient characteristics and arterial conditions, aiding in early intervention and personalized care strategies.

## Project Structure

- **main.ipynb**: Jupyter notebook containing data preprocessing, feature engineering, model training, and evaluation. It includes a detailed breakdown of the steps taken and model performance metrics.
- **requirements.txt**: List of necessary Python packages and dependencies for running the notebook.

## Key Steps

1. **Data Preprocessing**:
   - Handled missing values with mean/mode imputation.
   - Encoded categorical variables (e.g., gender, diabetes) for model compatibility.
   - Created target variable based on arterial abnormality combinations.

2. **Exploratory Data Analysis**:
   - Analyzed distribution across target groups.
   - Visualized key patient variable relationships.

3. **Model Training**:
   - Multiple models tested: SVM, K-Nearest Neighbors (KNN), Random Forest, Gradient Boosting, Decision Tree, ANN, and Logistic Regression.
   - SMOTE applied to balance class distributions for better model performance.
   - Grid search used to optimize model hyperparameters.

4. **Results**:
   - Best model achieved an accuracy of 88.89% using SVM with a linear kernel.
   - Precision, recall, and F1-score reported for each patient group.

## Installation

Clone the repository and install required packages:

```bash
git clone https://github.com/yourusername/CABG-patient-arterial-prediction.git
cd CABG-patient-arterial-prediction
pip install -r requirements.txt
```

##Usage
Run the Jupyter notebook:

```bash
jupyter notebook mian.ipynb
```

For a detailed walk-through of the code and model results, please refer to mian.ipynb. While the notebook demonstrates the project workflow, some model parameters and steps may vary. If any clarification is needed, please feel free to reach out.

##Notes
This repository provides a thorough approach for exploring and predicting arterial abnormalities, with potential adjustments based on client requirements.
