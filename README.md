# TorchOpenl3 Model Weights
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

All the weight files are ported from Openl3 [Openl3 Library](https://github.com/marl/openl3)<br/>

We import the weights of Spectogram and Melspectgrom layer as Numpy array and then load in Pytorch model.<br/>
Except these layers for all layers we used [MMdnn](https://github.com/microsoft/MMdnn) to import the weights from keras to Pytorch.<br/>
After loading the weights in model we save the model weights in .pth.tar files.