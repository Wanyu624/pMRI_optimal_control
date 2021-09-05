# Calibration-less_pMRI_optimal_control
This work aims at developing a novel calibration-free fast parallel MRI (pMRI) reconstruction method incorporate with discrete-time optimal control framework. The reconstruction model is designed to learn a regularization that combines channels and extracts features by leveraging the information sharing among channels of multi-coil images. We propose to recover both of magnitude and phase information by taking advantage of structured multiplayer convolutional networks in  image and Fourier spaces.

# Requirements

The code was implementated on Window 10 via tensorflow-gpu 1.10.0, python 3.6.10

# Training

For training the network, simply use

```pMRI-CNet-K-optimal_control.py```


# Testing

The reconstruction process is automatically start after training process stopped for certain epochs.
We provided the learned weights that has already trained, you can just comment the training part in the code.
The output are 15 recontructed knee images as ```*.mat```.
