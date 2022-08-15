1. This code is for Tomato crop leaf disease prediction
2. Lybraries used: Keras, Tensorflow, Numpy, Matplotlib, Sklearn 
3. Platform used : Jupyter Notebook  
4. Dataset : Downloaded from public domain Kaggle datset
5. Classes : Three classes(Diseases) created to predict the diseases
6. Dataset size : 300 images
7. Dataset splitting: we have splitted the Dataset as 80% training, 10% Validation and 10% Testing
8. Deep learning model : CNN
9. To train the model following input required, like Image Size=256, Batch Size=32, Channels = 3(RGB), Epochs = 10
10. In preprocessing step: 
	The all input images are unified by resizing 256*256, 
	rescaling 1 to 255, and data augmnetation by random flip
11. For classification we used CNN model with 32 features, kernel size (3,3), pooling (2,2), and activiation function: softmax
12. Performance the model achieved accuracy around 68%
