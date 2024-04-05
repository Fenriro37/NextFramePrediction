# Next frame prediction
## Description
Code for the project "Next frame prediction" for the course "Deep Learning" at the University of Bologna.


The project consists of predicting the next frame in a short movie sequence.

The used dataset is the Moving MNIST, composed of 10,000 video sequences, each consisting of 20 frames. Each video sequence is composed of two digits that move independently around the frame. The digits frequently intersect with each other and bounce off the edges of the frame.

While each sequence has a length of 20, we are going to use **only 3 consecutive frames as input**, and **predict the next one**.

My solution is based on the [SimVp](https://github.com/A4Bio/SimVP) model recreated using Keras.

## Example
![Alt text](https://github.com/Fenriro37/NextFramePrediction/blob/main/images/example.png)
