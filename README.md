# Captcha Recognitoin

## Introduction
The goal of this project is to train a model used to recognize captcha. This project is developed from scratch on python and jupyter notebook.
The network is trained by TensorFlow on Nvidia Geoforce 1090 card.

## Result
Go to [test.ipynb](https://github.com/kevinlzb/Captcha-Recognition/blob/master/test.ipynb) to check the test result.

## Data preparation
1. Generate Captcha Images
  Used python ImageCaptcha library to generate raw images, with 4 numbers on it. The size of the raw image is 3 * 224 * 224
  There are 10k images, and it is enough to train the network.
  
2. Convert to tfrecord
  On [generate tfrecod](https://github.com/kevinlzb/Captcha-Recognition/blob/master/generate%20the%20dataset.ipynb), you can convert the raw 
  dataset to tfrecord file which is tensorflow friendly data format. I attached [this](https://indico.io/tensorflow-data-inputs-part1-placeholders-protobufs-queues/) article for understanding, which will be talking about 
  tfrecord, queuerunner etc.


  
 

