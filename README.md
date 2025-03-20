# CharityML: Finding Potential Donors

This project implements a machine learning pipeline to identify potential donors for CharityML, a fictional charity organization, based on US Census data. The goal is to predict whether an individual makes more than $50,000 annually, which would make them more likely to donate.

## Project Overview

The main components of this project are:

- **Data exploration** of census data to understand income distribution
- **Data preprocessing** including feature scaling and encoding of categorical variables
- **Model selection** comparing Random Forest, Decision Tree, and Logistic Regression algorithms
- **Hyperparameter tuning** to optimize model performance
- **Feature importance analysis** using Random Forest to identify key predictive factors

## Files in this Repository

- `CharityML.ipynb`: The main Jupyter notebook containing the complete analysis and model building process
- `CharityML.html`: HTML version of the analysis notebook
- `census.csv`: The dataset from the 1994 U.S. Census
- `visuals.py`: Supporting Python script for data visualization

## Dataset Description

The dataset contains information about individuals collected from the 1994 U.S. Census. Features include:

- **Demographic information**: age, workclass, education, marital status, occupation, relationship, race, sex, native country
- **Financial information**: capital gain, capital loss, hours per week

The target variable is whether an individual makes more than $50,000 annually.

## Requirements

This project uses:
- Python 3.12
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

## Usage

The analysis can be explored by opening the Jupyter notebook:

```
jupyter notebook CharityML.ipynb
```

Alternatively, you can view the HTML version in any web browser by opening `CharityML.html`.

## Results

The optimized machine learning model can effectively identify individuals likely to earn more than $50,000 annually, providing CharityML with a tool to focus their outreach efforts on individuals with the highest donation likelihood.

## Acknowledgments

The dataset comes from the UCI Machine Learning Repository, originally published in Ron Kohavi and Barry Becker's article "Scaling Up the Accuracy of Naive-Bayes Classifiers: A Decision-Tree Hybrid." 

## Credits

This project was developed by Xinwei Li. GitHub: [@li-xinwei](https://github.com/li-xinwei)

Project website: [https://li-xinwei.github.io/CharityML/](https://li-xinwei.github.io/CharityML/) 