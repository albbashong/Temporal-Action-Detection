# Temporal Action Detection based on Action Former


## Introduction

This code implements temporal action detection model, using Pooling layer with convolution layer.
This code based on Actionformer[this link](https://arxiv.org/abs/2211.09074). [this link](https://github.com/happyharrycn/
actionformer_release)



## Code Overview
The structure of this code repo is heavily inspired by Detectron2. Some of the main components are
* ./libs/core: Parameter configuration module.
* ./libs/datasets: Data loader and IO module.
* ./libs/modeling: Our main model with all its building blocks.
* ./libs/utils: Utility functions for training, inference, and postprocessing.

## Installation
* Follow INSTALL.md for installing necessary dependencies and compiling the code.

## Frequently Asked Questions
* See FAQ.md.

**Unpack Features and Annotations**
* Unpack the file under *./data* (or elsewhere and link to *./data*).
* The folder structure should look like
```
This folder
│   README.md
│   ...  
│
└───data/
│    └───thumos/
│    │	 └───annotations
│    │	 └───i3d_features   
│    └───...
|
└───libs
│
│   ...
```
