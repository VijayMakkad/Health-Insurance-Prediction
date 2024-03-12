# Health Insurance Prediction using Linear Regression

This repository contains the code for predicting health insurance charges using linear regression. The model is built using the data set named `medical.csv`, which is already included in the code.

## Overview

Health insurance charges can vary significantly depending on various factors such as age, BMI, smoking habits, region, etc. Predicting these charges accurately can help insurance companies and individuals in making informed decisions regarding insurance coverage and premiums.

In this project, we utilize linear regression to predict health insurance charges based on a set of features extracted from the `medical.csv` dataset.

## Data

The `medical.csv` dataset contains the following columns:

- Age: Age of the individual
- Sex: Gender of the individual (male/female)
- BMI: Body Mass Index of the individual
- Children: Number of children/dependents covered by the insurance
- Smoker: Whether the individual is a smoker or not (yes/no)
- Region: The region where the individual resides
- Charges: Health insurance charges incurred by the individual

## Requirements

To run the code in this repository, you'll need:

- Python 3.x
- Jupyter Notebook
- Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

You can install the required libraries using pip:

```
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Usage

1. Clone the repository:

```
git clone https://github.com/VijayMakkad/Health-Insurance-Prediction
```

2. Navigate to the repository directory:

```
cd health-insurance-prediction
```

3. Open the Jupyter Notebook file `Health_Insurance_Prediction.ipynb`:

```
jupyter notebook Health_Insurance_Prediction.ipynb
```

4. Follow the instructions provided in the notebook to train the linear regression model and make predictions.

## Results

The trained linear regression model achieves a certain level of accuracy in predicting health insurance charges based on the provided features. The results and evaluation metrics are discussed in detail within the Jupyter Notebook.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
