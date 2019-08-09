# Colorisation-Autoencoder
Use AI to color black and white pictures


The purpose of this project is to create a deep learning algorithme that will convert a black and white picture into a colorized picture.

The picture dataset is the content of my phone.
The first script preprocessing loop through the picture resizing and converting it and in black and white.
Then the picture are saved as numpy array.

Model 1 : Autoencoder Conv - Conv - Conv - Dense - Deconv - Deconv


Model 2 : tune VGG16 model.
  Use the 10 fisrt layers of the VGG16 as encoder in order to get to have an abstract representation of the picture.
  Then use convolution in the decoder to generate the picture.
