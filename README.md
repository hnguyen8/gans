# DCGAN for Numerical Simulation
A DCGAN model is trained on a Simulation of thermal convection and outputs a 256 x 256 fake image of the simulation.
For more details, see the [jupyter notebook](https://github.com/hnguyen8/gans/blob/main/DCGAN_sim_2.ipynb).
# Environment
The jupyter notebook was implemented to run in Google Colab, and was given access to user's Google Drive. Inputs and Outputs are saved in their Drive. 
# Real Images
The first sub-images of the GIF are the training set. The remaining plots are 4 statistical moments (mean, variance, skewness, kurtosis), which are the standard for assessing the quality of the fake images later. 
![](https://github.com/hnguyen8/gans/blob/e5411c5838d6969b4dc66f828aa08e31ffd3d509/Real_images_gif.gif)
# Fake Images
he first sub-images of the GIF are the fake images produced by the model within the first 1000 epochs. The remaining plots are 4 statistical moments. A convincing fake image should have very similar statistical moments to the real images. 
![](https://github.com/hnguyen8/gans/blob/0227e52fe7964d608e4224f7c98ba53b8d041309/FAKE_first_thousand_epochs.gif)
# Reference
Losely based on
1. [DCGAN to generate face images by fchollet](https://keras.io/examples/generative/dcgan_overriding_train_step/)
2. [DCGAN256 by Daniel Klöck](https://github.com/dkk/DCGAN256/blob/master/README.md)
