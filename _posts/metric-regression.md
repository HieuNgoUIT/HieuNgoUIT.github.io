# Metrics trong Machine Learning - Regression

Trong phần này ta sẽ tìm hiểu về các metrics sau:
1. MSE - Mean Square Error
2. RMSE - Root Mean Square Error
3. R2 
4. MAE - Mean Absolute Error

và best constant của chúng 

> best constant: if we have to predict the same value for every object, what value is optimal to predict according to the chosen metric 

có thể hiểu best constant là base model của chúng ta, nếu model của chúng ta predict có score dưới score của base model => model chúng ta tệ hơn một model không học gì cả. 

## Notation
![Notation](a.png)


## MSE - Mean Square Error 

![MSE](mse.png)

Best contant : mean value

## RMSE

![RMSE](rmse.png)

Sử dụng thay thế mse

## R2 
![R2](r2.png)

## MAE

![mae](mae.png)

best contant : median 

# Take away

+ Have outliers: MAE
+ sure outliers?: MAE 
+ unexpected value we should care? MSE 
