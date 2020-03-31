# project-ml-twitter-sentiment-analysis
project-ml-twitter-sentiment-analysis created by GitHub Classroom
- Import the required Python libaries at one place
- Place the train and test data files in the same folder as that of the notebook
- Read the train and test data set from the folder
- Perform Exploratory Data Analysis(EDA) and cleansing on the merge(train + test) tweets
- Perform Stemming and Tokenziation on the cleaned tweets using NLTK 
- Create features for Bag of words, TF-IDF, Word to Vector and Document to Vector using Gensim model 
- Evaluate the below mentioned classification model on the basis of high F1- Score:
	1. Logistic Regression
	2. Support Vector Machine
	3. RandomForest (tree based algorithm)
	4. XGBoost (tree based algorithm)
	
- Hyper Parameters Tuning for the XGBoost model for params:
    1.  max_depth 
    2.  min_child_weight 
    3.  eta 
    4.  subsample 
    5.  colsample_bytree 
- Replace the parameter value of previous params before you tune next set of params
- Predict the values using the tuned model on the test sample shared.
