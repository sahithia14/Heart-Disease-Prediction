# A Novel Approach to the Diagnosis of Heart Disease using Machine Learning and Deep Learning



## Dataset Description: 

This data set is from the UCI Machine Learning library, and it can be found here: http://archive.ics.uci.edu/ml/datasets/Heart+Disease 

This data set currently contains 303 instances. From a maximum of 76 features in the dataset, 14 relevant features were extracted.

The target variable is feature # 14, which represents any narrowing in any major blood vessel due to cholesterol and plaque deposits, as detected through the use of an angiogram. This is a key indicator of heart disease, and can be used as the basis for prediction.  More information about coronary heart disease can be found here: https://www.mayoclinic.org/diseases-conditions/coronary-artery-disease/symptoms-causes/syc-20350613

Feature #14 has also been reduced to a binary problem to detect the presence of any vessel narrowing; the levels of severity will not be the main goal of this specifc project 


## Project Summary:

  According to BBC news, 1 out of every 3 heart disease cases are misdiagnosed. Heart Disease continues to be the leading cause of death in many countries, and a conclusive and early diagnois can be the difference between life and death.  The use of Machine Learning (ML) techniques and Deep Neural Networks (DNN) can mitigate the possibility of human error while increasing prediction accuracy rates.
  
  Machine learning models such as Random Forest, Naive Bayes, K-Nearest Neighboors, and Support Vector Machine were trained using GridSearch Optimization and various hyperparameter tuning techinques. After evaluating all models, the Random Forest algorithm preformed the best with a 83 percent accuracy. A Deep Neural Network was also developed using a gradient descent optimization and dropout regularization. This neural network had a 94% accuracy after k-fold cross validation, and a Matthews Correlation Coeffcient of 0.91. 
  
  Comparing the winning Machine Learning algorithim (Random forest) with the Deep Learning algorithm illustartes how the Deep Neural Network outperformed the Machine Learning Model. Thus, the deep neural network is used for the heart disease diagnostic tool, built through Python Flask. 
  
  
  ###### [Poster](https://drive.google.com/file/d/1PPnvQyqsieQ1u0aSWUt5iOaHYtIPZZxO/view?usp=sharing)
  ###### [Paper](https://drive.google.com/file/d/1JIIpSb1ZlV79cKrQgYABZJMG1iRvLU82/view?usp=sharing)




