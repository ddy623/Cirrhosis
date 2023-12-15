# Cirrhosis
The purpose of this task is to analyze Cirrhosis using Machine Learning. Cirrhosis is the late stage of scarring of the liver, which can be caused by liver diseases and conditions such as hepatitis and chronic alcholism. 
Features that play a role in predicting Cirrhosis are Age, Sex, Cholesterol, Bilirubin, Platelets, and so on.  
In order to analyze the impact of Cirrhosis, it was decided to use 'Status' as the target.  This enabled the data to focus on the patient (c), patient censored due to liver treatment, and death.
The data showed that there was a higher number of people among the censored group, second was death and last was the group with treatment.  ![download](https://github.com/ddy623/Cirrhosis/assets/129712664/f97ab0cc-432a-4b0d-a3a9-8f4a7f554c10)

Final Analysis:
This model used various methods to attempt to make a prediction as to what persons would likely develop Cirrhosis of the liver. For example, we used feature engineering such as PCA, 
Wrapper Method, and Random Forest Classifier.  
Using PCA, the model showed an overall accuracy of 0.75% on the test data. We also used PCA with a variance of 0.85%, which showed an overrall accuracy of 0.74%.  
Using the model without PCA, the results showed an overrall accuracy of 1.00 on the train data but on the test data, it showed 0.79%

When using feature selection, the model showed an overrall accuracy of 0.79 and when using the Wrapper Method, there was a 0.55 level of accuracy on the test data.  On the other hand, for the train data, there was an accuracy level of 0.86, as this indicates overfitting with the model.
In using neural networks, the results showed an overrall accuracy of 0.29, which is the lowest of all the models. It can be assumed that the models were not able to have high accuracy due to overfitting, which potentially contributed to the model not being able to generalize the data.


