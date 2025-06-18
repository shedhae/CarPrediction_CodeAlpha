# CarPrediction_CodeAlpha
Overview
This project aims to predict car prices using a dataset containing various features of cars such as year, present price, kilometers driven, fuel type, selling type, transmission, and owner information. The project involves data exploration, visualization, and building a linear regression model to predict selling prices based on these features.
Dataset
The dataset used in this project is named car data.csv and contains the following columns:

Car_Name: Name of the car

Year: Manufacturing year of the car


Selling_Price: Selling price of the car (target variable)

Present_Price: Current market price of the car

Driven_kms: Kilometers driven by the car

Fuel_Type: Type of fuel the car uses (Petrol, Diesel, etc.)

Selling_type: Type of sale (Dealer, Individual)

Transmission: Transmission type (Manual, Automatic)

Owner: Number of previous owners

Project Structure
The project is organized in a Jupyter Notebook (CarPricePrediction.ipynb) with the following steps:

Importing Libraries: Essential libraries like pandas, numpy, matplotlib, seaborn, and scikit-learn are imported.

Loading Data: The dataset is loaded from the CSV file.

Data Exploration:

Displaying the first few rows of the dataset.

Checking dataset information and statistical summary.

Data Visualization:

Histogram of the selling price distribution.

Line plots showing relationships between present price and selling price, and kilometers driven and selling price.

Model Building:

Splitting the data into training and testing sets.

Training a linear regression model.

Evaluating the model using metrics like mean absolute error, mean squared error, and R-squared.

Usage
Prerequisites:

Python 3.x

Jupyter Notebook

Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

Steps to Run:

Clone the repository.

Install the required libraries using pip install -r requirements.txt (if a requirements file is provided).

Open the Jupyter Notebook and run each cell sequentially.

Results
The project includes visualizations to understand the data distribution and relationships between features. The linear regression model is evaluated to predict car prices based on the given features.





