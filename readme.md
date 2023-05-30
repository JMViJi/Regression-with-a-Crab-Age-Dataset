# Crab Age Prediction 

## Introduction
The Crab Age Prediction project aims to accurately predict the age of a crab based on its physical attributes. This prediction plays a crucial role in the commercial crab farming business where knowing the right time to harvest crabs is vital to ensure optimal resource utilization. The problem is framed as a regression problem, tackled using comprehensive exploratory data analysis, feature engineering, and robust regression modeling.

## Dataset
The dataset contains observations of crabs, each providing multiple physical attributes. These attributes include Sex, Length, Diameter, Height, Weight, Shucked Weight, Viscera Weight, Shell Weight, and Age. The data is clean with no missing or mismatched values.

## Dataset Features
- `Sex`: Gender of the crab, categorized as Male, Female, and Indeterminate.
- `Length`: Length of the crab in feet.
- `Diameter`: Diameter of the crab in feet.
- `Height`: Height of the crab in feet.
- `Weight`: Weight of the crab in ounces.
- `Shucked Weight`: Weight of the crab without the shell, in ounces.
- `Viscera Weight`: Weight of the crab's abdominal organs, in ounces.º
- `Shell Weight`: Weight of the crab's shell, in ounces.
- `Age`: Age of the crab, in months.

## Methodology
The following stages were employed in this project:

1. **Exploratory Data Analysis (EDA)**: Understand the distribution of data, correlations between different features, and detection of potential outliers or anomalies.
2. **Feature Engineering**: Generate new features that might improve the model's accuracy using combinations of existing features or transformations.
3. **Model Building**: Build various regression models like Linear Regression, Decision Trees, Random Forests, SVM, etc., to predict the age of the crab.
4. **Model Evaluation**: Evaluate the model using appropriate metrics and error analysis.
5. **Model Tuning**: Tune hyperparameters and apply techniques like cross-validation to avoid overfitting.

## Usage
The project is structured as a Jupyter notebook, which provides a detailed walk-through of the code, methodology, and analysis. To use the notebook, clone the repository and run it on a Jupyter notebook environment. The required dependencies can be installed using pip:

```bash
pip install -r requirements.txt
```

## Contact
For any questions, comments, or feedback, feel free to reach out to me at josevillalbajimenez@gmail.com

## Acknowledgments
This project would not have been possible without the dataset provided for this competition. I would like to thank Kaggle for hosting this competition and providing an excellent platform for data science enthusiasts to learn and grow.


