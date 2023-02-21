# Credit_Risk_Analysis

## Results

### Naive Random Oversampling

![Screenshot (167)](https://user-images.githubusercontent.com/114521887/220454448-b665e787-52d2-441f-93f2-3585420ee3ab.png)

Balanced Accuracy Score: 0.6293939430565123

### SMOTE Oversampling

![Screenshot (169)](https://user-images.githubusercontent.com/114521887/220454608-b72aa080-c8e9-437b-866f-8136359e862f.png)

Balanced Accuracy Score: 0.6277008271188627

### Cluster Centroids Undersampling

![Screenshot (171)](https://user-images.githubusercontent.com/114521887/220455103-ec47346b-f18e-4e0d-be76-81889d70a851.png)

Balanced Accuracy Score: 0.5103893461611291

### SMOTEENN Combination Sampling

![Screenshot (173)](https://user-images.githubusercontent.com/114521887/220455376-2b2136e5-44d9-4806-b844-8683a06f518d.png)

Balanced Accuracy Score: 0.6411460410698961


### Balanced Random Forest Classifier

![Screenshot (164)](https://user-images.githubusercontent.com/114521887/220453698-8a717ef8-519a-4cf6-b574-7d00b918b6e2.png)

Balanced Accuracy Score: 0.8731182795698925

### Easy Ensemble Classifier

![Screenshot (165)](https://user-images.githubusercontent.com/114521887/220453764-7954a3e0-f611-49e1-ba37-bd3fcf220d27.png)

Balanced Accuracy Score: 0.9316600714093861

## Summary

When we look at our balanced accuracy scores, the Easy Ensemble AdaBoost Classifier is the best model to use with a Balanced Accuracy Score of 0.93. The Balanced Random Forest Classifier came closest with a Balanced Accuracy Score of 0.87. Each of our other models produced low Balanced Accuracy Scores of all less than 0.65. The Easy Ensemble AdaBoost Classifier model also had the highest recall score. Given the results, it seems the Easy Ensemble AdaBoost Classifier model is the best machine learning model to use for credit card analysis.


