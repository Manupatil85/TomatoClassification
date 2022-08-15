This code is for Tomato crop leaf disease prediction
Lybraries used: Keras, Tensorflow, Numpy, Matplotlib, Sklearn 
Platform used : Jupyter Notebook  
Dataset : Downloaded from public domain Kaggle datset
Classes : Three classes(Diseases) created to predict the diseases
Dataset size : 300 images
Dataset splitting: we have splitted the Dataset as 80% training, 10% Validation and 10% Testing
Deep learning model : CNN
To train the model following input required, like Image Size=256, Batch Size=32, Channels = 3(RGB), Epochs = 10
In preprocessing step: 
	The all input images are unified by resizing 256*256, 
	rescaling 1 to 255, and data augmnetation by random flip
For classification we used CNN model with 32 features, kernel size (3,3), pooling (2,2), and activiation function: softmax
Performance the model achieved accuracy around 68%
