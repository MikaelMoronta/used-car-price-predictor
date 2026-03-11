# Capstone Final Report: Used Car Price Predictor

**Student:** Mikael Moronta Francisco  
**Course:** Capstone - Spring 2026  
**Instructor:** Dr. Shusen Pu

---

## 1. Introduction (Problem Framing and Motivation)
This project is about understanding how to predict the prices of used cars using data science. Used car prices can be hard to guess because they change based on many different factors like the brand, how old the car is, and how many miles it has been driven. I want to build a machine learning model that takes these details and gives an accurate price.

### Problem Definition
The main question I am trying to answer is: "Can a data science model accurately predict a car's resale price based on its history and features?" In this project, my "target" variable—the thing I want to find—is the price of the car. The other details like mileage, registration year, and engine size are my "features" or inputs. Success for this project means my model’s guesses are close to the real prices, which I will measure using metrics like Mean Absolute Error (MAE) and $R^{2}$.

### Significance and Motivation
This problem is important because the used car market is a huge part of the economy. Buyers want to know they are getting a fair deal, and sellers want to set a price that is competitive. Dealerships and insurance companies also need to know the true value of a vehicle to make good business decisions.

### Context and Background
This project builds on the idea of Regression, which is a standard method in statistics and data science for predicting numerical values. I will specifically use Multiple Linear Regression, which looks at several features at once to find patterns in the data. This method is a great way to see how different variables (like age vs. mileage) impact a single outcome like price.

### Objectives and Goals
My main goals for this project are:
* To find out which features (like mileage or engine size) have the biggest impact on a car's price.
* To build a regression model that can predict the price of a car it has never seen before.
* To evaluate the model and see how accurate it really is compared to a simple baseline.

### Summary of Approach
I am using a dataset from Kaggle that has over 1,500 car records. My workflow will follow these steps:
1. **Data Cleaning:** Handle missing information and make sure the numbers are ready for the model.
2. **Train-Test Split:** Divide the data into a training set for the model to learn from and a testing set to check its work.
3. **Modeling:** Train the regression model using Python and libraries like Scikit-Learn.
4. **Evaluation:** Look at the results and charts to see how well the model performed.
