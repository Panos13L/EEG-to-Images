# EEG-to-Images
An idea of creating images from EEG signals.

First we slice the signal into windows (3 seconds in this case).

Then we extract features from EEG signals (Differential Entropy for Theta, Alpha, Beta bands).

Then, we create images from this features & we can use them for other tasks (like classification).
