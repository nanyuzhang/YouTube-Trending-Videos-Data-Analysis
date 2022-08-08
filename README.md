# YouTube-Trending-Videos-Data-Analysis

## About Project 
* Conducted data cleansing to perform exploratory data analysis (EDA) and data visualization of 143K+ YouTube trending videos;investigated users behaviors and features related to trending videos
* Implemented feature engineering and built a multi-class classifier on YouTube video views range with Python; tuned parameters and compared model performance using KNN, Random Forest and XGBoost, achieving 73% accuracy

## Motivation
* The analysis and prediction may help YouTube advertsing department to make business strategies and decisions and get more ads profit on popular videos. 
* The analysis and prediction may help YouTubers know how to improve their videos to get more views(eg. post time, title,description, tags, etc).

## Data Source: 
https://www.kaggle.com/datasets/rsrishav/youtube-trending-video-dataset

## Technologies Used:
Python

## Detailed process
### EDA 
Examples:
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
