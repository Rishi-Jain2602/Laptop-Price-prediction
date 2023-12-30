# Laptop-Price-Predictor
A website for predicting the price of the laptop using machine learning.
***


## Requirements
- Python 3.x
- Jupyter Notebook
- Python Libraries- Numpy,Pandas,Seaborn,sklearn and pickle
***

## Installation
1. Clone the repository
```bash
git clone https://github.com/Rishi-Jain2602/Laptop-Price-prediction.git
```

2. Install the Project dependencies
```bash
pip install -r requirements.txt
```

3. Download Model Files
Download the following pre-trained model files:
- df.pkl: Pickle file containing preprocessed data
- pipe.pkl: Pickle file containing trained model pipeline 
- page.py: Python script for streamlit web application


4. Download Dataset
- laptop_data.csv

5. Start the web server
Now after installing all the required files and modules, you can use the model by running the following command in the terminal:
```bash
streamlit run page.py
```
This will execute the page.py script, which uses the pre-trained model (df.pkl and pipe.pkl) on the provided dataset (laptop_data.csv).
***
## Features
- By Providing the details of laptops like:
  1. Company
  2. Its Type of laptop(means whether it is Ultrabook , Notebook ,Netbook etc.)
  3. Ram size
  4. Weight of Laptop
  5. Whether it is Touchscreen or not
  6. IPS present or not
  7. Screen size
  8. Screen Resolution
  9. Cpu like Intel core i7/i5/i3 , AMD Processor etc.
  10. GPU like Intel , Nvidia or AMD
  11. Whether it is Os is mac , windows ,linus etc
- We can predict the price of the laptop

***
## Model Training
### Data Source 
Laptop Prices data: The primary dataset used for this analysis is the "Laptop_data.csv" file, containing detailed information about Laptops which includes its Brand , weight,  screen resolution , screen size , ram etc.

### Tools
- Vscode

### Data Cleaning/Preparation
In the initial data preparation phase, we performed the following tasks:
1. Data loading and inspection.
2. Handling missing values.
3. Data cleaning and formatting.

### Exploratory Data Analysis
EDA involved exploring the sales data to answer key questions, such as:
1. Which laptops brand are more in demand?
2. Is touchscreen Laptops are in trend or not?
3. What screen size and Screen Resolution did people prefer? 

### Type of Algorithm used for Model
 ** Random Forest Regression **
- It is basically belongs to Family of Decision tree
- A decision tree is a flowchart-like structure where each internal node represents a decision based on the value of a particular feature, each branch represents the outcome of that decision, and each leaf node represents the final prediction or decision.
#### Advantage
- It can handle Overfitting and non-linearity.
- Can be applied to various type of data including Numerical and categorical data
#### Limitation
- Higher the number of trees lead to better performance but upto a certain extent.
***
### Results
Its accuracy was coming out to be 88.79% and mean absolute error is 15.8%

![results](https://github.com/Rishi-Jain2602/Laptop-Price-prediction/assets/118871883/cc99b85e-af70-4590-a8ca-86b788e5b41e)
***
### Note

1. Make sure you have Python 3.x installed
2. It is recommended to use a virtual environment to avoid conflict with other projects.
3. If you encounter any issue during installation or usage please contact rishijainai262003@gmail.com or rj1016743@gmail.com
