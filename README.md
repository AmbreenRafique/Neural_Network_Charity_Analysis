# Neural_Network_Charity_Analysis

## Overview: of the loan prediction risk analysis:

By using the features in the provided dataset to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.
The CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as the following:

- EIN and NAME—Identification columns
- APPLICATION_TYPE—Alphabet Soup application type
- AFFILIATION—Affiliated sector of industry
- CLASSIFICATION—Government organization classification
- USE_CASE—Use case for funding
- ORGANIZATION—Organization type
- STATUS—Active status
- INCOME_AMT—Income classification
- SPECIAL_CONSIDERATIONS—Special consideration for application
- ASK_AMT—Funding amount requested
- IS_SUCCESSFUL—Was the money used effectively

"IS_SUCCESSFUL" is our target column to predict whether applicants will be successful.
We are considering the following columns as our features
 - 'APPLICATION_TYPE',
 - 'AFFILIATION',
 - 'CLASSIFICATION',
 - 'USE_CASE',
 - 'ORGANIZATION',
 - 'INCOME_AMT',
 - 'SPECIAL_CONSIDERATIONS'
 
The reason of dropping "EIN" and "Name" columns is, as it doesn't have anything to do with the prediction. 


## Results:


chaning in neurons, and activation functions to compare the performance is as follows:

## 1st
![sc1](https://user-images.githubusercontent.com/108497494/200899901-0da25eaf-e434-44f7-9a3a-8530aef31f57.jpg)
![s1 performance](https://user-images.githubusercontent.com/108497494/200899915-a719fa7a-8412-4efa-a598-c7100913607f.jpg)

## 2nd
![sc 2](https://user-images.githubusercontent.com/108497494/200899941-7d363880-424b-474c-9967-339a19378d9d.jpg)
![sc 2 performance](https://user-images.githubusercontent.com/108497494/200899963-31befa88-9dbc-402b-ae1f-05940747a97e.jpg)

## 3rd
![sc 3](https://user-images.githubusercontent.com/108497494/200899990-3f617abf-520c-48bb-aeaa-53e43f1e4fc4.jpg)
![SC performance](https://user-images.githubusercontent.com/108497494/200900233-0a83f30c-7f60-4e4e-a641-020b8e3af18e.jpg)

Tryed different Models by changing 
1: The number of Nuerons in each model and/or
2: Activation functions and/or
3: dropping extra rows in the DataFrame and/or
4: Increasing/dicreasing the number of Epochs in the Models 
 It doesn't make any noticeable differance in accuracy or the performance of any of the models.
 I was not able to achieve the target model performance.

There is a bulleted list that answers all six questions (15 pt)
Summary:

None of above shows good accuracy level or performance.
We should try other machine learning models other than Nurel networks for better performance.
