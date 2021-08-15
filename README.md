## Overview
The purpose of this analysis was to predict credit risk through suverised machine learning. Our model utilizes oversampling, undersampling, and a SMOTEENN algorithm to generate this analysis.

## Results
We have recorded precision scores, accuracy scores, and recall scores.

![Screen Shot 2021-08-15 at 1 33 40 PM](https://user-images.githubusercontent.com/82029390/129487202-f895a8cc-790e-4a36-930c-99e66a31121c.png)


Our calculated accuracy score is 65%. Our generated precision for our high-risk is 1% and the F1 score is 2%. These scores do not suggest that our model would be satisfactory in classification.




### SMOTE Oversampling Model

![first_screenshot](https://user-images.githubusercontent.com/82029390/129487137-345ee37b-a6e5-4ec4-86f9-4881690e868d.png)

Our SMOTE oversampling model appears to be roughly the same as our random oversampling shown previous. The precision for high risk is still at 1% and F1 score is 2%. The balances accuracy score is still 65%

### Undersampling

![Screen Shot 2021-08-15 at 1 37 35 PM](https://user-images.githubusercontent.com/82029390/129487313-4104dffb-394f-481c-9d30-9012100bca72.png)

Our undersampling model returns an accuracy score of 51%, much lower than the two models we assessed previously. Both the precision score and F1 score are 1%.


## Summary

We can thus see that various supervised machine learning models can be used, some more accurate than others. The gap between high risk a low risk loans remains large. Our easy ensemble AdaBoost classifier returns to us the largest accuracy score(as seen in our jupyter notebook). It records the highest accuracy score and F1 score and it would thus be prudent to use this model among the others.


























