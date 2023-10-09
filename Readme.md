![alt-test](https://github.com/HitPant/Fire_intensity_regressor/blob/master/images/algeria.jpeg)

# Description

dataset: https://archive.ics.uci.edu/dataset/547/algerian+forest+fires+dataset

In this project we have used Algerian Forest Fires Dataset to find intensity of fire using regression techniques. Here we compute FWI based on features columns.
FWI: Fire Weather Index, it is a numeric rating system used to assess the potential intensity and behavior of wildfires based on current weather conditions

## Techniques used: <br>
    1. Linear Regression
    2. Ridge Regression
    3. Lasso Regression
    4. ElasticNet

## Steps Performed: <br>
## 1. Data Cleaning:
        - Finding Null values
        - convert data type for columns
        - merge data

![alt-text](https://github.com/HitPant/Fire_intensity_regressor/blob/master/images/cleaned_data.png)
    
## 2. EDA:
### Encoding categorical variables

        - Monthly fire analysis region-wise 
![alt-text](https://github.com/HitPant/Fire_intensity_regressor/blob/master/images/fire1.png)
![alt-text](https://github.com/HitPant/Fire_intensity_regressor/blob/master/images/fire2.png)

### Density plot of featues to understand the distribution <br>
![alt-text](https://github.com/HitPant/Fire_intensity_regressor/blob/master/images/data_dist.png)

### Analyse outliers <br>

### Feature Selection <br>
![alt-text](https://github.com/HitPant/Fire_intensity_regressor/blob/master/images/corr.png)

### Feature Scaling <br>
![alt-text](https://github.com/HitPant/Fire_intensity_regressor/blob/master/images/scaling.png)
    
## 3. Model Training:
### Regression
![alt-text](https://github.com/HitPant/Fire_intensity_regressor/blob/master/images/Slide1.JPG)

![alt-text](https://github.com/HitPant/Fire_intensity_regressor/blob/master/images/Screenshot%202023-10-08%20203244.png)

### Parameter Tuning using ElasticNet
![alt-text](https://github.com/HitPant/Fire_intensity_regressor/blob/master/images/Screenshot%202023-10-08%20210557.png)


        


