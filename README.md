# Super Resolution Generation with Efficient Sub-Pixel (SRGAN)

## Introduction

* Efficient Sub-Pixel is a model that reconstructs a high-resolution version of an image given a low-resolution version. It takes advantage of efficient "sub-pixel convolution" layers, which learn a series of image scaling filters.

![](https://miro.medium.com/max/1400/1*HzJlV2c6XOzRyTojleJdGQ.jpeg)

## Conv 2D

* Conv2D class. 2D convolution layer (e.g. spatial convolution over images). This layer creates a convolution kernel that is convolved with the layer input to produce a tensor of outputs. If use_bias is True, a bias vector is created and added to the outputs.