# appplication_identity_fraud_project

Identity fraud or identity theft is a common type of fraud where a suspect deliberately uses 
another person’s personal identifying information without authorization or creates synthetic 
identity information in some way to conduct fraud or deception activities in favor of unlawful 
benefits. This type of fraud usually happens in the financial world, in particular, the banking 
industry. 

This project will be **focusing on identifying and predicting fraud applications in the 
identification application process by building a data-driven algorithm.** The overall goal of the 
project is to find the most effective and efficient statistical analysis model to predict and 
identity fraud applications. 

The report details the creation and completion process of a supervised machine learning 
algorithm that can perform real-time fraud detection. Our team has decided to accomplish our 
overall project goal by completing the following five objectives: 
  1. Data cleaning – detect, correct, and remove inaccurate/corrupted/incomplete/duplicate 
data records from the dataset
  2. Feature creation – construct new and insightful features from existing data entries to 
train a machine learning model
  3. Feature selection – select a subset of features by reducing the number of input 
variables 
  4. Modeling – establish machine learning models, train and test the models to discover 
the most efficient and effective model
  5. Model analysis and conclusion – analyze models created in the previous steps and 
make recommendations for future application fraud identification process

Our team has utilized many different algorithms to fit the data, including Logistic Regression, 
Random Forest, XGBoost, Light GBM, and Neural Network. We have also tried several 
combinations of parameters for each model and compared the performance of different 
models based on FDR at a 3% rejection rate.

Among all these models, a LightGBM Classifier (n_estimators=600, max_depth=5, 
min_child_samples, num_leaves=20, subsample=0.6, colsample_bytree=0.8, 
learning_rate=0.05) was selected as our best and final model. The FDR scores achieved by 
this model on training, testing, and OOT data are 56.17%, 55.61%, and 53.55%. The key 
statistics of the top 20 bins also show that our final model has a good performance in 
detecting fraud.

We also discussed the potential future improvements for our model, such as building more 
expert features and performing more hyperparameters tuning.
