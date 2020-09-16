# MNIST

Goal: Create a model that recognizes images of numbers 0-9. <br/>

MNIST1 is first used to create 540,000 extra images with elastic distortion. <br/>
MNIST2 is a pure numpy implementation of a 2 layer neural network, the model trained had an accuracy of 96.66% accuracy on test data. <br\>
MNIST3 uses tensorflow.keras and implements a CNN, accuracy of 99.59%. <br\>

Training the CNN for 10 epochs took more than 5 hours! There are people who used data augmentation to generate many millions of images. <br\>
I might try this again once I get a usable GPU. <br\>
