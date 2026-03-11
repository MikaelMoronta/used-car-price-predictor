# Capstone Final Report: Used Car Price Predictor
**Student:** Mikael Moronta Francisco  
**Course:** Capstone - Spring 2026  
**Instructor:** Dr. Shusen Pu

---

## 1. Introduction (Problem Framing and Motivation)
This project is about understanding how to predict the prices of used cars using data science. Used car prices can be hard to guess because they change based on many different factors like the brand, how old the car is, and how many miles it has been driven. I want to build a machine learning model that takes these details and gives an accurate price.

### Problem Definition
[cite_start]The main question I am trying to answer is: "Can a data science model accurately predict a car's resale price based on its history and features?"[cite: 15, 17]. [cite_start]In this project, my "target" variable—the thing I want to find—is the price of the car[cite: 18]. [cite_start]The other details like mileage, registration year, and engine size are my "features" or inputs[cite: 32]. [cite_start]Success for this project means my model’s guesses are close to the real prices, which I will measure using metrics like Mean Absolute Error (MAE) and $R^{2}$[cite: 18, 41].

### Significance and Motivation
[cite_start]This problem is important because the used car market is a huge part of the economy[cite: 19]. [cite_start]Buyers want to know they are getting a fair deal, and sellers want to set a price that is competitive[cite: 19, 63]. [cite_start]Dealerships and insurance companies also need to know the true value of a vehicle to make good business decisions[cite: 19].

### Context and Background
[cite_start]This project builds on the idea of **Regression**, which is a standard method in statistics and data science for predicting numerical values[cite: 21, 22]. [cite_start]I will specifically use **Multiple Linear Regression**, which looks at several features at once to find patterns in the data[cite: 35, 36]. [cite_start]This method is a great way to see how different variables (like age vs. mileage) impact a single outcome like price[cite: 38].

### Objectives and Goals
[cite_start]My main goals for this project are[cite: 23]:
* [cite_start]To find out which features (like mileage or engine size) have the biggest impact on a car's price[cite: 24].
* [cite_start]To build a regression model that can predict the price of a car it has never seen before[cite: 24].
* [cite_start]To evaluate the model and see how accurate it really is compared to a simple baseline[cite: 40, 56].

### Summary of Approach
[cite_start]I am using a dataset from Kaggle that has over 1,500 car records[cite: 26, 32]. My workflow will follow these steps:
1. [cite_start]**Data Cleaning:** Handle missing information and make sure the numbers are ready for the model[cite: 34].
2. [cite_start]**Train-Test Split:** Divide the data into a training set for the model to learn from and a testing set to check its work[cite: 34].
3. [cite_start]**Modeling:** Train the regression model using Python and libraries like Scikit-Learn[cite: 40, 45].
4. [cite_start]**Evaluation:** Look at the results and charts to see how well the model performed[cite: 26, 53].
