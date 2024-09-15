# PRODIGY_DS_03

Customer Purchase Prediction Using Decision Tree Classifier
Welcome to the Customer Purchase Prediction repository! This project involves building a decision tree classifier to predict whether a customer will purchase a product or service based on their demographic and behavioral data. We use the Bank Marketing dataset from the UCI Machine Learning Repository for this analysis.

Project Overview
The goal of this project is to develop a decision tree classifier that can predict customer purchase behavior. We utilize the Bank Marketing dataset, which contains information about customer demographics and past interactions with a bank's marketing campaigns.

Dataset
The dataset used in this project is the Bank Marketing Dataset available at the UCI Machine Learning Repository. It includes the following attributes:

age: Age of the customer.
job: Type of job.
marital: Marital status.
education: Level of education.
default: Whether the customer has credit in default.
housing: Whether the customer has a housing loan.
loan: Whether the customer has a personal loan.
contact: Type of communication used to contact the customer.
month: Last contact month of the year.
day_of_week: Last contact day of the week.
duration: Duration of the last contact.
campaign: Number of contacts performed during this campaign.
pdays: Number of days since the client was last contacted from a previous campaign.
previous: Number of contacts performed before this campaign.
poutcome: Outcome of the previous marketing campaign.
y: Whether the customer subscribed to a term deposit (target variable).
Objectives
Data Preprocessing:

Clean and prepare the dataset for analysis.
Handle missing values and encode categorical variables.
Split the data into training and testing sets.
Model Building:

Train a decision tree classifier on the training data.
Tune hyperparameters to optimize model performance.
Evaluation:

Evaluate the model using accuracy, precision, recall, and F1-score.
Visualize the decision tree to understand its structure.
Prediction:

Use the trained model to predict customer purchase behavior on new data.
Repository Structure
bank_marketing.csv: The raw dataset used for analysis.
data_preprocessing.ipynb: Jupyter Notebook for data preprocessing and preparation.
decision_tree_classifier.ipynb: Jupyter Notebook for building and evaluating the decision tree classifier.
visualizations.py: Python script for visualizing the decision tree.
requirements.txt: List of Python packages required for this project.
README.md: This file.
Getting Started
Prerequisites
Make sure you have Python 3.x installed. You will also need Jupyter Notebook for running the notebooks.

Installation
Clone the Repository:

bash
Copy code
git clone https://github.com/yourusername/customer-purchase-prediction.git
Navigate to the Project Directory:

bash
Copy code
cd customer-purchase-prediction
Create a Virtual Environment (Optional but recommended):

bash
Copy code
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
Install Required Packages:

bash
Copy code
pip install -r requirements.txt
Running the Analysis
Start Jupyter Notebook:

bash
Copy code
jupyter notebook
Open data_preprocessing.ipynb and decision_tree_classifier.ipynb from the Jupyter interface to follow along with data preparation, model building, and evaluation.

Visualize the Decision Tree:

Run the visualizations.py script to generate and save visualizations of the decision tree.

bash
Copy code
python visualizations.py
Key Findings
Model Performance: The decision tree classifier achieves an accuracy of X% on the test set, with precision, recall, and F1-score metrics as follows: Precision: X%, Recall: X%, F1-score: X%.
Feature Importance: Key features influencing the model include duration, campaign, and previous.
Decision Tree Visualization: The decision tree structure helps understand how decisions are made based on customer attributes.
Contributing
Contributions are welcome! If you have suggestions for improvements, bug fixes, or additional features, please fork the repository and submit a pull request. You can also open an issue for discussions or feedback.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments
UCI Machine Learning Repository for providing the Bank Marketing dataset.
Scikit-learn, Pandas, NumPy, and Matplotlib for their essential data analysis and machine learning tools.
