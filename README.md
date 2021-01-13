# multipleLinearRegression
 simple multiple linear regression to compare if adding some random variable will be a good predictor or not compared with adding relevant variable. This code is extended version of [Simple Regression](https://github.com/hasbiabdulmajid/linearRegression) by adding 1 more variable (column)
 
 ## Reference
 This code is my training with following 365 Data Science Course
 
 ## Dataset
 - *Multiple linear regression.csv*
 this dataset is contain table with 3 column 'SAT','GPA', and 'Rand 1,2,3'. This dataset is dataset that contain random variable that used in *multipleLinear1.ipynb* and *multipleLinear3.ipynb*
 - *Dummies.csv*
 this dataset is contain table with 3 column 'SAT','GPA', and 'Attendace'. This dataset is dataset that contain relevant variable that used in *multipleLinear2.ipynb*
 
 ## Library Used for Regression
 - Stats Model (OLS) for *multipleLinear1.ipynb* and *multipleLinear2.ipynb*
 - Sklearn Linear Regression for *multipleLinear3.ipynb*
 
 ## Result
 the *Attendance* and *SAT* predictor has better result compare to *Rand 1,2,3* Predictor for GPA because *Rand 1,2,3* have a 'high' p-value compared *Attendance* and *SAT* p-value also *Rand 1,2,3* have a 'Weight' value that very close to zero (-0.00703) and because closer weight value to zero the smaller the impact so the *Rand 1,2,3* variable does not contribute to the model. In the end after trying to drop the *Rand 1,2,3* variable the prediction  almost have same result without droping it and have same result after rounded it up.
