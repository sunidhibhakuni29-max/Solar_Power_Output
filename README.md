
# Solar Power Output Prediction

### Predicting Solar Power Output Using Machine Learning

## 1. Project Overview

Solar energy is one of the most important sources of renewable energy. Predicting solar power output helps in understanding solar energy generation and improving energy planning.

This project focuses on predicting solar power output using Machine Learning techniques, particularly Linear Regression.

The project uses Python and Jupyter Notebook for data analysis, model development, prediction, and evaluation.

### Objectives

- Analyse solar power plant data.
- Understand the factors affecting solar power generation.
- Perform data preprocessing and exploration.
- Apply Linear Regression for solar power prediction.
- Compare model performance.
- Generate and analyse prediction results.

## 2. Team Members and Roles

| S.No. | Name | GitHub Username | Role |
|---|---|---|---|
| 1 | Satinderpal Singh | satinderpal747 | Documentation Lead |
| 2 | Sunidhi Bhakuni| sunidhibhakuni29 | Execution Lead |
| 3 | Jeswanth Saw | Jeswanth-sai | PPT Lead |
| 4 | Sarina | Sarina-17 | Video Lead |

All team members contribute to the project and maintain their own GitHub commit history.

## 3. Project Structure

```text
Solar_Power_Output/
│
├── Code/
│   ├── Solar Power Plant Data.csv
│   ├── code.ipynb
│   ├── model_comparison.csv
│   ├── solar_linear_regression.pkl
│   └── solar_prediction_results.csv
│
├── presentation/
│
├── README.md
│
└── requirements.txt
```

### File Description

| File | Description |
|---|---|
| Solar Power Plant Data.csv | Dataset used for the project |
| code.ipynb | Jupyter Notebook containing project code |
| model_comparison.csv | Stores model comparison results |
| solar_linear_regression.pkl | Saved Linear Regression model |
| solar_prediction_results.csv | Stores prediction results |
| requirements.txt | Required Python libraries |
| presentation/ | Project presentation files |

## 4. Dataset Description

The project uses the Solar Power Plant Data dataset.

**Dataset File:** Solar Power Plant Data.csv

The dataset is used for analysing solar power generation and developing a machine learning model to predict solar power output.

Dataset details:

- Dataset Name: Solar Power Plant Data
- File Format: CSV
- Data Source: Kaggle
- Number of Rows: 8760
- Number of Columns: 8
- Target Variable: Solar Production

## 5. Technologies and Requirements

The following technologies are used in this project:

| Technology | Purpose |
|---|---|
| Python | Programming language |
| Jupyter Notebook | Code development and execution |
| Pandas | Data manipulation |
| NumPy | Numerical calculations |
| Matplotlib | Data visualisation |
| Seaborn | Statistical visualisation |
| Scikit-learn | Machine Learning |
| Pickle | Saving the trained model |

### Python Version

Python 3.14.6

### Dependencies

All required Python libraries are listed in requirements.txt.

## 6. Installation and Execution

Follow these steps to run the project on your computer.

### Step 1: Clone the Repository

```bash
gh repo clone sunidhibhakuni29-max/Solar_Power_Output
```

### Step 2: Open the Project Directory

```bash
cd Solar_Power_Output
```

### Step 3: Install Required Libraries

```bash
pip install -r requirements.txt
```

### Step 4: Navigate to the Code Folder

```bash
cd Code
```

### Step 5: Launch Jupyter Notebook

```bash
jupyter notebook
```

### Step 6: Execute the Project

1. Open the relevant project notebook.
2. Make sure the dataset is available in the Code folder.
3. Run the notebook cells in sequential order.
4. Observe the data analysis and model training.
5. View the prediction results and model evaluation.

Note: Confirm which notebook is the main execution notebook with the Execution Lead.

## 7. Methodology

The project applies Linear Regression for predicting solar power output.

The general workflow includes:

1. Data Collection
2. Data Loading
3. Data Exploration
4. Data Preprocessing
5. Feature Selection
6. Model Training
7. Prediction
8. Model Evaluation
9. Model Comparison

### Linear Regression

Linear Regression is a supervised Machine Learning algorithm used to predict continuous numerical values based on input features.

The general equation is:

Y = b0 + b1X1 + b2X2 + ... + bnXn

Where:

- Y = Predicted output
- X = Input features
- b0 = Intercept
- b1, b2, ... = Model coefficients

## 8. Model Evaluation and Results

The project includes the following result files:

- model_comparison.csv
- solar_prediction_results.csv
- solar_linear_regression.pkl

These files are used to store model comparison information, prediction results, and the saved Linear Regression model.

Actual evaluation metrics and graphs should be added after reviewing and executing the project notebook.

## 9. Expected Output

The project aims to generate:

- Analysis of solar power plant data.
- Machine Learning model predictions.
- Model comparison results.
- Solar power output predictions.
- Visual representation of prediction results.

Actual output screenshots and graphs will be included after successful execution.

## 10. Presentation

- Project PPT: To be added
- Project Video: To be added.

The presentation explains the problem statement, dataset, methodology, results, and team contributions.

## 11. AI-Use Disclosure

ChatGPT was used to assist with the preparation and organisation of project documentation.

All documentation is reviewed and edited by the team.

Any other AI tools used for coding, debugging, or analysis should also be disclosed with their respective purposes and verification methods.

The team is responsible for understanding and verifying the project code, model, and results.

## 12. Conclusion

This project demonstrates the application of Machine Learning techniques for predicting solar power output using solar power plant data.

By using Linear Regression and Python-based data analysis, the project provides practical experience in data preprocessing, model training, prediction, model evaluation, and collaborative software development using GitHub.

---

**Course:** AI101 - Data Science and AI Essentials with Python

**Institution:** School of AI and Data Engineering, IIT Ropar

**Project Title:** Solar Power Output Prediction

