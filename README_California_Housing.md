
# Predicitng Median House prices for different California Districts using Linear Regression (SkLearn)

A brief description of what this project is that it is a predicitve analytics Linear regression model, developed for predicting the Median Housing prices of different states of California. We have built the predictive model on the back of 8 dependant parameters and over 20,000 different instances and records.

## Implementation Details

- Dataset: California Housing Dataset (view below for more details)
- Model: [Linear Regressor](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html)
- Input: 8 features - Median Houshold income, House Area, ...
- Output: House Price

## Dataset Details

This dataset was obtained from the StatLib repository ([Link](https://www.dcc.fc.up.pt/~ltorgo/Regression/cal_housing.html))

This dataset was derived from the 1990 U.S. census, using one row per census block group. A block group is the smallest geographical unit for which the U.S. Census Bureau publishes sample data (a block group typically has a population of 600 to 3,000 people).

A household is a group of people residing within a home. Since the average number of rooms and bedrooms in this dataset are provided per household, these columns may take surprisingly large values for block groups with few households and many empty houses, such as vacation resorts.

It can be downloaded/loaded using the sklearn.datasets.fetch_california_housing function.

- [California Housing Dataset in Sklearn Documentation](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.fetch_california_housing.html)
- 20640 samples
- 8 Input Features: 
    - MedInc median income in block group
    - HouseAge median house age in block group
    - AveRooms average number of rooms per household
    - AveBedrms average number of bedrooms per household
    - Population block group population
    - AveOccup average number of household members
    - Latitude block group latitude
    - Longitude block group longitude
- Target: Median house value for California districts, expressed in hundreds of thousands of dollars ($100,000)

## Evaluation and Results
![alt text](https://github.com/123ofai/Demo-Project-Repo/blob/main/results/test.png)

As you can see from the above image, the model has signifcant amount of error in <x, y, z regions>

| Metric        | Value         |
| ------------- | ------------- |
| R2 Score      |  0.582        |
| MSE           |  0.55         |

## Appendix

This dataset consists 2 possibilly co-related features in form of No of rooms and No. of bedrooms in the houses. Simply because of the fact that the rooms with more number of rooms are also expected to have more bedrooms and vice-versa.


## Acknowledgements

 - [Dataset Resopurse for Model Building](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.fetch_california_housing.html)
 - [Resource for learning Multicollinearity](https://www.datasklr.com/ols-least-squares-regression/multicollinearity)
 - [Linear Regression Resource](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html)


## Documentation

[Documentation](https://scikit-learn.org/stable/supervised_learning.html#supervised-learning)


## Screenshots

![App Screenshot](https://www.google.com/imgres?imgurl=http%3A%2F%2Fwww.stanford.edu%2Fclass%2Fstats202%2Ffigs%2FChapter3%2F3.1.png&tbnid=lrKLIRzo4njiAM&vet=12ahUKEwiW2_uz9d-CAxXY6DgGHRyhARMQMygEegQIARB2..i&imgrefurl=https%3A%2F%2Fweb.stanford.edu%2Fclass%2Fstats202%2Fnotes%2FLinear-regression%2FSimple-linear-regression.html&docid=vDNVMkA5hygvEM&w=2404&h=1550&q=linear%20regression&ved=2ahUKEwiW2_uz9d-CAxXY6DgGHRyhARMQMygEegQIARB2)


## API Reference

#### Get all items

```http
  GET /api/items
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Get item

```http
  GET /api/items/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |

#### add(num1, num2)

Takes two numbers and returns the sum.


## Badges

Add badges from somewhere like: [shields.io](https://shields.io/)

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)

