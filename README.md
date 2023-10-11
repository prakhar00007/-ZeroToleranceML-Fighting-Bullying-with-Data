## **Protect The Vulnerable**


**_This project builds a neural network model to predict if a person will engage in bullying behavior again in the future, based on survey data._**

## **DATA** 
**_This project builds a neural network model to predict if a person will engage in bullying behavior again in the future, based on survey data._**

- _Age_
- _Gender_
- _Type of bullying done (verbal, physical, cyber)_
- _Reason for bullying_
- _Location of bullying_
- _Victim identity (strangers, friends, etc)_
- _Response after bullying_
-  _Perceived severity_
-  _Consequences_
- _Will bully again (target variable)_


**_There are 10 total features and the target is a binary classification - Yes or No for "Will bully again"._**

## **Analysis** 
- _The data is explored through visualizations of the target variable across the other features._
- _The categorical features are label encoded to numeric._
- _The data is split into training and test sets._
- _The training data is resampled using SMOTE to handle class imbalance._

## **Model**
- _A neural network model is built with the Keras API, including:_
  - _Input layer for the 9 features_
  - _Hidden layers of 64, 128, 256, 64, 16 units with ReLU activation_
  - _Output layer with sigmoid activation for binary classification_

- _The model is trained for 100 epochs._


## **Results** 
- _The model achieves 76% accuracy on the test set._
- _Additional tuning could improve performance further._

