Procedure to generate final output file:
1. Keep all the training and testing files and the scripts in one folder and set the working directory to that folder. 
2. Run gbm.py to generate intermediate predictions with gbm model. 
3. Run xgb.py to generate intermediate predictions with xgb model. 
4. Run keras_try.py to generate intermediate predictions with keras neural network. 
5. Run averager.py to generate the final predictions with an average for all models. 