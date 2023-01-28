# DDoS_detector_by_ML
Each piece of code has been commented out briefly. <br><br>
In the beginning, we must apply some pre-processing tasks on our raw data, in which pre-processing part has raw data as an input with a shape of (225745, 79) and a ready CSV file as an output (225741, 67). <br>
Some additional extracting information has been applied to data, such as which port is most used or how many attacks happened on it etc. <br>
ML-model-applying part will directly go for applying cross-validation and then applying the models by using a function which will make fit, predict, gather the metric values (accuracy rate, precision score, recall score, and f1) and plot the confusion matrix faster, and more convenient.
