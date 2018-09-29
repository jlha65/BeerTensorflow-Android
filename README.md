# TensorFlow Android Beer Recognition Demo


## Description

Use of https://github.com/tensorflow/tensorflow/tree/master/tensorflow/examples/android with a replaced frozen graph model designed to recognize the following beers:

- sol
- indio
- tecate
- xx
- miller
- bohemiaP
- strongbowA
- strongbowR
- heineken
- carta
- indioC
- tecateC
- heineken6

Very slow, in my Le Max 2 phone loads one inference per about 8-10 seconds. This is due to the model being faster-rcnn and not optimized.
