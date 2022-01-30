# Credit Risk Analysis

## Overview
The overarching goal of this project is to use machine learning to predict credit risk. In the data set, there is a higher proportion of "good" loans versus risky loans; an unbalanced set of classification calls for the application of various models and resampling techniques to identify a model with the highest degree of precision.  
 
### Resouces
- Software: Visual Studio Code, Jupyter Lab
- Languages: Python
- Libraries: numpy, pandas, matplotlib, scikit-learn
- Data: LoanStats_2019Q1.csv

## Results

## Oversampling Techniques

#### Naive Random Oversampling
<img width="377" alt="Screen Shot 2022-01-30 at 3 05 49 PM" src="https://user-images.githubusercontent.com/91163155/151717799-dc3a412a-41eb-4881-bf43-94b3aba76213.png">
<img width="628" alt="Screen Shot 2022-01-30 at 3 05 57 PM" src="https://user-images.githubusercontent.com/91163155/151717808-d042d33f-9ade-4d62-b97a-0893d7953000.png">

#### SMOTE Oversamping
<img width="377" alt="Screen Shot 2022-01-30 at 3 06 12 PM" src="https://user-images.githubusercontent.com/91163155/151717821-62c71530-335d-4e89-8c21-ebc62dda091e.png">
<img width="625" alt="Screen Shot 2022-01-30 at 3 06 24 PM" src="https://user-images.githubusercontent.com/91163155/151717828-d7cd003f-d09d-4415-a8b8-601d0193cd27.png">


## Undersampling Techniques
#### Cluster Centroids
<img width="383" alt="Screen Shot 2022-01-30 at 3 06 40 PM" src="https://user-images.githubusercontent.com/91163155/151717835-fce2f1b4-a7eb-416b-95a8-d9de0b358367.png">

<img width="627" alt="Screen Shot 2022-01-30 at 3 06 51 PM" src="https://user-images.githubusercontent.com/91163155/151717846-73054014-7a0c-4374-a36e-51d383628f44.png">


## Combination (Over & Under) Sampling
#### SMOTEENN 
<img width="377" alt="Screen Shot 2022-01-30 at 3 07 10 PM" src="https://user-images.githubusercontent.com/91163155/151717856-0fcd5c1f-fa99-4dbb-b1a1-449fe305b701.png">
<img width="622" alt="Screen Shot 2022-01-30 at 3 07 21 PM" src="https://user-images.githubusercontent.com/91163155/151717867-03e5bd70-4ad8-4b62-bb32-20c03473fd64.png">



## Ensemble Learners
#### Balanced Random Forest
<img width="382" alt="Screen Shot 2022-01-30 at 3 07 55 PM" src="https://user-images.githubusercontent.com/91163155/151717893-5367c72c-6761-4df9-a4dc-4b965924b968.png">
<img width="418" alt="Screen Shot 2022-01-30 at 3 08 07 PM" src="https://user-images.githubusercontent.com/91163155/151717897-23aa430b-b370-4eb0-9931-9fe68b6341ab.png">

<img width="636" alt="Screen Shot 2022-01-30 at 3 08 40 PM" src="https://user-images.githubusercontent.com/91163155/151717916-ebf8fdb3-d9c4-407f-9c58-ee2b57f93899.png">


#### Easy Ensemble AdaBoost 
<img width="384" alt="Screen Shot 2022-01-30 at 3 08 55 PM" src="https://user-images.githubusercontent.com/91163155/151717928-e22b9652-a7bc-4798-b93f-42153a9b5beb.png">
<img width="627" alt="Screen Shot 2022-01-30 at 3 09 04 PM" src="https://user-images.githubusercontent.com/91163155/151717937-233ab47a-f6eb-4327-a54a-48154d9f5d2e.png">


## Summary
