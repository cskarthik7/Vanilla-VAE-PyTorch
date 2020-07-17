

        
        


# Simplified Vanilla-Variational Autoencoders in PyTorch 

![codecov.io Code Coverage](https://img.shields.io/codecov/c/github/dwyl/hapi-auth-jwt2.svg?maxAge=2592000) 
[![Generic badge](https://img.shields.io/badge/PyTorch-Passing-<COLOR>.svg)](https://shields.io/)


# Data Used [![Generic badge](https://img.shields.io/badge/kaggle-ChestXRAY-blue.svg)](https://shields.io/) :

Chest XRAY Images(Source - Kaggle)

This dataset contains Chest XRAY images with 2 classes - healthy Chest XRAY Images , Pneumonia Chest XRAY Images

Sample Image : 

![alt text](https://github.com/cskarthik7/Vanilla-VAE-PyTorch/blob/master/download.jpeg?raw=true)


# Model Architecure ![Code Climate](https://codeclimate.com/github/dwyl/esta/badges/gpa.svg) : 

The model is based on Encoder-Decoder networks .

The Encoder downsamples the image with two key differen hidden layers : mu(Learned mean) and sigma(standard deviation)

The decoder Network upsamples the samples reparameterised from the outputs of the encoder(mu and sigma)

Optimizer used : Adam

Loss functions : KL Divergence Loss and Binary Cross Entropy Loss

# Training [![Generic badge](https://img.shields.io/badge/Code-Passing-blue.svg)](https://shields.io/):

The model was trained for 50 Epochs with learning rate of 0.003

And if the loss is constant or increasing for 3 iterations then the model is assumed to be trained!








