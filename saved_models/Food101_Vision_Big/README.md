Food101 Vision Big from the course, fit with all of the data from the Food101 dataset.
75,750 training images and 25,250 testing images.

Steps:
* Using TensorFlow Datasets to download and explore data
* Creating preprocessing function for the data
* Batching & preparing datasets for modelling (from tf.data API, prefetch and parallel computing)
* Creating modelling callbacks (earlyStopping, checkpointCallback, reduceLRonPlateau)
* Setting up mixed precision training (for faster learning)
* Building a feature extraction model
* Fine-tuning the feature extraction model
