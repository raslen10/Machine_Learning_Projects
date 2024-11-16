# Loan Prediction Project

## Project Overview
This project aims to predict loan eligibility using various machine learning models. The dataset includes information about loan applicants, such as their gender, marital status, income, loan amount, credit history, and more. By processing and analyzing this data, we can build predictive models to determine the likelihood of loan approval.

## Dataset
The dataset used in this project is stored in an Excel file named `loan.xlsx`.

## Features
- `Gender`: Male or Female
- `Married`: Applicant's marital status
- `Dependents`: Number of dependents
- `Education`: Applicant's education level
- `Self_Employed`: Whether the applicant is self-employed
- `ApplicantIncome`: Applicant's income
- `CoapplicantIncome`: Co-applicant's income
- `LoanAmount`: Amount of the loan
- `Loan_Amount_Term`: Term of the loan in months
- `Credit_History`: Credit history meets guidelines
- `Property_Area`: Urban, Semiurban, Rural
- `Loan_Status`: Loan approved (Y/N)

## Models Used
- Random Forest Classifier
- Support Vector Machine (SVM)
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Gradient Boosting Classifier

## Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/loan-prediction.git
    cd loan-prediction
    ```

2. Create a virtual environment and activate it:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

## Usage
1. Place the `loan.xlsx` dataset in the project directory.

2. Run the main script to preprocess the data, train the models, and evaluate them:
    ```sh
    python main.py
    ```

## Code Description
### Data Preprocessing
- Handling missing values by filling with the mode or mean of the respective columns.
- Creating new features such as `TotalIncome` and `loanamount_log`.
- Encoding categorical variables using `LabelEncoder`.

### Model Training and Evaluation
- Splitting the dataset into training and test sets.
- Training multiple models and evaluating them based on accuracy, confusion matrix, and classification report.

### Visualization
- Using Seaborn to create count plots for categorical variables.

## Results
Each model's accuracy, confusion matrix, and classification report are printed to the console for comparison.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.


