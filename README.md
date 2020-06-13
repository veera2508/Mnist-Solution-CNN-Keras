# Mnist-Solution-CNN-Keras
Solution for the mnist dataset using a CNN created with the keras programming framework. 99% accuracy.
Dataset needs to be downloaded,
Feel free to change the model and test the accuracy!

Network Structure:
Model: "sequential_1"
_________________________________________________________________
Layer (type)                 Output Shape              Param #   
=================================================================
Conv1 (Conv2D)               (None, 26, 26, 15)        150       
_________________________________________________________________
Conv2 (Conv2D)               (None, 22, 22, 30)        11280     
_________________________________________________________________
MaxPool (MaxPooling2D)       (None, 11, 11, 30)        0         
_________________________________________________________________
Flatten (Flatten)            (None, 3630)              0         
_________________________________________________________________
Dense1 (Dense)               (None, 250)               907750    
_________________________________________________________________
Dropout (Dropout)            (None, 250)               0         
_________________________________________________________________
Dense2 (Dense)               (None, 10)                2510      
=================================================================
Total params: 921,690
Trainable params: 921,690
Non-trainable params: 0

