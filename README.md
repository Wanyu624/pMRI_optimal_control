# Calibration-less_pMRI_optimal_control

# Requirements

The code was implementated on Window 10 via tensorflow-gpu 1.10.0, python 3.6.10

# Training

For training the network, simply use

```pMRI-CNet-K-optimal_control.py```


# Testing

The reconstruction process is automatically start after training process stopped for certain epochs.
We provided the learned weights that has already trained, you can just delete the training part in the code.
The output are 15 recontructed knee images as ```*.mat```.
