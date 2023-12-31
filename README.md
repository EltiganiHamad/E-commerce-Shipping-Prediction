# Enhancing E-commerce Shipping Efficiency through Machine Learning Insights

## Overview

In our recent project, our team delved into the vast realm of e-commerce shipping data, aiming to optimize and enhance the efficiency of the shipping process through the application of various machine learning algorithms. This endeavor involved a meticulous exploration of the dataset, employing advanced techniques to select features, and evaluating the performance of diverse machine learning models.

## Dataset Description

E-Commerce Shipping Dataset downloaded from https://www.kaggle.com/datasets/prachi13/customer-analytics<br>

This dataset contains customer information of an international e-commerce company. By implementing machine learning techniques we were hoping to find the patterns and create a model that will predict if future products will be delivered to the customers on time.<br><br>

Features:<br>
    1. ID: ID Number of Customers.<br>
    2. Warehouse block: The Company have big Warehouse which is divided in to block such as A,B,C,D,F.<br>
    3. Mode of shipment:The Company Ships the products in multiple way such as Ship, Flight and Road.<br>
    4. Customer care calls: The number of calls made from enquiry for enquiry of the shipment.<br>
    5. Customer rating: The company has rated from every customer. 1 is the lowest (Worst), 5 is the highest (Best).<br>
    6. Cost of the product: Cost of the Product in US Dollars.<br>
    7. Prior purchases: The Number of Prior Purchase.<br>
    8. Product importance: The company has categorized the product in the various parameter such as low, medium, high.<br>
    9. Gender: Male and Female.<br>
    10.Discount offered: Discount offered on that specific product.<br>
    11.Weight in gms: It is the weight in grams.<br>
<br>
Target:<br>
    Reached on time: 1 Indicates that the product has NOT reached on time and 0 indicates it has reached on time.
    
    
## Feature Selection:



### Ensemble of Feature Selection Algorithms:

Utilizing a sophisticated ensemble of feature selection algorithms, we systematically identified the most influential variables impacting the shipping process. This ensemble included popular techniques such as Recursive Feature Elimination (RFE), Boruta, and SelectKBest. The collective insights derived from these algorithms guided us in constructing a streamlined set of features that significantly contributed to model performance.

### Hypothesis-Driven Feature Selection:

In parallel, we embraced a hypothesis-driven approach to feature selection. Drawing on our domain knowledge and industry expertise, we formulated hypotheses about key factors influencing shipping efficiency. Features were selected based on these hypotheses, enabling us to test and validate our assumptions through the lens of machine learning.

## Objective

The primary goal was to identify patterns, correlations, and insights within the shipping data that could be leveraged to improve delivery times, reduce costs, and enhance overall customer satisfaction. To achieve this, we employed a two-fold approach in selecting features for training our machine learning models. We described insights gained through the exploration and analysis done in this project in a comprehensive report that can be found in this reposistory.
