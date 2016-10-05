## Packages Used
1. scikit-learn 0.17.1 http://scikit-learn.org/stable/
   <br> sudo pip install scikit-learn
2. pandas 0.18.1 http://pandas.pydata.org/ <br> sudo pip install pandas
3. numpy 1.11.1 http://www.numpy.org/ <br> sudo pip install numpy
4. xgboost 0.6 https://github.com/dmlc/xgboost/tree/master/python-package 
5. keras 1.0.8 https://keras.io/#installation <br> sudo pip install keras

## Dependencies for packages 
1. scipy 0.18.0 https://www.scipy.org/ <br> sudo pip install scipy

## Procedure to generate final output file:
1. Keep all the training and testing files and the scripts in one folder and set the working directory to that folder. 
2. Run gbm.py to generate intermediate predictions with gbm model. 
3. Run xgb.py to generate intermediate predictions with xgb model. 
4. Run keras_try.py to generate intermediate predictions with keras neural network. 
5. Run averager.py to generate the final predictions with an average for all models. 
