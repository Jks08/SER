# SER
A Speech Emotion Recogniser(SER). 
It consists of an audio recorder code, a machine learning model and a predictor code to get the output.
The machine learning model was trained using Convolution Neural Network(CNN) and ADAM optimizer. The datasets used were RAVDESS and TESS.
The Audio Recorder records the audio for 5 seconds and sends it to the predictor. 
The predictor calls upon the ML model which is saved on the system as a '.h5' file. 
The input is fed and analyzed by the Model.
The output is given as a string. 

The RAVDESS and TESS datasets are extracted and put together under one folder and then supplied to the ML Model.
The Model has an accuracy of about 60% (very low), which can be improved by varying the optimizer values such as learning rate, decay rate, dropout, batch size, etc.

Make sure that the dataset files are extracted and stored in one folder named as 'Ravtess' which should be stored in your Jupyter notebook path (or you can store it anywhere just be sure to make the corresponding changes to the Path.).

You can also merge all 3 code files in one noebook, but make sure to run them in the order as follows: ML Model -> Audio Recording -> Predictor 
