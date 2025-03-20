# Titatanic-Survival
# Titanic Survival Prediction

## Overview
This project predicts passenger survival on the Titanic using machine learning. The model is built with **Random Forest Classifier** and evaluates survival probabilities based on passenger details.

## Dataset
The dataset includes:
- **Passenger Information**: Age, Gender, Embarked Location
- **Ticket Details**: Fare, Class
- **Target Variable**: `Survived` (1 = Survived, 0 = Not Survived)

## Preprocessing Steps
1. **Data Cleaning**:
   - Dropped unnecessary columns (`Name`, `Ticket`, `Cabin`).
   - Handled missing values (`Age`, `Embarked`, `Fare`) with median/mode imputation.
2. **Encoding Categorical Features**:
   - Converted `Sex` and `Embarked` into numerical values.
3. **Feature Scaling**:
   - Standardized numerical features for better model performance.

## Model Selection
The **Random Forest Classifier** is used due to its robustness and accuracy in classification tasks.

## Model Evaluation
The model is assessed using:
- **Accuracy Score**
- **Classification Report** (Precision, Recall, F1-score)

## Installation & Usage
### **Requirements**
Ensure you have the necessary libraries installed:
```sh
pip install pandas numpy scikit-learn seaborn matplotlib
```

### **Running the Notebook**
1. Open Jupyter Notebook:
   ```sh
   jupyter notebook
   ```
2. Load `Titanic Survival.ipynb` and execute all cells.

## Future Improvements
- Experiment with feature engineering (family size, deck extraction, etc.).
- Test other models like Logistic Regression or XGBoost.
- Deploy as a web application for interactive predictions.

## Repository Structure
```
📁 Titanic-Survival
│── Titanic Survival.ipynb  # Jupyter Notebook with model implementation
│── tested.csv              # Dataset file
│── README.md               # Project documentation
```

## License
This project is open-source and available for educational and research purposes.
