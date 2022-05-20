# DCGAN for Numerical Simulation
A DCGAN model is trained on a Simulation of thermal convection and outputs a 256 x 256 fake image of the simulation.
For more details, see the [jupyter notebook](https://github.com/hnguyen8/gans/blob/main/DCGAN_sim_2.ipynb).
# Environment
The jupyter notebook was implemented to run in Google Colab, and was given access to user's Google Drive. Inputs and Outputs are saved in their Drive. 
# Real Images
The first sub-images of the GIF are not directly used for training. The grayscale, 256x256-cropped version of these images are given as training material for the DCGAN model. The remaining plots are 4 statistical moments (mean, variance, skewness, kurtosis), which are the standard for assessing the quality of the fake images later. 
![](https://github.com/hnguyen8/gans/blob/7f6da09cfbef41825f4dbed3b9c0e714b71d3ed7/Real_images_gif.gif)
# Fake Images
The DCGAN model generates fake images in binary values, which was then plotted with cool-warm-color-scheme for illustration purpose only. The first sub-images of the GIF are the fake images produced by the model within the first 2,000 epochs. The remaining plots are 4 statistical moments. A convincing fake image should have very similar statistical moments to those of a real image. 
![](https://github.com/hnguyen8/gans/blob/df065cb02c874e9384af3127d8803a4cb9e028b0/FAKE_first_2000_epochs.gif)
# Reference
Losely based on
1. [DCGAN to generate face images by fchollet](https://keras.io/examples/generative/dcgan_overriding_train_step/)
2. [DCGAN256 to generate hands by Daniel Klöck](https://github.com/dkk/DCGAN256/blob/master/README.md)
