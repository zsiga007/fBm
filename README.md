# fBm
Fractional Brownian Motion approached by Machine Learning for the M2R project.

In the 'Finding H with NN regression' folder we propose a neural network which can approximate the H-parameter of fBm. Testing on a dataset consisting of 
50000 fBm-s with randomly generated H parameters between 0 and 1, with allowed maximal difference in the predicted and true H being 0.04 gives around 90%
accuracy.

In the 'Testing time series for fBm' we propose a CNN approach to decide if a time series is a fBm.
