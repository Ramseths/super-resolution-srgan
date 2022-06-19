# Super Resolution Generation with Efficient Sub-Pixel (SRGAN)
![GitHub last commit](https://img.shields.io/github/last-commit/Ramseths/super-resolution-srgan)
![License](https://img.shields.io/github/license/Ramseths/super-resolution-srgan)
![GitHub repo size](https://img.shields.io/github/repo-size/Ramseths/super-resolution-srgan)

## Introduction

* Efficient Sub-Pixel is a model that reconstructs a high-resolution version of an image given a low-resolution version. It takes advantage of efficient "sub-pixel convolution" layers, which learn a series of image scaling filters.

![](https://miro.medium.com/max/1400/1*HzJlV2c6XOzRyTojleJdGQ.jpeg)

## Dataset

* [Go to Dataset](https://www2.eecs.berkeley.edu/Research/Projects/CS/vision/grouping/BSR/)

* Natural Images

## Conv 2D

* Conv2D class. 2D convolution layer (e.g. spatial convolution over images). This layer creates a convolution kernel that is convolved with the layer input to produce a tensor of outputs. If use_bias is True, a bias vector is created and added to the outputs.

## Peak Signal-to-Noise Ratio
* Is an expression for the ratio between the maximum possible value (power) of a signal and the power of distorting noise that affects the quality of its representation.  Because many signals have a very wide dynamic range, (ratio between the largest and smallest possible values of a changeable quantity) the PSNR is usually expressed in terms of the logarithmic decibel scale.
