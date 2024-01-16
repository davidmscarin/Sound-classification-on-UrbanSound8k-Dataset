## ML2 Project 1 - UrbanSound8k Classification


This project was developed for the Aprendizagem Computacional 2 course.
These notebooks document every step of the work developed from data extraction, training and evaluating various networks and experimenting.
We decided to use two different approaches for our networks: an RNN and a CNN, each one using a different kind of input data extracted from the dataset. The notebooks document our experiments with various combinations of architectures and parameters.
Finally, we end by attempting to build an ensemble learning model that combines the two kinds of networks. It should be noted that this attempt was made before final adjustments and conclusions, and wasn't pursued any further than its first iteration because of its lack of better showings and time/computational power requirements.

Notebooks should be read as follows:
1. data_extraction.ipynb - code for extracting the spectrograms and Mel frequency cepstral coefficients used as training data for the networks 
2. CNNexperiment.ipynb - building and training several CNN'S using spectrogram data (different VGG based architectures)
3. RNN.ipynb - building and training several RNN's using mfcc data (our own architectures)
4. ensemble.ipynb - combining networks from both experiments into an ensemble model which was trained with both kinds of data


The dataset files are not included in this delivery package but the histories and scores respective files for the trained RNN's were kept and sent (if there's any curiosity in changing the k-fold plots in the notebook).
