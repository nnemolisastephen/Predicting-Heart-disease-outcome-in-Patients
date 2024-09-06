## HEART DISEASE PREDICTION

I built a predictive model using logistic regression algorithm that can predict whether a patient has a heart condition or not given the different features.

## Description of the project

Exploratory data analysis: 
I examined the distribution of each feature to the target label. 

Data Preprocessing: 
I checked for and handled missing values. I also managed outliers appropriately. Split the data into training and testing sets. 

Feature engineering: Used StandardScaler to scale my numerical features and made sure I prevented data leakage.

Model training: 
I trained a logistic regression model using solver = ‘saga’ and max_iter= 5000

Model evaluation: 
I evaluated my model using a classification report and then used the magnitude of the coefficients to determine which feature(s) has the strongest effect on the prediction output. Then, I tested my model on new data from an unknown patient. 
