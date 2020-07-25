# machine-learning-challenge
EXOPLANET CLASSIFICATION BY USING MACHINE LEARNING ALGORITM

Nasa’s exoplanet exploration program let us observe objects outside of our solar system.  KOI Kepler object of interest has been classified as exoplanets or a false positive. The task to identify a planet is taking too much effort and resources by satellites. The data about this program is now public, so because of it we can use it and apply Machine learning techniques to help in classifying these objects as exoplanets or not.

This exercise follows 3 Machine Learning Models: Logistic Regression, Decision Tree and Random Forest, all of them are well known for classification purposes.
The next diagram follows the steps taken within each process:

1.-Data Engineering
2.-Train Model 
3.-Test Model 
4.-Get conclusions.

After running the tree models, we found the following results:



Logistic Regression	0.83	On test data
Decision Tree	0.89	On test data
Random Forest	0.92	On test data



Random Forest:
Is a supervised learning algorithm, it has been used for Classification in a regression problem. This algorithm creates decision trees a get a prediction for each of them. Finally selects the best solution by means of voting. As we observed in the table above Random Forest performed better than the other models. With 0.92 %  on score, Random Forest was the best ML model to predict if the KOI is CONFIRME as a exoplanet of it remains as FALSE POSITIVE.

Take a look at each model process to review the steps followed in each case.
