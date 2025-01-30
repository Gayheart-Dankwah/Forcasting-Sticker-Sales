# **Forcasting-Sticker-Sales**
This project aims to forcast stickers sales in different countries.

![Project Screenshot](cute-stickers-heart-flower-star-more_123891-161446.jpg)

## **Table of Contents**
- [Introduction](#introduction)
- [Features](#features)
- [Dataset](#dataset)
- [Exploratory Data Analysis](#EDA)
- [Installation](#Installation)
- [Usage](#usage)
- [Model Evaluation](#model-evaluation)
- [Results](#results)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [Contact](#contact)

---

## **Introduction**
This project is a Machine learning-Time Series project to predict sticker sales in different countries such as **norway, Kenya,etc**. The model is built with **ARIMA**



## **Features**
- **Deployment-ready API** using Flask

---

## **Dataset**
- **Source:** [Kaggle](https://kaggle.com)
- **Shape:** 230130 rows, 5 columns
- **Preprocessing:**  
  - Sine Encoding method was used to capture seasonality patterns
- variables:
- * date- date of purchase
  *  Country
  *  Store
  *  Product
  *  num_sold - number of stickers sold
# Exploratory Data Analysis
The EDA section includes the following analysis:

### Univariate Analysis
Explores the distribution of individual features using visualizations.

### Bivariate Analysis
Investigates the relationship between the target variable and other features.


## Predictive Modeling
The predictive modeling section includes the implementation of two models:
### Autoregressive Integrated Moving Average (ARIMA)
A traditional model for time series forcasting.

### Random Forest Regressor
An ensemble learning method for Regression tasks.


## Installation
1. Clone the repository: `git clone https://github.com/your-username/your-repo.git`
2. Install the required dependencies: `pip install -r requirements.txt`

## Usage
1. Ensure the dataset file `train.csv` is in the same directory as the Python script.
2. Run the Python script
## Model Evaluation
The performance of the models is evaluated using Mean Absolute Percentage error(MAPE).
## Results
* Mean absolute percentage error score: 7.88%
* The model performance was impressive and great since the average deviation between the Actual and the predicted was 7.88%

## Deployment
* Flask API is greatly recommended
## Contributing
I welcome  all contributions from professionals and individuals. use
* pull request on GitHub

## Contact
Email: gayheartdankwah133@gmail.com
LinkedIn: [linkedIn](https://www.linkedin.com/in/gayheart-dankwah-9525451a8/)

