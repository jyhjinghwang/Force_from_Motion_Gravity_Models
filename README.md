# Force from Motion Gravity CNN Models

This is the repository for releasing trained CNN models for gravity prediction of the paper, "Force from Motion: Decoding Physical Sensation from a First Person Video" in CVPR 2016.

For more information, please visit our project webpage: http://www.seas.upenn.edu/~hypar/ffm.html


## Model Definition

We use Caffe deep learning framework: http://caffe.berkeleyvision.org/

The CNN models are fine-tuned from ImageNet-pretrained AlexNet with the following input/output modifications:

* Image resolution is (180, 320), instead of (227, 227).

* Output of the network is 61 dimensions. It predicts the probability of projected gravity angle discretized by 1 degree between -30 and 30 with the 31th dimensions as 0 degree.

Please check the sample prototxt file.


## Available Models

There are 3 models fine-tuned for different scenarios: biking (taxco), skiing, and jet-skiing.

Due to the size limitation of Github, please download the trained models from: 
https://upenn.box.com/v/gravity
