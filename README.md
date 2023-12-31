# Facial-Expression-Classifier
Written in python, this project utilizes scikit-learn and tensorflow to build, train and test convolutional neural networks to recognize human emotions in images of faces.

Example images:

![image](https://github.com/MillerAJ/Facial-Expression-Classifier/assets/9644656/8ae0f5e7-c05d-472b-9f16-c5e7bc33de75)


The model which achieved the highest accuracy, cnn_model_3c2, consisted of 32 convolutional layers feeding into a 25-layer artificial neural network. The model had 1,747,756 trainable variables, and with the assitance of data augmentation, it was able to achieve an accuracy of .83 on the test data. 

Classification report for cnn_model_3c2:

![image](https://github.com/MillerAJ/Facial-Expression-Classifier/assets/9644656/dd10974b-ef3e-4572-89e5-a47c0cd77c6c)






Search for "observation" in the notebook and cycle through results for a quicker, higher-level view of my comments as the notebook progresses.
