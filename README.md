# Pueumonia-Detection-Using-CNN

Detects a visual signal for pneumonia in medical images using convolutional neural networks (CNN)

•	This code was run on google colab with 32GB of RAM and high performance TPU

•	The model consists of 4 hidden layers, 1 input and output layer


## Approach

• Using Convulational Neural Network we segment the image, using bounding boxes (it is a area defined by two longitudes and latitudes) directly as a mask.

• Connected components is used to separate multiple areas of predicted pneumonia.

• The code at the terminal end is simply a bounding box drawn around every connected component traced by the model.

• The data is saved in a comma separated value file which gives the features along with the patient ID who are detected positive foe the pneumonia.
