
# NHS Salary Prediction Project

This project aims to predict minimum and maximum salaries based on identified key features. It includes data preprocessing, feature selection, and employs the Decision Tree Regressor for model training and evaluation.

## Overview

This project predicts salaries based on key features. It's designed to solve the problem of predicting the salaries of physicians working with NHS. The dataset used is https://www.kaggle.com/datasets/homelesssandwich/nhs-jobs.
This data was scraped from the NHS jobs website.
The dataset will be valuable to those who seek to understand the the job market of doctors for the NHS within the UK.
This data only includes jobs that were deemed as being related to doctors from March 2019 to October 2019. Fields relating to a json file derive from a json file embedded in the HTML code. These fields are typically easier to work with as they contain less user inputted data.
## Inspiration
What variables constitute to salary?
Can salary be predicted?
What important bits of information can be extracted from the job descriptions?
## Features

- Data preprocessing
- Feature selection
- Model training and evaluation using the Decision Tree Regressor

## Getting Started

### Prerequisites

Ensure you have the following dependencies installed:

- Python 3.x
- Pandas
- Scikit-learn
- Matplotlib

### Installation

Use the following command to install the required dependencies:

```bash
pip install -r requirements.txt
```

## Usage

To use the project, run the following command:

```bash
python main.py
```

## Models

The project utilizes the Decision Tree Regressor, a machine learning algorithm that builds a tree-like model. In simple terms, it learns decision rules from the data to predict target values.

## Results

The model performance metrics and results are discussed in the python files.

## Contributing

Feel free to contribute.
## License

This project is licensed under the MIT License. See the [LICENSE.md](LICENSE.md) file for details.
