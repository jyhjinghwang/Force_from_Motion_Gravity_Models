# EgoPhysics Gravity CNN Model

This is the repository for releasing trained gravity CNN models of the paper, "Force from Motion: Decoding Physical Sensation from a First Person Video" in CVPR 2016.

For more information, please check the project webpage: http://www.seas.upenn.edu/~hypar/ffm.html


## Model Definition

The CNN models are fine-tuned from ImageNet-pretrained AlexNet with the following input/output modifications:

The input resolution is (180, 320), instead of (227, 227).

The output is 61 dimensions. It predicts the probability of projected gravity angle discretized by 1 degree between -30 and 30 with the 31th dimensions as 0 degree.


## Available Models

There are three models fine-tuned for different scenarios: biking (taxco), skiing, and jet-skiing.


Due to the size limitation of Github, please download the trained models from: 
https://upenn.box.com/v/gravity
