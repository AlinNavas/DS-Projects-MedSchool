# Projects
DS projects using medical data

DS Proj 1 - Using clinical symptoms to accurately predict type 2 DM
This notebook attempts to use multiple supervised machine learning approaches such as KNN, Logistic regression, SVM and Decision trees to diagnose Diabetes Mellitus by solely relying on clinical symptoms and not on traditional laboratory investigations like FBS (fasting blood sugar)/ PPBS (Post prandial blood sugar)/ HbA1c (glycated hemoglobin).


DS project 2 - Using multiple body circumferences to estimate body fat.
This notebook attempts to build a ML model using multiple linear , ridge , lasso regression and regression trees to predict body fat using multiple body circumferences without relying on the density calculated from underwater weighing.


DS proj 3 -  Predicting recurrance of breast cancer based on histopathological findings
 I used PCA to identify the 9 principle components that use reduce the number of dimensions inputed from 24 to 9. These 9 components which are linear combinations of the 24 initial features, explain 90 percent of the variance of the original dataset. I then built a MLP model and train it on the 32 featured data set ad get an f1 score of .69. I then train the same model on 9 component PCA transformed data. The f1 score improved marginally to 0.71.


DS proj 4 -  Attempting to use CNN and transfer learning to differentiate the different histopathological types of non small cell lung carcinomas (NSCLC) using just CT scans
This notebook attempted to  differentiate the different histopathological types of lung carcinomas using just CT scans (i.e without invasively taking histopathological samples) via a basic 12 layered CNN and later applies a transfer learning approach with ResNet50 ,a very deep CNN model that has been pre trained using a massive image set called imagenet to try to imporve accuracy.
