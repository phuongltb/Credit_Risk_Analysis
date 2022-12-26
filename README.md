# Credit_Risk_Analysis
Employ different techniques to train and evaluate models with unbalanced classes to predict credit risk.

## Overview of the project
This project consists of the following:
  - Use Resampling Models to Predict Credit Risk.
  - Use the SMOTEENN Algorithm to Predict Credit Risk.
  - Use Ensemble Classifiers to Predict Credit Risk.
  - A Written Report on the Credit Risk Analysis in README.md

## Results
  - Predict credit risks using Random Oversampling model. This model gives a balanced accuracy score of 62.93%, precision of high risk is 0.01, and recall score for high risk is 0.57
  
    ![image](https://user-images.githubusercontent.com/110554264/209492324-ce633ebc-2a3b-4f7e-aa31-094f15043792.png)

    ![image](https://user-images.githubusercontent.com/110554264/209492357-06c3a480-3836-45ee-ac66-971d2cc13f8d.png)

    
  - Predict credit risks using SMOTE model. This model achieves a balanced accuracy score of 62.77%, precision of high risk is 0.01, and recall score for high risk is 0.62
  
    ![image](https://user-images.githubusercontent.com/110554264/209492690-9ddcd173-834b-466a-b6f8-ded9748380e1.png)
    
    ![image](https://user-images.githubusercontent.com/110554264/209492726-4980a7fa-8ea8-410b-b7dc-76536f782bd7.png)


  - Predict credit risks using Undersampling model. This model gives a the same balanced accuracy score as the SMOTE model, precision of high risk is 0.01, and recall score for high risk is 0.61. 
    
    ![image](https://user-images.githubusercontent.com/110554264/209492846-3be769a5-028c-4936-92a4-57cec638c915.png)

    ![image](https://user-images.githubusercontent.com/110554264/209492872-c64400be-c970-4cf4-950e-5acd8c5af8a4.png)

  - Predict credit risks using Combination (Over and Under) Sampling with SMOTEENN algorithm. This model achieves a better balanced accuracy score of 64.11%, precision of high risk is 0.01, and recall score for high risk is 0.7
  
    ![image](https://user-images.githubusercontent.com/110554264/209493046-4dff2749-ca86-4c0f-acaa-3347fa8e2efa.png)

    ![image](https://user-images.githubusercontent.com/110554264/209493066-dd003080-b347-4541-96f0-11d1141e9c11.png)

  - Predict credit risks using Balanced Random Forest Classifier model giving an accuracy score of 78.77%, precision for high risk is 0.04, and recall score for high risk is 0.67
    
    ![image](https://user-images.githubusercontent.com/110554264/209493346-25677df6-f790-4926-9be8-cdc7e4f9f3ac.png)

    ![image](https://user-images.githubusercontent.com/110554264/209493367-abe263b7-4fb2-4cce-800b-c23722df2073.png)

  - Predict credit risks using Easy Ensemble AdaBoost Classifier model. This model provides the best balanced accuracy scores of 92.54% among 6 machine learning models being used, precision for high risk is 0.07, and recall score for high risk is 0.91
    
    ![image](https://user-images.githubusercontent.com/110554264/209493470-57df09a9-7147-4169-ba6e-c3d7ba5b53f8.png)

    ![image](https://user-images.githubusercontent.com/110554264/209493486-dbe890cc-1e97-4991-a678-adb9a5277e35.png)

## Summary
Among these 6 machine learning models being used to predict credit risk, Easy Ensemble AdaBoost Classifier had the highest balanced accuracy scores and seems to be the best model to use to predict credit risk. However, the F score of this model for high risk prediction is only 0.14 which means the quality or performance of this model on a dataset is very low. Therefore, I would suggest that instead of using these models, we should collect more data for a larger dataset for learning. This might expose a a different and more balanced perspective on the classes.
