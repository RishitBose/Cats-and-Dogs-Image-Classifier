# Cats-and-Dogs-Image-Classifier
This repository has a neural network model that classifies images of cats and dogs of size 256x256.

The data to train this neural network has been taken from here: https://storage.googleapis.com/mledu-datasets/cats_and_dogs_filtered.zip

I did not train the Neural Network from scratch and instead used Transfer Learning. I used EfficientNet V2 as the backbone. Link to EfficientNet V2: https://tfhub.dev/google/imagenet/efficientnet_v2_imagenet21k_xl/feature_vector/2


**Current Issues**

1. Neural Network only works on images that are 256x256x3. Trying with other size images using numpy's resize function distorts the image in a weird way which drastically reduces accuracy. 
