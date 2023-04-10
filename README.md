# Image-caption-genrator-using-CNN-and-LSTM

##PROBLEM STATEMENT
The objective of the project is to predict the captions for the input image. 
The dataset consists of 8k images and captions for each image.The features are extracted from both the image and the text captions for input.
The features will be concatenated to predict the next word of the caption. CNN is used for images and LSTM is used for text. 
BLEU Score is used as a metric to evaluate the performance of the trained model.

##DATASET
Flickr8k_Dataset: Contains 8092 photographs in JPEG format.

Flickr8k_text: Contains a number of files containing different sources of descriptions for the photographs.

Flickr_8k_text folder contains file Flickr8k.token which is the main file of our dataset that contains image name and their respective captions separated by newline(“\n”).

The image dataset is divided into 6000 images for training, 1000 images for validation and 1000 images for testing.

Here, we will break down the module into following sections for better understanding:

•	Pre-processing of Image

•	Creating the vocabulary for the image

•	Train the set

•	Evaluating the model

•	Testing on individual images
