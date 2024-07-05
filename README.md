# Challenge 13 - Classification; Spam Detector
--------
## Overview and agenda for spam detection
1. Import dependencies
- pandas
  - Used for all data related tasks (ex. data manipulation)
- train test split
  - A class within sklearn.model_selection, which is used to split the training and testing data
- accuracy score
  - A class within sklearn.metrics, which is used to retrieve the accuracy score to predict model performance
- StandarScaler
  - A class within sklearn.preprocessing, which is used to enhance model performance
- LogisticRegression
  - A class within sklearn.linear_model, which is used for logistic regression models
- RandomForestClassifier
  - A class within sklearn.ensemble, which is used for random forest classification models
2. Retrieve the data
- Import CSV
3. Split the data into training and testing sets
- Create the labels set 'y' and features DataFrame 'X'
- Check the balance of the label variables
- Split the data into X_train, X_test, y_train, y_test
3. Scale the features
- Create the StandardScaler instance
- Fit the Standard Scaler with the training data
- Scale the training data
4. Create and fit a Logistic Regression Model
- Train a Logistic Regression model and print the model score
- Make and save testing predictions
  - View testing predictions
- Calculate the accuracy score
5. Create and fit a Random Forest Classifier Model
- Train a Random Forest Model and print the model score
- Make and save testing predictions
  - View testing predictions
- Calculate the accuracy score
6. Evaluate the Models
- The Random Forest Model has a higher accuracy score.
-----------------
### Additional sources
#### Sources like ChatGPT, Xpert learning assistant, AskBCS, Google, YouTube, and Columbia provided tutoring were used for clarification, and debugging if/where needed.
