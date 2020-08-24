# Intrusion-Detect-Attack-recognition-Based-on-Randomforest-XGBoost
## Details: 
In this project, I built a model for intrusion detection based on the KDD99 dataset. First I explored the data, conducted data preprocession, dropped all the features whose variance was 0, and some features that had the same correlations. After splitting the dataset, obtaining the train set, and test set, I trained the models based on Random Forest & XGBoost and adjusted relevant parameters using gridSearchCV. Finally, I stacked the two models using the Logistic Regression algorithm.

## Results: 
After stacking the two models using the LR algorithm, the performance had been increased greatly. The accuracy is around 0.976 on the test set. Through this project, I have a clearer insight into machine learning skills, such as the workflow and where you should pay attention to if the model doesn't work well.
