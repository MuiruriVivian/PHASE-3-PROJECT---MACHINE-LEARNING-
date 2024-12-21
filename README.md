# PHASE-3-PROJECT---MACHINE-LEARNING

## **BUSINESS UNDERSTANDING**

You have been called for an interview in ABC company, a logistics and supply chain provider that aims to improve delivery efficiency by ensuring products are delivered on time. They would like to optimize their operations by eradicating delays in shipment whih has been impacting customer satisfaction and the operational cost. They would like you to identify the key factors, that influence product delivery.




You are expected to Create a model to identify the key factors influencing product delivery delays and recommend strategies for improving delivery efficiency, reducing operational costs, and enhancing customer satisfaction.

### **Objective of the Analysis**
1. Identify the Key Factors impacting delivery timeliness.


2. Develop a predictive model to forecast whether shipments will reach their destinations on time.

3. Analyse the data to reduce delays and improve the overall customer experience.

4. Minimize financial losses associated with delayed shipments

### **Dataset Information**

The dataset used was **E-Commerce Shipping Data** that was extracted from kaggle (https://www.kaggle.com/datasets/prachi13/customer-analytics).

The dataset used for model building contained 10999 observations of 12 variables.

This dataset contains records of shipments from an international e-commerce company specializing in electronic products. The primary objective is to analyze and predict whether shipments are delivered on time, aiming to enhance customer satisfaction and optimize delivery performance.

Data Types:
Numerical: Customer_care_calls, Customer_rating, Cost_of_the_Product, Prior_purchases, Discount_offered, Weight_in_gms

Categorical: Warehouse_block, Mode_of_Shipment, Product_importance, Gender

Binary: Reached_on_Time_Y_N

Logistics regression model

The logistic regression model achieves an accuracy of 63.09%, with better performance for Class 1 (precision: 66%, recall: 77%) compared to Class 0 (precision: 56%, recall: 43%). The weighted F1-score is 0.62, reflecting moderate overall classification performance, though class imbalance may favor Class 1. Regression metrics indicate poor fit, with negative R² values (-0.5562 for training, -0.5295 for testing) and moderate MSE (0.3742 train, 0.3691 test), suggesting the model struggles to explain variability in the data. To improve, consider addressing class imbalance, enhancing feature engineering, tuning hyperparameters, and exploring alternative models like Random Forests or Gradient Boosting.




