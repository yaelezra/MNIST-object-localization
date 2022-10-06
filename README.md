# MNIST-object-localization

In this project I used the MNIST dataset to build an object localization network. 

First, the MNIST 28X28 images were placed in bigger images 50X50.

Then, a CNN with a classification head and a regression head, predicts the digit in the big image and its bounding box. The CNN was evaluated using confusion matrix, MSE and accuracy. 

Lastly, I used data augmentation methods on some of the images. A new CNN network ran on the new dataset. 
