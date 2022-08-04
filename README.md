# HackerEarth-Machine-Learning-challenge

[Link to the competition](https://www.hackerearth.com/challenges/competitive/hackerearth-machine-learning-challenge-predict-the-lowest-price/problems/).

### Problem
A leading global leader of e-commerce has over 150 million paid subscription users. One of the many perks of the subscription is the privilege of buying products at lower prices. For an upcoming sale, the organization has decided to promote local artisans and their products, to help them through these tough times. However, slashed prices may impact local artists.


### Project Summary
Use machine learning to predict the lowest price with Python.

### Purpose
To not let discounts affect local artists, the company has decided to determine the lowest price at which a particular good can be sold. Your task is to build a predictive model using Machine Learning that helps them set up a lowest-pricing model for these products.

### Data
#### Data Description
| Column  | Description |
| ------------- | ------------- |
| Item_Id | Unique item ID  |
| Date  | Date  |
| State_of_Country | State no. of the country  |
| Market_Category | Category of the market to which the product belongs to  |
| Product_Category | Category of the product  |
| Grade  | Quality of the product |
| Demand  | Demand rate of the product in the market  |
| Low_Cap_Price [Target]  | Lowest price that can be offered  |
| High_Cap_Price  | Original maximum price in the current market  |

#### Data Files

The dataset folder consists of the following files:

* Train.csv: Contains training data [9798 x 9] that must be used to build the model
* Test.csv: Contains test data [5763 x 8] to be predicted on
* sample_submission.csv: Contains sample submission format with dummy values filled for test data


### Result
After cleaning raw data, I tested a number of independent variables and found the significant features. Then, I utilized them to train a model and predicted the lowest price. Finally, this outcome got me the 51th prize.
<img width="1440" alt="截圖 2022-08-04 下午9 15 18" src="https://user-images.githubusercontent.com/67684645/182856141-d2316182-4f0f-4486-b6d2-c830510b29e7.png">
