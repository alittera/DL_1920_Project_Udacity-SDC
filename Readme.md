# Prediction of vehicle steering angles

This is a course project based on [Udacity Self-Driving Car second Challenge](https://medium.com/udacity/were-building-an-open-source-self-driving-car-ac3e973cd163)  
"The purpose of the challenge is to take image frames from a camera mounted to the windshield of our car, and predict the appropriate steering angle using convolutional neural networks and deep learning."

# Dataset 

It is possible to find tha dataset torrents in the original [location](https://github.com/udacity/self-driving-car) provided by udacity. 

# Our Solution - Poster

![enter image description here](url)
# Usage

All the code is divided in different ipython notebook, it possible to use the code installing the dependencies and running a notebook server.
At the beginning of each cell is it possible to change the default values of the parameters. 
The project has been divided in the following files:
- **Models.ipynb**: definition of models and train/test functions
- **MyDataset.ipynb**: dataset generator
- **Image_angles.ipynb**: generate frames and video with true and predicted angle 
- **Attention_map.ipynb**: generate frames and video of the attention map
- **Train.ipynb**: Training of then model (and testing)
- **RMSELoss.ipynb**: custom root mean square error 
- **Utils.ipynb**: utils for drawing on images and saving video files