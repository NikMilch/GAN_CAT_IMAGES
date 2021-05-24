# GAN_CAT_IMAGES
DEEP LEARNING 

GAN models generate new samples that comes from existing distribution of samples - for example generating image that is similar, but specifically different for the existing dataset. Gan models are compiled from tew neuron networks that compete each other (zero-sum game). The main idea is training the discriminator "indirectly". The discriminator is being updated dynamically the generator is used not to train to minimize the distance to the specific image, but rather to fool the discriminator.

### Packages ###
- numpy 
- matplotlib
- tensorflow 
- keras - Sequential
- keras.layers - Dense, LeakyReLU, Reshape, Conv2DTranspose, Conv2D, Dropout, Flatten, BatchNormalization
- keras.models - RMSprop, Adam
- os, datetime, cv2
- tensorflow.keras.callbacks - TensorBoard

### Additional notes ###

More epoches needs for better resolution of the images 
