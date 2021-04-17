# SER
This Speech Emotion Recogniser(SER) was built using Jupyter Notebook. 
It consists of an audio recorder code, a machine learning model and a predictor code to get the output.
The machine learning model was trained using Convolution Neural Network(CNN) and ADAM optimizer. The datasets used were RAVDESS and TESS.
The Audio Recorder records the audio for 5 seconds and send it to the predictor. 
The predictor calls upon the ML model which is saved on the system as a '.h5' file. 
The input is fed and analyzed by the Model.
The output is given as a string. 
