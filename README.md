# SWAT_data_Attack_Prediction
Using SWAT(Secure water treatment testbed) data to predict when the system is under attack. We are using 6 known types of attacks to apply machine learning algorithm  .
We are applying feature selection method to reduce the number of features from 52 to 10 using Chi square method. Selecting 10 features from PCA as we found out that keeping 10 top features will retain 99.97% of data information.
Then we apply ensemble method to train and test data using different ML algorithms on test data.
The data we observed are:
# LGR+RFC+SVM(5)+SVM(8)+MLP
Test Accuracy: 0.9993762993762993 
Val Accuracy: 0.9993761696818465 
Train Accuracy: 0.9993761696818465
# LGR+RFC+SVM(5)+SVM(8)
Test Accuracy: 1.0 
Val Accuracy: 1.0 
Train Accuracy: 1.0
# LGR+RFC+SVM(5)
Test Accuracy: 1.0 
Val Accuracy: 1.0 
Train Accuracy: 1.0
# LGR+RFC
Test Accuracy: 0.9991683991683992 
Val Accuracy: 0.9989602828030776 
Train Accuracy: 0.9990642545227698
# LGR
Test Accuracy: 0.9985446985446985 
Val Accuracy: 0.9983364524849241 
Train Accuracy: 0.9984404242046163
# RFC
Test Accuracy: 1.0 
Val Accuracy: 1.0 
Train Accuracy: 1.0
# SVM(5)
Test Accuracy: 0.9993762993762993 
Val Accuracy: 0.999168226242462 
Train Accuracy: 1.0
# SVM(8)
Test Accuracy: 0.7796257796257796 
Val Accuracy: 0.7797878976918278 
Train Accuracy: 0.7797878976918278
# MLP(5,5,2)
Test Accuracy: 0.8667359667359668 
Val Accuracy: 0.866916198793928 
Train Accuracy: 0.8668122270742358
# LGR+RFC+SVM(5)+MLP
Test Accuracy: 1.0 
Val Accuracy: 1.0 
Train Accuracy: 1.0

