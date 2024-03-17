 # Salary Prediction Using Linear Regression

This GitHub repository contains code for predicting an employee's salary based on their experience, test score, and job role. The model uses the Linear Regression algorithm to make predictions.

## Getting Started

To activate the code in your local environment or Google Colab/Notebook, please follow these steps:

### Prerequisites

Before running the code, ensure you have installed the following libraries:

* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn

You can install them using pip:
```bash
pip install -r requirements.txt
```
or individually:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Steps to Run the Code

1. **Download CSV File**: Download the `Salary_Dataset.csv` file from the provided link (<https://drive.google.com/file/d/1WkCZ6FzBKlJjxHV7MnQ04XhvS8qfPgTG/view?usp=sharing>) and save it in your working directory.

2. **Import Dataset**: Use the following command to import the dataset into your notebook or IDE:
   ```python
   data = pd.read_csv('content/Salary_Dataset.csv')
   ```

3. **Run the Code**: Simply copy and paste the provided Python script `salary_prediction.py` into your Jupyter Notebook or other preferred IDE and run it step by step. Alternatively, if you are using Google Colab, mount your Google Drive and upload the downloaded CSV file before executing the provided script.

The code includes exploratory data analysis, feature engineering, training a linear regression model, evaluating its performance, and making predictions based on new input features.

**Note**: Please replace 'your_model.save("path")' with the desired path where you want to store your trained model locally. This will allow you to load the saved model directly without re-training each time.
