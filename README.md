# Lenear-Regression-Bike-Sharing
**Problem Statement**
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 


In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 

**Steps Involved:**
1. Importing Libraries
2. Loading and Analysing the DATA
3. Data Cleaning & Manipulation
4. Handling Outliers
5. Handling Null Values
6. Exploratory Data Analysis (EDA): Univariate and Bivariate Analysis 
7. Splitting the Data into Training and Testing Sets
8. Building a Linear Model
   a) SciKit Learn for its compatibility with RFE (which is a utility from sklearn)
   b) BUILDING MODEL USING STATSMODEL
9. Making Predictions
10. Model Evaluation

**Libraries Used:**
1. NumPy as np
2. Pandas as pd
3. Matplotlib.pyplot as plt
4. Seaborn as sns
5. statsmodels.api as sm 
6. RFE from sklearn
7. Variance_inflation_factor (VIF)

**Inferences:**
1. **Best fitted line:** 
count(y)= 0.0529 x Sep-0.0528x Dec-0.0558x Jan-0.0651x Nov-0.29x Light Snow-0.08xMist and cloudy-0.1042x spring-0.1081x holiday+0.4005x temp

2. Demand decreases if it is Holiday , Spring, Light Snow ,Jan, Dec


![image](https://user-images.githubusercontent.com/90130378/161399743-efc85635-1dfa-444f-96f0-0b31b3138196.png)
![image](https://user-images.githubusercontent.com/90130378/161399750-a8180184-8f69-4db2-8fd7-38b17ffe2d71.png)
![image](https://user-images.githubusercontent.com/90130378/161399769-75c2cdb2-89ae-4e8e-981c-fe91921b819a.png)
![image](https://user-images.githubusercontent.com/90130378/161399786-465950f6-9d27-4dfc-b85a-c5722ac10af1.png)
![image](https://user-images.githubusercontent.com/90130378/161399804-f4f37ace-683b-41ab-8cd9-5b180c3789d9.png)
![image](https://user-images.githubusercontent.com/90130378/161399814-a15f093d-f348-4830-9f1b-bb62455da44a.png)






