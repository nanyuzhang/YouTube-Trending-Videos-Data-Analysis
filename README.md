# YouTube-Trending-Videos-Data-Analysis

## About Project 
Performed 

## Motivation

## Data Source: 
https://www.kaggle.com/datasets/rsrishav/youtube-trending-video-dataset

## Technologies Used:
Python

## Detailed process
### EDA 

<img width="453" alt="Screen Shot 2022-08-07 at 18 31 58" src="https://user-images.githubusercontent.com/48861299/183321967-90bed1c0-d9ca-4093-ae4c-42f98df7aab7.png">
<img width="912" alt="Screen Shot 2022-08-07 at 18 32 06" src="https://user-images.githubusercontent.com/48861299/183321976-24717d10-f8fc-4962-81ae-30784cd2ea2a.png">
<img width="777" alt="Screen Shot 2022-08-07 at 18 32 37" src="https://user-images.githubusercontent.com/48861299/183321985-dc703bcb-e9e0-44ac-a5e0-d2d1e65a7873.png">

### Feature Engineering
<img width="450" alt="Screen Shot 2022-08-07 at 18 53 27" src="https://user-images.githubusercontent.com/48861299/183323131-fa94fd7b-c255-4902-a8ef-5e046e7f0e80.png">

### Model
Multi-class classifier with time-based cross validation
| Model      | Accuracy |Precision |Recall | F1-score
| ----------- | ----------- |----------- |----------- |----------- |
| KNN      | 0.69       |0.68      |  0.69    |0.68    |
| Random Forest   | 0.73        |0.73        |0.73        |0.73        |
| XGBoost   | 0.73        |0.76        |0.73        |0.74        |
