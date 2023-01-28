# DDoS_detector_by_ML
Each piece of code has been commented out briefly. <br><br>
In the beginning, we must apply some pre-processing tasks on our raw data, in which pre-processing part has raw data as an input with a shape of (225745, 79) and a ready CSV file as an output (225741, 67). <br>
Some additional extracting information has been applied to data, such as which port is most used or how many attacks happened on it etc. <br>
ML-model-applying part will directly go for applying cross-validation and then applying the models by using a function which will make fit, predict, gather the metric values (accuracy rate, precision score, recall score, and f1) and plot the confusion matrix faster, and more convenient. <br><br>
One example of outputs that is for the RandomForest model (n_estimators = 60): <br>
![randomforest_60](https://user-images.githubusercontent.com/123311716/215292461-9e3ffa2e-956e-4144-8783-4c4486ed2267.PNG)
