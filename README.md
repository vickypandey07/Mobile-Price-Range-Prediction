# **Mobile-Price-Range-Prediction**
Mobile phones have become the greatest necessity for almost all individuals nowadays. People want more features and best specifications in a phone and that too at cheaper prices. The demand for phones is so high that there is a huge competition prevailing between mobile manufacturers. To stay ahead in the race, these companies try to bring in new features and innovations so that people are lured towards buying their brand smartphones.
Price of a mobile phone is influenced by various factors. Brand name, newness of the model, specifications such as internal memory, camera, ram, sizes, connectivity etc., are some of the important factors in determining the price.
As a business point of view, it becomes an utmost priority to analyse these factors from time to time and come up with best set of specifications and price ranges so that people buy their mobile phones.In the competitive mobile phone market companies want to understand sales data of mobile phones and factors which drive the prices. The objective is to find out some relation between features of a mobile phone and its selling price.

**Dataset info**

* Number of records: 2000

* Number of attributes: 21

**Features information:**

The dataset contains features like:
* **Battery_power** - Total energy a battery can store in one time measured in mAh
* **Blue** - Has bluetooth or not
* **Clock_speed** - speed at which microprocessor executes instructions
* **Dual_sim** - Has dual sim support or not
* **Fc** - Front Camera mega pixels
* **Four_g** - Has 4G or not
* **Int_memory** - Internal Memory in Gigabytes
* **M_dep** - Mobile Depth in cm
* **Mobile_wt** - Weight of mobile phone
* **N_cores** - Number of cores of processor
* **Pc** - Primary Camera mega pixels
* **Px_height** - Pixel Resolution Height
* **Px_width** - Pixel Resolution Width
* **Ram** - Random Access Memory in Mega Bytes
* **Sc_h** - Screen Height of mobile in cm
* **Sc_w** - Screen Width of mobile in cm
* **Talk_time** - longest time that a single battery charge will last when you are on call
* **Three_g** - Has 3G or not
* **Touch_screen** - Has touch screen or not
* **Wifi** - Has wifi or not
 
 **Target Variable :** 
 * **'Price_range'**: This is the target variable with value of 0(low cost), 1(medium cost), 2(high cost) and 3(very high cost).
---
**The main objective is to build a predictive model, which could help in predicting the price range of mobile phones.**
---

**Prerequisites**
* Good understanding of ML algorithms

**Technologies used**
* IDE- Google colab 

# **Project Work flow**
---

1. Importing Libraries

2. Loading the dataset

3. Exploratory data analysis

4. Data Wrangling

5. Splitting the data and standardization

6. Fitting models

7. Model Explainability

8. Conclusion
--- 

# Conclusion

Thats it! We have come to an end of our long exercise. Throughout the analysis we went through various steps to determine our predictions for the mobile price range. We started with simple EDA where we analysed our dependent variable as well as other independent variables. We found out the correlation, count, relationships with the dependent variable. We looked for missing values and outliers and did some feature modifications.

Finally we implemented 2 machine learning algorithms namely; RandomForest and XGBoost. We tried hyperparameter tuning to reduce overfitting and increase model performance. The best performance was given by our XGBoost model.

We also implemented shap techniques to identify the important features impacting our model predictions. We saw ram, battery power, px_height and px_weight were the major contributors. Higher the values of these led to higher predicted values.

The accuracy of our best model was 0.89 and 0.85 for training and test set respectively. Although, the difference is still 4, considering the simplicity and less no. of observations, this can be considered a good model. Performance can be improved even further by applying fine tunings and gathering more amount of observations so that the models can identify more patterns and become less prone to overfitting. With evolution of new technology, these numbers can change in future hence there will always be a need to check on the model from time to time. I hope this exercise will help you to take a step forward!


**Sources**
This project is part of AlmaBetter Curriculum.
