# Behavioural Cloning in Self Driving Cars using Python
In this project i developed a Self-Driving Car model using technique called Behavioural Cloning using deep Convolutional Neural Networks that can steer a car in a simulator provided by Udacity. The CNN drives the car autonomously around a track. The network is trained on images from a video stream that was recorded while a human was steering the car. The CNN thus clones the human driving behavior.


The goals / steps of this project are the following:
* Use the simulator to collect data of good driving behavior
* Build, a convolution neural network in Keras that predicts steering angles from images
* Train and validate the model with a training and validation set
* Test that the model successfully drives around track one without leaving the road
* Summarize the results with a written report

## Getting started

The project includes the following files:
* Behavioural_Cloning.ipynb containing the script to create and train the model
* drive/drive.py for driving the car in autonomous mode in Udacity Self-Driving Car Simulator
* drive/model.h5 this is model i trained using convolution neural network 

## CNN Model in Action

You need to download and unpack the [Udacity self-driving car simulator](https://github.com/udacity/self-driving-car-sim) (Version 1 was used).

To run my trained model with drive.py code start the simulator in `autonomous mode`, open another shell and type 

```
> git clone https://github.com/abidaks/self-driving-car-behavioural-cloning
> cd self-driving-car-behavioural-cloning
> python drive/drive.py
```

Then you will see the model driving the car in autonomous mode.

## Training Your own Model
I recomend to train your Behavioural Cloning in Self Driving Cars model using [Google Colab](https://colab.research.google.com/).

Upload the Behavioural_Cloning.ipynb to your drive folder and run it, when the training complete code will download model.h5 file to your local directory. Copy the file to same folder as drive.py file is located and run the drive.py file to see your own trained model in action.

## License
[MIT](https://choosealicense.com/licenses/mit/)